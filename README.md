# LocalMusic AI

**Create music with AI, entirely on your Mac.**

LocalMusic AI is a native macOS application that generates original music on-device using Apple Silicon. Powered by the [ACE-Step 1.5](https://github.com/ace-step/ACE-Step-1.5) latent diffusion model and the [MLX](https://github.com/ml-explore/mlx) framework, it produces full songs from text descriptions — no cloud, no subscriptions, no data leaving your machine.

## Features

- **Text-to-Music Generation** — Describe genre, mood, instruments, and tempo. Add lyrics. The AI composes, arranges, and produces a complete track.
- **100% On-Device** — Runs natively on Apple Silicon GPU via MLX. ~60 seconds of audio in ~11 seconds on M-series chips.
- **Free Cloud Generation** — Optionally generate via the [ACE Music API](https://acemusic.ai/) without downloading any models. Free API keys available.
- **Stem Separation** — Split any song into vocals and accompaniment using a built-in neural Spleeter model.
- **Music Video Generator** — Create visualizer videos synced to your tracks with real-time Metal shader rendering.
- **LoRA Style Adapters** — Apply community style personas (jazz, lo-fi, orchestral, metal) and blend them.
- **Voice Personas** — Train custom LoRA adapters on vocal samples to generate music in a specific voice or style.
- **Audio Editor** — Trim, crop, and adjust generated tracks before exporting.
- **Privacy First** — No analytics, no tracking, no accounts. Everything stays in your Mac's sandboxed container.

## System Requirements

| | Minimum |
|---|---|
| **macOS** | 15.0 (Sequoia) or later |
| **Chip** | Apple Silicon (M1 or later) |
| **RAM** | 16 GB (32 GB recommended) |
| **Storage** | ~5 GB for the AI model |

The AI model (~4 GB) is downloaded from Hugging Face on first launch and cached locally.

## Built With

- [ACE-Step 1.5](https://github.com/ace-step/ACE-Step-1.5) — Latent diffusion model for music generation
- [MLX](https://github.com/ml-explore/mlx) — Apple's machine learning framework for Apple Silicon
- [ACE Music](https://acemusic.ai/) — Free cloud generation API
- SwiftUI + Metal — Native macOS UI with GPU-accelerated shader visualizers

## Links

- [Website](https://fspecii.github.io/LocalMusicAI/)
- [Privacy Policy](https://fspecii.github.io/LocalMusicAI/privacy.html)
- [Support](https://fspecii.github.io/LocalMusicAI/support.html)

## Author

**Valentin Neagu**

- [X / Twitter](https://x.com/AmbsdOP)
- [YouTube](https://www.youtube.com/@Ambsd-yy7os)
- [GitHub](https://github.com/fspecii)

## License

All rights reserved. Copyright 2025 Valentin Neagu.

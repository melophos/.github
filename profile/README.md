<h1 align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/melophos/melophos/main/assets/brand/melophos-wordmark-dark.svg">
    <img src="https://raw.githubusercontent.com/melophos/melophos/main/assets/brand/melophos-wordmark-light.svg" alt="MELOPHOS" width="440">
  </picture>
</h1>

**Song made visible.** An open instrument learning platform: a small hub lights up the notes to play on a keyboard or guitar, captures every note played and turns practice into data you own.

- **Light-guided practice** with Melody, Rhythm and Listen modes
- **Any instrument** over USB-MIDI, Bluetooth MIDI, MIDI jacks or audio, described by open profiles
- **Practice data on your own server**: streaks, accuracy, tempo progress and per-key heatmaps
- **Accessibility first**: guidance on one flat line, colour never the only signal, visual timing cues
- **Open hardware and software**: CERN-OHL-S boards, AGPL code, self-hosted with Docker

## Repositories

| Repository | What it is |
| --- | --- |
| [melophos](https://github.com/melophos/melophos) | The monorepo where all development happens. Start here |
| [firmware](https://github.com/melophos/firmware) | ESP32-S3 hub firmware in C++ |
| [hardware](https://github.com/melophos/hardware) | KiCad designs for the hub, octave LED bars and fret bar |
| [core](https://github.com/melophos/core) | Scoring engine in Rust, for the browser and the server |
| [server](https://github.com/melophos/server) | Self-hostable FastAPI server and Docker Compose stack |
| [studio](https://github.com/melophos/studio) | Browser app for practice, songs and hub setup |
| [client](https://github.com/melophos/client) | Python client and a hub simulator |
| [profiles](https://github.com/melophos/profiles) | Instrument profiles and their schema |
| [docs](https://github.com/melophos/docs) | Architecture, protocol, roadmap and guides |

Every component repository is a read-only copy published from the monorepo. Issues, discussions and pull requests all go to [melophos/melophos](https://github.com/melophos/melophos).

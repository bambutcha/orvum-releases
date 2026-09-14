<div align="center">

# ORVUM

**Multiplayer voxel sandbox** — explore, build, and play together.

[![Latest release](https://img.shields.io/github/v/release/bambutcha/orvum-releases?include_prereleases&style=for-the-badge&label=RELEASE)](https://github.com/bambutcha/orvum-releases/releases)
[![Downloads](https://img.shields.io/github/downloads/bambutcha/orvum-releases/total?style=for-the-badge&label=DOWNLOADS)](https://github.com/bambutcha/orvum-releases/releases)
[![Platform](https://img.shields.io/badge/PLATFORM-Linux%20x86__64-1a1a1a?style=for-the-badge)](https://github.com/bambutcha/orvum-releases/releases)

<br />

**[↓ Download](https://github.com/bambutcha/orvum-releases/releases)** ·
**[Release notes](https://github.com/bambutcha/orvum-releases/releases)**

</div>

---

## Play

1. Open **[Releases](https://github.com/bambutcha/orvum-releases/releases)** and take the newest **player** build.
2. Unpack the archive.
3. Run `./Orvum`.

| Package | What it is |
|--------:|------------|
| Player (`orvum-linux-…`) | Launcher + game client |
| Server (`orvum-server-…`) | Dedicated / VPS host |

Always use the assets attached to a release — this repository is the download channel, not a source tree.

### Requirements

- **OS:** Linux (x86_64)
- **GPU:** Vulkan-capable driver
- **Network (optional):** UDP for multiplayer / Open to LAN

---

## Features

- Flat voxel world — break and place blocks
- Movement with collision, jump, and world bounds
- **Multiplayer** — Join by IP, Open to LAN, remote players & nameplates
- Host **view distance** settings (render / simulation)
- Long-range world streaming without freezing the simulation tick
- Horizon fog that hides the render edge
- Single entry point: `Orvum` (client lives under `lib/`)

More systems (inventory, crafting, creatures, combat) are on the roadmap.

---

## Saves

| | Path |
|--|------|
| Default | `~/.local/share/orvum` |
| Override | `ORVUM_DATA_DIR` |
| Portable | `data/` next to the binary |

---

## Multiplayer (quick)

1. Host: **Play** → Esc → **Open to LAN** → show address if needed  
2. Friend: **Multiplayer** → **Join** → `IP:port`

Dedicated hosts use the server package from the same release.

---

## Versioning

Releases follow SemVer-style tags (`vMAJOR.MINOR.PATCH` + optional `-alpha` / `-beta`).

- Badges and links above always track **whatever is newest** on this repo
- No need to edit this README when a new build ships — publish a Release, attach binaries, done

---

## License & source

Game binaries and assets distributed here are provided for playing and testing.

Source development happens in a separate private repository. Redistribution of builds without permission is not allowed unless a release states otherwise.

---

<div align="center">

**Orvum** · made by [bambutcha](https://github.com/bambutcha)

[Releases](https://github.com/bambutcha/orvum-releases/releases) · [Issues](https://github.com/bambutcha/orvum-releases/issues)

</div>

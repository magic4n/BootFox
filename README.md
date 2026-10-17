<p align="center">
  <img src="icon.svg" width="140" alt="BootFox Studio logo"/>
</p>

<h1 align="center">BootFox Studio</h1>

<p align="center">
  <b>Custom Android firmware studio: builds, ports and curated downloads.</b>
</p>

<p align="center">
  <a href="LICENSE"><img alt="License: GPL-3.0" src="https://img.shields.io/badge/License-GPL--3.0-red.svg"/></a>
  <img alt="Platform" src="https://img.shields.io/badge/Platform-Android-3DDC84.svg"/>
  <img alt="Devices" src="https://img.shields.io/badge/Devices-Xiaomi-FF6900.svg"/>
  <img alt="Status" src="https://img.shields.io/badge/Status-Active-FFD400.svg"/>
  <a href="https://github.com/magic4n/BootFox"><img alt="Repo" src="https://img.shields.io/badge/GitHub-magic4n%2FBootFox-black.svg"/></a>
</p>

---

## Overview

**BootFox Studio** is a studio for creating and porting custom Android firmware. We build ready-to-flash images and port projects to new devices, based on established ROMs and, in some cases, on community GSIs.

Our work is focused on **Xiaomi** devices for now, and we are actively developing **FoxRunner**, a tool that will let anyone build firmware on their own machine.

## Supported Firmware

BootFox Studio works with and ports the following projects:

- **LineageOS**
- **LunarisAOSP**
- **HyperOS**
- **PixelOS**
- **crDroid**
- **ColorOS**
- **EvolutionX**
- **InfinityOS**
- and other community ROMs

Each project keeps its own upstream credits. BootFox Studio does not claim ownership of any upstream code.

## Roadmap

| Stage | Item | Status |
|------:|------|:------:|
| 1 | Xiaomi firmware builds | In progress |
| 2 | Public portal with downloads and mirrors | In progress |
| 3 | Structured firmware catalog | Planned |
| 4 | **FoxRunner**: self-service build tool | In development |
| 5 | Expanded device coverage | Planned |

## Repository Structure

```
BootFox/
├── icon.svg        # Project logo
├── LICENSE         # GNU General Public License v3.0
├── README.md       # This file
├── portal/         # Download portal: links to firmware builds
└── catalog/        # Firmware catalogs, one folder per project
```

### `portal/`

The portal contains links to BootFox Studio firmware builds. Downloads are hosted on our own mirrors, which are provided through HTML index pages by **foxer** and **magic4n**.

### `catalog/`

The catalog holds firmware catalogs. Each firmware project has its own folder, and each folder contains the catalog for that project. Browse the folders to find the builds you need.

## Mirrors

Firmware builds are mirrored by:

- **foxer**
- **magic4n**

Always verify checksums before flashing any image.

## Disclaimer

**Please read this section carefully before flashing anything.**

- BootFox Studio is an independent project. It is **not affiliated with, endorsed by, or sponsored by** Google, LineageOS, Xiaomi, or any other company, brand, or project mentioned in this repository. All trademarks belong to their respective owners.
- Flashing custom firmware can **void your warranty**, may **brick your device**, and can lead to **data loss**. You do it entirely at your own risk.
- Back up your data before installing anything.
- Builds are provided **"as is"**, without warranty of any kind. See the [LICENSE](LICENSE) for details.

## Contributing

Contributions are welcome:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/your-change`.
3. Commit your changes with clear messages.
4. Open a pull request describing what you changed and why.

Please keep all contributions, including documentation, in English.

## License

BootFox Studio is free software, released under the **GNU General Public License v3.0**. See [LICENSE](LICENSE) for the full text.

Copyright (C) 2026 foxer, magic4n

---

<p align="center">
  <sub>Built with 🦊 by the BootFox team</sub>
</p>

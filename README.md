````markdown
# Lab

A curated collection of projects built with AI assistance.  
Each project lives as an independent repository, organized through Git submodules.

> Every project was developed with AI unless explicitly marked otherwise.

---

# Projects

| # | Project | Description | AI | Stack |
|:-:|---------|-------------|:--:|-------|
| 1 | [tg-manager](https://github.com/GustavoNaldoni1/tg-manager) | Global CLI for Telegram — conversations, files, encryption, and reports | Yes | Python · Telethon · Fernet |
| 2 | [pixelcodec](https://github.com/GustavoNaldoni1/pixelcodec) | Store any file as a video on YouTube using binary encoding with Reed-Solomon error correction | Yes | Python · ffmpeg · NumPy · OpenCV · Reed-Solomon |
| 3 | [localfinder](https://github.com/GustavoNaldoni1/localfinder) | Find the best route between two points — walking, driving, motorcycle, or public transit | Yes | Python · OSRM · Nominatim · folium |
| 4 | [optimus-cli](https://github.com/GustavoNaldoni1/optimus-cli) | Global CLI for Windows 10/11 optimization — 50+ scripts across 13 categories including cleanup, gaming, privacy, and performance | Yes | Python · PowerShell |
| 5 | [apps](https://github.com/GustavoNaldoni1/apps) | Collection of desktop automation tools and workflow utilities for Windows | Yes | Python · pyautogui · PowerShell · ctypes |
| 6 | [clienter-tas](https://github.com/GustavoNaldoni1/clienter-tas) | Global TAS CLI for recording, editing, executing, and managing frame-by-frame inputs | Yes | Python · pynput · argparse |
| 7 | [permasave](https://github.com/GustavoNaldoni1/permasave) | Permanent cloud storage CLI using GitHub Gists with optional authenticated encryption | Yes | Python · hashlib · hmac · base64 · urllib |

---

# Structure

```text
lab/
├── README.md
├── .gitmodules
├── tg-manager/
│   └── Telegram Manager CLI
├── pixelcodec/
│   └── PixelCodec Video Storage
├── localfinder/
│   └── Route Finder CLI
├── optimus-cli/
│   └── Windows Optimization Suite
├── apps/
│   └── Desktop Automation Collection
├── clienter-tas/
│   └── Tool-Assisted Speedrun CLI
└── permasave/
    └── Permanent Storage CLI
````

Each directory is a standalone repository linked as a Git submodule, maintaining its own history, dependencies, and license.

---

# Submodules

| Submodule    | Repository                                                                      | Status |
| ------------ | ------------------------------------------------------------------------------- | :----: |
| tg-manager   | [GustavoNaldoni1/tg-manager](https://github.com/GustavoNaldoni1/tg-manager)     | Active |
| pixelcodec   | [GustavoNaldoni1/pixelcodec](https://github.com/GustavoNaldoni1/pixelcodec)     | Active |
| localfinder  | [GustavoNaldoni1/localfinder](https://github.com/GustavoNaldoni1/localfinder)   | Active |
| optimus-cli  | [GustavoNaldoni1/optimus-cli](https://github.com/GustavoNaldoni1/optimus-cli)   | Active |
| apps         | [GustavoNaldoni1/apps](https://github.com/GustavoNaldoni1/apps)                 | Active |
| clienter-tas | [GustavoNaldoni1/clienter-tas](https://github.com/GustavoNaldoni1/clienter-tas) | Active |
| permasave    | [GustavoNaldoni1/pms-cli](https://github.com/GustavoNaldoni1/permasave)         | Active |

---

# Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/GustavoNaldoni1/lab.git
```

---

# Convention

* All projects must be added as Git submodules pointing to their own repositories
* Projects not built with AI are marked with `No` in the `AI` column
* Each submodule maintains its own `README.md` and `LICENSE`
* Projects should be self-contained and independently installable
* CLI tools should provide a consistent user experience and storage structure when applicable

---

# License

Each submodule has its own license.
This repository serves as an organizational index only.

```
```

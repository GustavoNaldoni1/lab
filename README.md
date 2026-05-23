````md
# Lab

A curated collection of projects built with AI assistance.  
Each project lives as an independent repository, organized here through Git submodules.

> Every project was developed with AI unless explicitly marked otherwise.

---

## Projects

| # | Project | Description | AI | Stack |
|:-:|---------|-------------|:--:|-------|
| 1 | [tg-manager](https://github.com/GustavoNaldoni1/tg-manager) | Global CLI for Telegram — conversations, files, encryption, reports | Yes | Python · Telethon · Fernet |

---

## Structure

```text
lab/
├── README.md
├── .gitmodules
└── tg-manager/
    └── Telegram Manager CLI
```

Each directory is a standalone repository linked as a submodule, maintaining its own history, dependencies, and license.

---

## Submodules

| Submodule | Repository | Status |
|-----------|------------|:------:|
| tg-manager | [GustavoNaldoni1/tg-manager](https://github.com/GustavoNaldoni1/tg-manager) | Active |

---

## Clone with Submodules

```bash
git clone --recurse-submodules https://github.com/GustavoNaldoni1/lab.git
```

---

## Convention

- All projects must be submodules pointing to their own repository
- Projects not built with AI are marked with `No` in the `AI` column
- Each submodule carries its own `README.md` and `LICENSE`

---

## License

Each submodule has its own license.  
This repository is an organizational index only.
````

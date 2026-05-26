# CURRENTLY RESOLVING ACCOUNT ISSUE, RELEASES SHOULD BE UP BY TOMORROW

# shitty-iso-dl

Automatically resolves and downloads the latest ISO for any of the listed Linux distributions. No more need to visit every single website for your private ISO archive.

Available as a CLI or a very primitive GUI.

---

## Download

Grab the latest release for your platform from the [Releases](../../releases) page.

| Platform | CLI | GUI |
|---|---|---|
| Windows | `shitty-iso-dl-cli.exe` | `shitty-iso-dl-gui.exe` |
| Linux | `shitty-iso-dl-cli` | `shitty-iso-dl-gui.AppImage` |

---

## Supported Distributions

**Arch family** — Arch, Manjaro KDE, CachyOS, EndeavourOS, Artix, Garuda Dr460nized, ArcoLinux, BlackArch

**Debian family** — Debian, Kali, ParrotOS, Tails, Devuan, Antix, MX Linux

**Ubuntu family** — Ubuntu, Kubuntu, Xubuntu, Lubuntu, Ubuntu MATE, Mint, Pop!\_OS, KDE Neon, Linux Lite, Trisquel

**Red Hat / Fedora family** — Fedora, Rocky, AlmaLinux, CentOS Stream, Qubes OS

**SUSE / Slackware / Mandriva** — openSUSE Tumbleweed, Slackware, Mageia, PCLinuxOS

**Independent & specialty** — Void, NixOS, Gentoo, Alpine, Deepin, ClearLinux, Puppy Linux, TinyCore, GoboLinux, KaOS, Calculate Linux, Grml, SystemRescue, Proxmox VE, TrueNAS SCALE

---

## Run from Source

Requires Python 3.x. No third-party dependencies. (Thank you Tkinter my beloved)

```bash
# CLI
python src/cli.py

# GUI
python src/gui.py
```

---

## Usage

**CLI** — prompts for a destination directory, then shows a numbered list of distros. Enter individual numbers separated by commas, or `A` for all.

**GUI** — select a destination folder, pick one or more distros from the list, hit Download. Skips files that already exist.

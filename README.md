# Ritual downloads

Installers for [Ritual](https://ritual-site.developer-amanuel.workers.dev), a calm, private
app for habits, a journal, tasks, notes, and focus. This repository holds only the
installers; there's no code here.

Get the newest version from **[Releases](../../releases/latest)**.

## Linux (64-bit)

| File | For | Install |
| --- | --- | --- |
| `Ritual_x86_64.AppImage` | Any distribution | `chmod +x Ritual_x86_64.AppImage && ./Ritual_x86_64.AppImage` |
| `Ritual_amd64.deb` | Ubuntu, Debian, Mint, Pop!_OS | `sudo apt install ./Ritual_amd64.deb` |
| `Ritual_x86_64.rpm` | Fedora, openSUSE, RHEL | `sudo dnf install ./Ritual_x86_64.rpm` |

Or straight from a terminal:

```sh
wget https://github.com/1-aminadab/ritual-releases/releases/latest/download/Ritual_amd64.deb
sudo apt install ./Ritual_amd64.deb
```

Ubuntu 22.04 or later (or a distribution from 2022 onward). The AppImage needs FUSE 2:
`sudo apt install libfuse2` (on Ubuntu 24.04: `libfuse2t64`).

Ritual updates itself after that: the AppImage quietly, the .deb and .rpm after asking.

Mac and Windows are coming soon.

# Running Wolf3D on Debian

## Overview

Play classic DOS games on modern Linux systems using DOSBox emulation with FreeDOS.

## Quick Start

Start with Wolfenstein 3D by id Software.

Install DOSBox:

```bash
sudo apt install dosbox
```

For more information, visit <https://www.dosbox.com/>

## Full Screen Configuration

Edit `~/.dosbox/dosbox-0.74-3.conf` and update the `[sdl]` section:

```bash
fullresolution=desktop
windowresolution=desktop
output=overlay
```

## TODO

- [ ] Wolf3D
- [ ] Doom
- [ ] Dockerize setup

## Run

```bash
dosbox ./wolf3d/WOLF3D.EXE
```

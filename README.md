# Deadlock Competitive Config

Optimized for minimum input lag and maximum stable FPS on Source 2.

## System Tested On
- GPU: RTX 4080
- CPU: Ryzen 7 7800X3D
- RAM: 64 GB DDR5
- Monitor: 1080p 360Hz
- NVCP FPS Cap: 357 | Reflex: On

## What's Included
- **gameinfo.gi** → Replace file in `Steam\steamapps\common\Deadlock\game\citadel\gameinfo.gi`
- **video.txt** → Replace file in `Steam\steamapps\common\Deadlock\game\citadel\cfg\video.txt`

## Setup
1. Download both files
2. Back up your original `gameinfo.gi` and `video.txt`
3. Replace both files with the downloaded versions
4. Edit `video.txt` lines marked with `[CHANGE]` to match your system (resolution, refresh rate, VendorID, DeviceID, RAM, VRAM)
5. Set both files to **read-only** (right-click → Properties → Read-only) to prevent the game from overwriting them
6. Do NOT change in-game graphics settings after applying

## Recommended Launch Options

## Notes
- If you use DLSS, keep `r_citadel_antialiasing` at `0` in video.txt (DLSS has built-in AA)
- If you use native render, set `r_citadel_upscaling` to `0` and `mat_viewportscale` to `1`
- After a Deadlock update, check if `gameinfo.gi` was reset — if so, replace it again

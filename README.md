# Deadlock Competitive Config
**Optimized for: Min. Input Lag | Max. Stable FPS on Deadlock.**

---

## 📦 What's Included

| File | Location |
|------|----------|
| `gameinfo.gi` | `Steam\steamapps\common\Deadlock\game\citadel\gameinfo.gi` |
| `cfg/video.txt` | `Steam\steamapps\common\Deadlock\game\citadel\cfg\video.txt` |
| `addons/pak99_dir.vpk` | Yellow enemy outline mod → `Steam\steamapps\common\Deadlock\game\citadel\addons\` |

---

## ⚙️ Setup

1. Download all files
2. Back up your original `gameinfo.gi` and `video.txt`
3. Replace `gameinfo.gi` and `video.txt` with the downloaded versions
4. Place `pak99_dir.vpk` inside the `addons` folder *(create the folder if it doesn't exist)*
5. Edit `video.txt` — fill in the lines marked with `[CHANGE]` to match your system:

| Setting | Value |
|---------|-------|
| `VendorID` | NVIDIA = `4318` · AMD = `4098` · Intel = `32902` |
| `DeviceID` | Copy from your original video.txt |
| `setting.mem_level` | 4–8GB RAM = `1` · 12–16GB = `2` · 24GB+ = `3` |
| `setting.gpu_mem_level` | 2–4GB VRAM = `1` · 6–8GB = `2` · 12GB+ = `3` |
| `setting.defaultres` | Your monitor width (e.g. `1920`) |
| `setting.defaultresheight` | Your monitor height (e.g. `1080`) |
| `setting.recommendedheight` | Same as `defaultresheight` |
| `setting.refreshrate_numerator` | Your monitor Hz (e.g. `144`, `240`, `360`) |
| `setting.r_citadel_upscaling` | No upscaling = `0` · FSR2 = `2` · DLSS = `4` |
| `setting.r_citadel_dlss_settings_mode` | DLSS Off = `0` · DLSS On = `1` |
| `setting.r_dlss_preset` | CNN = `0` · Transformer = `10` |

> 💡 **DLSS Preset:** RTX 4000 & 5000 series → use Transformer (`10`) · All other GPU cards → use CNN (`0`)

> ⚠️ **DeviceID** is unique to your GPU model. Open your original `video.txt` before replacing it and copy the value exactly. Do NOT leave it as `????`.

> 📁 How to find your original video.txt: `Steam\steamapps\common\Deadlock\game\citadel\cfg\video.txt`

6. Set `gameinfo.gi` and `video.txt` to **Read-only** to prevent the game from overwriting them → Right-click → Properties → check Read-only → Apply
7. ⚠️ **Do NOT change in-game graphics settings after applying** — it will overwrite your `video.txt`

---

## 📝 Notes

- 🔄 After a Deadlock update, check if `gameinfo.gi` was reset — if so, replace it again
- 🟡 The yellow outline mod (`pak99_dir.vpk`) is optional — remove it from addons if you prefer default outlines

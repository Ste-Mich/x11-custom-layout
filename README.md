
# 🇨🇿 Czech Colemak-DH X11 Keyboard Layout

A custom **X11 (XKB) keyboard layout** I made for x11 on Linux, based on **Colemak-DH** with a Czech symbols.  
Designed for comfortable typing with **CapsLock as a modifier layer**.  

<img width="1221" height="359" alt="image" src="https://github.com/user-attachments/assets/ee89db68-6103-45a1-b888-e10ac86e3c0b" />

<sub>(Layout image made with this handy [website](https://keyboard-layout-editor.com/))</sub>

## ✨ Features

- **Colemak-DH + Czech support** - type with one of the best layouts :)
- **CapsLock modifier** - arrow key, backspace, delete, home, end, page up & down without moving your hands
- **Mods included:**
  - 🔄 **Curl Mod** - more ergonomic home row key placement
  - ⤴️ **Angle Mod** - better wrist alignment on left hand
  - ↔️ **Wide Mod** - extra spacing between hands
 
## 📂 Installation

Download the file inside symbols, you can name it anything.

``` bash
# Copies the custom layout to other system pre-installed layouts. (needs to be re-run after an update)
sudo install -m 664 ~/Downloads/ss /usr/share/X11/xkb/symbols/

# Sets the current keyboard to 3 layouts with shortcut to toggle them.
# You can put this to .xprofile or .xinitrc depending on your system
setxkbmap -layout "cz,ss,us" -option "grp:alt_shift_toggle"
```

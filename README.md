## ROFI SCREENSHOT (use maim, xclip)

Based on [rofi-screenshot](https://github.com/ceuk/rofi-screenshot)

## Installation

Install dependencies

```
sudo pacman -S rofi maim xclip xdotool
```

> [!TIP]
> You can install dependencies with your package manager.

Clone the repository

```
git clone https://github.com/warmdev17/Rofi_Screenshot
cd Rofi_Screenshot
chmod u+x rofi-screenshot
sudo mv rofi-screenshot /usr/local/bin/
```

## Usage (example on i3wm)

```
bindsym $alt+Print exec rofi-screenshot
```

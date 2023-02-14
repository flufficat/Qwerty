# Qwerty
A simple bash tool to copy a line from a file to the clipboard

# Usage
1. `qwerty <file>`
2. Select the line you want to copy or search for it in rofi.
3. Done. Just paste it.


# Dependencies
#### Xorg
- [rofi](https://github.com/davatorium/rofi)
- [xclip](https://github.com/astrand/xclip)

#### Wayland
  - [wofi](https://hg.sr.ht/~scoopta/wofi)
  - [wl-clipboard](https://github.com/bugaevc/wl-clipboard)

# Install
1. Download the `xorg-qwerty` script if you use Xorg or download the `wayland-qwerty` script if you use Wayland
2. Rename the script to `qwerty` or something else if you would like to
3. Run `chmod +x qwerty` (or whatever you changed it to)
4. Place the qwerty script into the PATH such as ~/.local/bin or /usr/local/bin
#### Optional steps
5. If you want to run it when you right-click on a file there is also a provided .desktop file and image for it.
Just put the .desktop file wherever you put them, typically ~/.local/share/applications
6. Then put the folder with the image in your data folder, typically ~/.local/share
If you are unsure where this is run `echo $XDG_DATA_HOME`

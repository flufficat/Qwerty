# Qwerty
A simple bash tool to copy a line from a file to the clipboard

# Dependencies
- [rofi](https://github.com/davatorium/rofi)
- [xclip](https://github.com/astrand/xclip)
  - If you use wayland get [wl-clipboard](https://github.com/bugaevc/wl-clipboard) edit the script to look like:
  ```
  #!/bin/bash
  echo -n $(cat "$1" | rofi -dmenu -l 25) | wl-copy
  ```

# Install
1. Place the qwerty script into the PATH such as ~/.local/bin or /usr/local/bin

2. If you want to run it when you right-click on a file there is also a provided .desktop file and image for it.
Just put the .desktop file whereever you put them, typically ~/.local/share/applications

3. Then put the folder with the image in your data folder, typically ~/.local/share
If you are unsure where this is run `echo $XDG_DATA_HOME`

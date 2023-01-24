# How to Install

0.1: sudo apt-get install rofi polybar git plank picom (adapt apt to your current package manager, pacman/yay if you are using Arch)
1. Clone this repository
2. Move fonts folder to .local/share/fonts (cp -r fonts $HOME/.local/share)
3. Move Polybar to .config (cp -r polybar $HOME/.config)
4. Move to polybar folder (cd .config/polybar) then bash launch.sh to make sure there's no problem
5. Set Polybar to Autostart (look it up yourself)
6. Move plank theme (dock.theme) to /usr/share/plank/themes (use sudo for this one)
7. Move picom to config file (cp -r picom.conf $HOME/.config/picom) and type picom to ensure it's running
8. Set the Wallpaper (and set it to zoomed) 
9. You're done basically.

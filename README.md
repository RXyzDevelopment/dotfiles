# How to Install

0.1: sudo apt-get install rofi polybar git plank picom unzip (adapt apt to your current package manager, pacman/yay if you are using Arch)
1. Clone this repository
2. Move fonts folder to .local/share/fonts (cp -r fonts $HOME/.local/share)
3. Move Polybar to .config (cp -r polybar $HOME/.config)
4. Move to polybar folder (cd .config/polybar) then bash launch.sh to make sure there's no problem
5. Set Polybar to Autostart (look it up yourself)
6. Move plank theme (dock.theme) to /usr/share/plank/themes (use sudo for this one)
7. Move picom to config file (cp -r picom.conf $HOME/.config/picom) and type picom to ensure it's running
8. Set the Wallpaper (and set it to zoomed) 
9. Unzip the themes (unzip -r themename.zip)
10. Move it to $HOME/.local/share/themes
11. Set your Theme on Appearance
12. Copy both hideIt.sh and hideitconfig.sh to your home directory
13. Now, set your hideitconfig.sh
14. Type xprop |grep WM_NAME (before doing this, please run polybar) and then press the polybar (doesn't matter where)
15. You get something like polybar-mybar-blablabla, copy this
16. Now, nano hideitconfig.sh, replace mybar-vga to your own variable and try running it, if the polybar dissapear, open another tab of terminal and type ./hideIt.sh --name (name of your polybar) --toggle if the polybar appeared, it worked and therefore, set the keybinding for it more information https://awesomeopensource.com/project/tadly/hideIt.sh#polybar-my-main-bar
17. You're done basically.


Distro: MX Linux
DE: XFCE
Bar: Polybar
Wallpaper: Bootleggers 

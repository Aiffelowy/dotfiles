# dotfiles
you my need to adjust some configs to your preference (especially file paths in rofi-launcher)



# THIS IS NOT MY RICE

source: https://github.com/anteczko/Nier-Automata-Rice

I just fixed it, ported it to bspwm and added some stuff



# dependencies
bspwm (obviously),
sxhkd,
picom,
kitty,
rofi,
conky,
imagemagick,
polybar,
nitrogen,
feh,
redshift (so your eyes won't explode)
# installation
copy fonts to $HOME/.fonts and run fc-cache -fv

copy the cursor to $HOME/.icons and then change the cursor theme in for example lxappearance

copy your preferred polybar config to $HOME/.config/polybar as config.ini and also copy launch there and make it executable

copy bspwmrc to $HOME/.config/bspwm/ and make it executable ; kitty.conf to $HOME/.config/kitty/ ; picom.conf to /etc/xdg

for rofi copy all the files somewhere, and then change the paths in the rofi-launcher script, then copy the script to /usr/bin

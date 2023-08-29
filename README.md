# My dwm Build

## Changes
- Fonts change to Jetbrains Mono Semibold:size=22
- Delete tags 5-9 since I rarely use them

## TODOs
- Notifications with [Dzen2](https://wiki.archlinux.org/title/Dzen) or [Lemonbar](https://wiki.archlinux.org/title/Lemonbar). Maybe take a look for [Dunst](https://wiki.archlinux.org/title/Dunst)
- Statusbar
    - Transparency 
    - Mouse on or click event for status on the right hand side. 
    - Display only the application name in the middle. 
- Wallpaper utilities, including:
    - Set wallpaper by [feh](https://wiki.archlinux.org/title/Feh)
    - Adjust the accent colors and colorschemes of dwm, st, zsh etc based on the wallpapaer 

## Known Issue
- Mouse input doesn't function after waking from system sleep.
- Firefox right click window unexpectedly trun transparent due to the compositor. Should check picom to fix, in particular the man and the config.

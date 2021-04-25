# kara dots

this repo has configs for two WMs, bspwm and awesome, and independent configs
for other programs that I use

## bspwm

bspwm uses `sxhkd`, `polybar`, `dunst`, `nitrogen`, `light`, `maim` and `picom`

setup is fairly minimal, font is iosevka term, not much to say about it, its
based on the EndeavourOS bspwm community config since thats the distro I use

## awesome

awesome config is based on ElenaPan's incredible config (`elenapan/dotfiles`) it's not configured
very well yet so I mainly just use my bspwm setup

## misc programs

### kitty

terminal is kitty. not much in the config currently, font is iosevka mayukai and
it loads one of the many themes from `~/.config/kitty/themes` (default is nord)

### zsh

shell is `zsh` with `oh-my-zsh` installed. also has autocomplete and syntax
highlighting, and I have a couple aliases setup for programs like `exa` and `neovim`

### neovim

neovim config is based on `rafi/vim-config`. not much to say there, actual local
config files are in `~/.config/nvim/config/`

### sxhkd

hotkey daemon for x. everything is in `~/.config/sxhkd/sxhkdrc`. there are some
ACPI key events in there that may not be necessary, and some stuff you may wanna
remove if you just use awesomewm or another non-tiling wm

### gtk

gtk themes are in ~/.themes, i just use lxappearance to change it

### rofi

i dont really remember what my rofi config is like, powermenu.sh is like a nice
power menu window or something

## useful stuff

### color-scripts

`~/.local/share/color-scripts` is a dir that contains a lot of scripts for
testing terminal colors, testing nerd font usage, and testing powerline font usage.

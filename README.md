![alt text](readme-resources/dotfiles.png)

### Hello there! :octocat:

Those are my different bspwm and (no longer supported) openbox themes dotfiles, hope you find something useful in this mess ^^

Specific rices configs and colorschemes are [here](https://github.com/zodd18/dotfiles/tree/master/themes) and general configuration files are [here](https://github.com/zodd18/dotfiles/tree/master/global-config). You will need both.

I hope you understand everything here. :wink:

Here are some details about my setup:
<a href="https://youtu.be/_PTp5mh5_vQ"><img src="readme-resources/cute-rice.webp" alt="" align="right" width="400px"></a>
- **WM**                           : [bspwm](https://github.com/baskerville/bspwm) :art: 4 changable themes/mode!
- **DM**                           : [getty](https://wiki.archlinux.org/index.php/Getty) :blossom: minimal DM!
- **Shell**                        : [zsh](https://wiki.archlinux.org/index.php/zsh) :shell: with [oh my zsh](https://github.com/ohmyzsh/ohmyzsh) framework!
- **Terminal**                     : [kitty](https://github.com/kovidgoyal/kitty) :cat:
- **Panel**                        : [polybar](https://github.com/polybar/polybar) :shaved_ice: using [nerd fonts](https://github.com/ryanoasis/nerd-fonts) glyphs as icons!
- **Compositor**                   : [compton](https://github.com/chjj/compton) :sparkles:
- **Notify Daemon**                : [Dunst](https://wiki.archlinux.org/index.php/Dunst) :leaves: minimalism!
- **Application Launcher**         : [Rofi](https://github.com/davatorium/rofi) :rocket: apps & sidebar menu!
- **File Manager**                 : [Thunar](https://wiki.archlinux.org/index.php/Thunar) :bookmark: customized sidebar & icon!
- **Text Editor**                  : [nvim](https://github.com/neovim/neovim) :computer:

<br/><br/><br/>

![alt text](readme-resources/themes.png)

## [Horizon](https://github.com/zodd18/Horizon)
![alt text](screenshots/Horizon.png)
![alt text](https://github.com/zodd18/Horizon/blob/master/screenshot.png) 


<br/><br/>

## [PinkNordAlternative](https://github.com/zodd18/PinkNordAlternative) [(Fleon based)](https://github.com/owl4ce/dotfiles)
![alt text](screenshots/Alternative-pinknord.png)
![alt text](https://github.com/zodd18/PinkNordAlternative/blob/master/screenshot.png) 


<br/><br/>

## [PinkNord](https://github.com/zodd18/PinkNord)
![alt text](screenshots/PinkNord.png)
![alt text](https://github.com/zodd18/PinkNord/blob/master/screenshot.png) 


<br/><br/>

## [Gruvbox](https://github.com/zodd18/Gruvbox)
![alt text](screenshots/Gruvbox.png)
![alt text](https://github.com/zodd18/Gruvbox/blob/master/screenshot.png) 

<br/><br/>

## [SolarizedDark](https://github.com/zodd18/SolarizedDark)
![alt text](screenshots/SolarizedDark.png)
![alt text](https://github.com/zodd18/SolarizedDark/blob/master/screenshot.png) 


<br/><br/>

# Custom Theme Swap Utility

## Click the brush icon
![alt text](./screenshots/brush_.jpg)

## Choose the rice that you desire
![alt text](screenshots/theme-swap-showcase.png)

## Nice! Now you have a completely look and feel for your Linux desktop!
![alt text](screenshots/theme-swap-showcase-2.png)

<br/><br/>

![alt text](readme-resources/scripts.png)

## [WARNING]: Installation scripts are still work in progress. Use them at your own risk!!
### [WARNING!]: These are my personal config files, executing these scripts will overwrite several files in your system, only execute these in case you have a backup of your files.

## Download
```
mkdir -p ~/Documents/git-lab && git clone https://github.com/zodd18/dotfiles.git ~/Documents/git-lab/dotfiles && cd ~/Documents/git-lab/dotfiles
```

## Executing the script
You can install one of them by running the setup executable.

Installing necessary packages:

[WARNING!]: Support for Arch Linux based systems only (installation via pacman).

Use:

```shell
./setup.sh <ARG> 
```

where 
```<ARG>```
may be:

```
pacman       - installs necessary packages from pacman
aur          - installs necessary packages from AUR and external sources
themes       - installs .themes, .icons, .fonts, wallpapers and necessary/personal scripts
```

You can also do:


```shell
./setup.sh <ARG> <THEME_NAME>
```

where 
```<ARG>```
may be:

```
rice         - installs <RICE_NAME> rice
all          - installs all at once: pacman packages, aur packages, GTK themes, etc. And finally installs <RICE_NAME> theme if this argument was passed
```

where 
```<RICE_NAME>```
may be:

```
nord                    - Classic Nord look
pink-nord               - Pink Nord look
pink-nord-alternative   - Based on Fleon look
gruvbox                 - Classic Gruvbox look
solarized-dark          - Solarized Dark look
horizon                 - Based on VS Code Horizon Theme 
```

example:

```
setup.sh all pink-nord
```
(this command would install all necessary packages, themes, icons and would install pink-nord rice)

### Recomendation
You can try to install all at once by using "all" argument, however I'd install it one by one in case any installation fails. 
I'd follow this order: pacman, aur, themes, rice.

# Deprecated (old rices, these need a lot of cleaning)
```
dracula                 - Classic Dracula look
doombox                 - Doom version of gruvbox
```


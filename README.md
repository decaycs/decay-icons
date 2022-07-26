# Decay Icons

This is a port of [Decay Colorscheme](https://github.com/decaycs) for [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme).

![demonstration](./assets/main.png)

## Requirements

Ensure [Papirus Icon Theme](https://github.com/PapirusDevelopmentTeam/papirus-icon-theme) is installed.

## Installation

```sh

# First, clone the repository and change location to the cloned directory:
$ git clone https://github.com/decaycs/decay-icons
cd decay-icons

# Copy the contents of the src directory to /usr/share/icons/Papirus
sudo cp -r src/* /usr/share/icons/Papirus

# Call the papirus-folders script to set the color of the folders to the desired theme.
./papirus-folders -C [color] --theme [theme]

# Decay color options: decay-red, decay-yellow, decay-green, decay-blue, decay-purple, decay-cyan
# Theme options: Papirus-Dark, Papirus-Light
```

## Applying

Set the `gtk-icon-theme` to the theme the icons were applied to during installation in `~/.config/gtk-3.0/settings.ini`. Example:

```ini
gtk-icon-theme-name=Papirus-Dark # or Papirus-Light
```
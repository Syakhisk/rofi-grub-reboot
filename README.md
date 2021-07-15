# Rofi-grub-reboot: A simple rofi-based grub-reboot wrapper.
Never wait for your computer to reboot just to forget selecting the correct OS again.
Perfect solution for multi-booted / dual-booted machines.

![demo](./demo.gif)

# Dependencies
- [GRUB2](https://help.ubuntu.com/community/Grub2)
- [nodejs](https://nodejs.org/en/)
- [rofi](https://github.com/davatorium/rofi)

# Installation
- Install nodejs using your package manager (make sure you installed [rofi](https://github.com/davatorium/rofi))
```
# Arch
pacman -S nodejs

# Ubuntu, *buntu
sudo apt install nodejs
```
- clone this github repo
  `git clone https://github.com/syakhisk/rofi-grub-reboot.git`
- Move `rofi-grub-reboot` to desired location eg: `~/.local/bin`
- Profit

# Usage
- Run `rofi-grub-reboot` either from terminal, keybinding, or rofi drun
- Select desired OS to be booted (one off boot, not permanent)
- Confirm with y/yes n/no (pressing enter will choose yes by default)

# Todo
- Port code to python/bash for portability.



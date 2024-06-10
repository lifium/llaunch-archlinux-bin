# Legacy Launcher (TL Legacy) for Arch Linux
## Not an official repo for Legacy Launcher, may change over time.
### Check out [Legacy Launcher](https://llaun.ch/en) for more info.
---
## Introduction:

Legacy Launcher is a simple, light and fast Minecraft Launcher. But, the problem many (or some) people may face is that it is not available on Arch Linux, e.g. in the AUR, nor in the official repos. Luckily, this git repo exists as a measure to alleviate those problems, at least to a certain degree. Now, this git repo provides the package file to install onto Arch Linux using the `pacman` package manager. Alternatively, the steps required to make the package oneselves will also be mentioned in this README.md file.

---

## Installation prerequisites:

1. Install Java: Open the terminal and enter `sudo pacman -S jre-openjdk` or `sudo pacman -S jdk-openjdk`. Select any option when given so; for example, if the default is 1, then press Enter. When said to proceed with the installation, press `Y`. When the installation is finished, follow any of the two steps given below:

## a) Installation:

1. Open any terminal emulator such as `xfce4-terminal`, `konsole`, `Alacritty`, `kitty`, `terminator` or just use the `tty` if that's the only option or if ssh'd into a machine.

2. Clone the repository: `git clone https://github.com/lifium/llaunch-archlinux-bin`

3. Go to folder to install the package: `cd llaunch-archlinux-bin`

4. Install the package: `sudo pacman -U legacylauncher-1.0-1-any.pkg.tar.zst`

---

## b) D.I.Y method:

1. Install debtap using `yay`, `paru` or `pacaur`. In this case, `yay` will be used.
Run `yay -S debtap` on your terminal and wait for the download to finish.
After t is installed, run `sudo debtap -U` once to update its repositories.

3. Download the `TL_legacy.deb` file from [here.](https://llaun.ch/ubuntu)

4. To make the package, cd into the directory in which you have downloaded the `TL_legacy.deb` file and run `sudo debtap TL_legacy.deb` and wait for the recompilation to finish

5. Install the package: `sudo pacman -U legacylauncher-159.7-1-any.pkg.tar.zst`

---

It ***should*** work. Now, go to the applications menu or launcher and search for "Legacy Launcher", or type `legacylauncher` in the terminal to launch the game. Enjoy!

P.S: Sorry for the grammar.

N.B: You might want to use the `jre` package from Oracle through the AUR, as the `jre-openjdk` JVM is malfunctioning on my system.

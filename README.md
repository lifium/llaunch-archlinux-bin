# Legacy Launcher (TL Legacy) for Arch Linux
## Not an official repo for Legacy Launcher, may change over time.
### Check out [Legacy Launcher](https://llaun.ch/en) for more info.
---
##Introduction:

Legacy Launcher is a simple, light and fast Minecraft Launcher. But, the problem many (or some) people may face is that it is not available on Arch Linux, e.g. in the AUR, nor in the official repos. Luckily, this repo exists as a measure to alleviate those problems, at least to a certain degree. Now, this repo provides the package file to install onto Arch Linux using the `pacman` package manager. Alternatively, the steps required to make the package oneselves will also be mentioned in this README.md file.

---

##Installation prerequisites:

1. Install Java: Open the terminal and enter `sudo pacman -S jre-openjdk`. Select any option when given so for example if the default is 1, then press Enter. When said to proceed with the installation, press `Y`. When the installation is finished, follow any of the two steps given below:

## a) Installation:

1. Open any terminal emulator such as `xfce4-terminal`, `Alacritty`, `termite`, `terminator` or just use the `tty` if that's the only option or if ssh'd into a machine.

2. Clone the repository: `git clone https://https://github.com/lifium/tl-legacy-launcher-archlinux-git `

3. Go to folder to install the package: `cd tl-legacy-launcher-archlinux-git`

4. Install the package: `sudo pacman -U legacylauncher-1.0-1-any.pkg.tar.zst`

---

## b) D.I.Y method:

1. Install debtap using `yay`, `paru` or `pacaur`. In this case, `yay` will be used.
Run `yay -S debtap` on your terminal and wait for the download to finish.

2. Download the `TL_legacy.deb` file from [here.](https://llaun.ch/ubuntu)

3. To make the package, cd into the directory in which you have downloaded the `TL_legacy.deb` file and run `sudo debtap TL_legacy.deb` and wait for the recompilation to finish

4. Install the package: `sudo pacman -U legacylauncher-1.0-1-any.pkg.tar.zst`

---

It ***should*** work. Now, go to the applications menu or launcher and search for "Legacy Launcher", or type `legacylauncher` in the terminal to launch the game. Enjoy!


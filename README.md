```
                              .___      __    _____.__.__
                            __| _/_____/  |__/ ____\__|  |   ____   ______
                           / __ |/  _ \   __\   __\|  |  | _/ __ \ /  ___/
                          / /_/ (  <_> )  |  |  |  |  |  |_\  ___/ \___ \
                          \____ |\____/|__|  |__|  |__|____/\___  >____  >
                               \/                               \/     \/

                    This repository contains personal dotfiles of Samiul Azim.
```

# Dotfiles

## Used Applications

- **Distro:** Arch Linux
- **Window Manager:** [Xmonad](https://github.com/iamsamiulazim/Dotfiles/tree/main/.xmonad), [Spectrwm](https://github.com/iamsamiulazim/Dotfiles/tree/main/.config/spectrwm)
- **Shell:** [Fish](https://github.com/iamsamiulazim/Dotfiles/tree/main/.config/fish), [Zsh](https://github.com/iamsamiulazim/Dotfiles/blob/main/.zshrc), [Bash](https://github.com/iamsamiulazim/Dotfiles/blob/main/.bashrc) [(+Starship Prompt)](https://github.com/iamsamiulazim/Dotfiles/blob/main/.config/starship.toml)
- **Terminal:** [Alacritty](https://github.com/iamsamiulazim/Dotfiles/tree/main/.config/alacritty)
- **Text Editor:** [Nvim](https://github.com/iamsamiulazim/Neovim) 👉 [(See how to set up)](https://github.com/iamsamiulazim/neovim#-installation)
- **Menus:** Dmenu
- **File Manager:** Ranger, [Vifm](https://github.com/iamsamiulazim/Dotfiles/tree/main/.config/vifm)
- **Video Player:** VLC
- **System Monitoring Dashboard:** Htop
- **compositor:** Picom
- **screensaver:** Nitrogen

<br/>

## Clone these dotfiles into a new computer

I manage my dotfiles with a bare git repository and would encourage you to do the same. [How to?](https://www.atlassian.com/git/tutorials/dotfiles)
clone this gitlab repository

```
git clone --bare https://github.com/iamsamiulazim/dotfiles.git $HOME/.dotfiles
```

define the alias in the current shell scope.

```
alias dotfiles='/usr/bin/git --git-dir=$HOME/.dotfiles/ --work-tree=$HOME'
```

run this command if the alias is placed correctly in your shell.

```
dotfiles config --local status.showUntrackedFiles no
```

checkout the actual content from the git repository to your $HOME

```
dotfiles checkout
```

Awesome! You’re done.

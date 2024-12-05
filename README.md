# BRAIN MEMORY FOR INSTALLING THINGS

While this dotfiles repository is a handy way for me to keep track of what I've done with my files to-date,
it doesn't tell me anything about what I need to install to make sure they're set up correctly.
That's what this file is here to do.

# Prerequisites
First off, thanks to [Dreams of Autonomy - Stow manage dotfiles](https://www.youtube.com/watch?v=y6XCebnB9gs) for starting me on this awesome journey


## zsh
- zsh - install from [here](https://github.com/ohmyzsh/ohmyzsh/wiki/Installing-ZSH#how-to-install-zsh-on-many-platforms)
- fzf - 'fuzzy find' install from [here](https://github.com/junegunn/fzf?tab=readme-ov-file#installation)
- git - should be installed by default, if not it can be installed from [here](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
- A NerdFont - I use JetBrainsMono, there's a full list for download [here](https://www.nerdfonts.com/font-downloads)
- ripgrep - install from [here](https://github.com/BurntSushi/ripgrep?tab=readme-ov-file#installation)
- oh-my-posh - terminal themes install from [here](https://ohmyposh.dev/docs/installation/macos)

## neovim 
- NeoVim - install from [here](https://github.com/neovim/neovim/blob/master/INSTALL.md)
- LazyVim - add-on to nvim install from [here](https://www.lazyvim.org/installation)

## stow-based dotfiles management
- stow
    - MacOS
    ```bash
    brew install stow
    ```
    - RHEL/Fedora
    ```bash
    sudo dnf install -y stow
    ```
    - Ubuntu
    ```bash
    sudo apt install -y stow
    ```


## tmux
- tmux - install from [here](https://github.com/tmux/tmux/wiki/Installing)
- tmux package manager (tpm)
    ```bash
    git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm)
    ```

## reference links


# dotfiles
The goal of this repo is to have a central location to store all configs and make initial system set ups quick and easy

# Fedora Systems
## Prerequisites
### Install ghostty
sudo dnf copr enable scottames/ghostty
sudo dnf install ghostty

### stow-based dotfiles management
- stow
    - MacOS
    ```bash
    brew install stow
    ```
    - RHEL/Fedora
    ```bash
    sudo dnf install -y stow
    ```

# Dotfiles for Development

Welcome to my personal dotfiles repository! This collection contains configuration files for various development tools and applications I use regularly.

## Prerequisites

- **GNU Stow**: You need to have GNU Stow installed to set up these dotfiles.

  **Install Stow:**

  - **Ubuntu/Debian:**
    ```bash
    sudo apt-get install stow
    ```
  - **Fedora:**
    ```bash
    sudo dnf install stow
    ```
  - **Arch Linux:**
    ```bash
    sudo pacman -S stow
    ```
  - **macOS (Homebrew):**
    ```bash
    brew install stow
    ```

## Backup Original Dotfiles

Before applying these dotfiles, it's highly recommended to back up your existing configuration files to prevent any loss of personal settings.

**Create a backup directory:**
```bash
mkdir -p ~/dotfiles_backup
cp ~/.bashrc ~/dotfiles_backup/
mv ~/.zshrc ~/dotfiles_backup/.zshrc.bak
cp -r ~/.config/ ~/dotfiles_backup/

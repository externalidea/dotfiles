# My Dotfiles (Arch + Hyprland)

Personal dotfiles backup. Deployed via **GNU Stow**.

#### Stow mirrors the exact structure of your home directory (`~`). 
---

## Deployment

### 1. Install Dependencies
```bash
sudo pacman -Syu git stow
```
### 2.Clone Repository 
```bash 
git clone https://github.com/externalidea/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
```
### 3.Symlink Everything
```
stow -t ~ hypr kitty and so on....
```
### To update links
```
stow -R -t ~ package_name
```

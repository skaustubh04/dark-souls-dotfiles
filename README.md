# Arch Linux Dotfiles
My Arch Linux Hyprland dotfiles. <br>
This isn't 100% my creation, it contains configs from many other people that I've modified to my liking.

## Rice preview

![Rice_Preview](images/rice_preview/hypr_land.png)

## Basic Requirements

Ensure the following are installed on local system (in shell, `$`):

### Yay

```
git clone https://aur.archlinux.org/yay-bin.git "$HOME"/.srcs/yay && cd "$HOME"/.srcs/yay/ && makepkg -si
```

### Git

```
yay -S git
```

### Stow

```
yay -S stow
```

## Installation

Install it on local machine using the following command:

```
git clone https://github.com/skaustubh04/dotfiles.git
```

then use GNU stow to create symlinks (soft links):

```
stow .
```

## PS
Don't forget to edit image paths in `.zshrc`.<br>
The following YouTube video was used as reference: https://youtu.be/y6XCebnB9gs?si=vpPFBIVO-yilL6Lw

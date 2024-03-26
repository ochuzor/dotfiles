dotfiles
========

A collection of my personal dotfiles. 

Here's a little preview of what it looks like with the lovely [catppuccin theme](https://github.com/catppuccin/catppuccin) enabled.


![tmux screenshot](screenshot.png)


Installation
------------
Your first step is to clone this repository:

    git clone https://github.com/hamvocke/dotfiles.git ~/.dotfiles

### Manual Installation
Create symbolic links for the configurations you want to use, e.g.:

    ln -s ~/.dotfiles/vim/.vimrc ~/.vimrc


### Using [GNU Stow](https://www.gnu.org/software/stow/) _(recommended)_
Install GNU Stow _(if not already installed)_

    Mac:      brew install stow
    Ubuntu:   apt-get install stow
    Fedora:   yum install stow
    Arch:     pacman -S stow

Then simply use stow to install the dotfiles you want to use:

    cd ~/.dotfiles
    stow vim
    stow tmux

Ref: https://github.com/hamvocke/dotfiles/tree/master

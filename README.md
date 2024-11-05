# My dotfiles

This directory contains the dotfiles for my system

## Requirements

Ensure you have the following installed on your system

### Git
Arch:
```
pacman -S git
```
Debian/Ubuntu:
```
apt install git
```

### Stow
Arch:
```
pacman -S stow
```
Debian/Ubuntu: 
```
apt install stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git
```
$ git clone git@github.com/dreamsofautonomy/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
Video: https://www.youtube.com/watch?v=y6XCebnB9gs

# snackster-zsh-theme
<img src="https://s3.amazonaws.com/ohmyzsh/oh-my-zsh-logo.png" alt="Oh My Zsh">

## Overview

A beautiful theme for [Oh My Zsh](https://github.com/ohmyzsh/ohmyzsh) framework, that will make your terminal look and feel amazing!

<p align="center">
  <img width="650" alt="terminal" src="https://user-images.githubusercontent.com/9936714/73313755-fe8a8180-4223-11ea-918b-b9ed64be7bab.png">
</p>


## Prerequisites

This zsh theme requires Powerline patched font in order for this theme to render properly. Instuctions on how to install are found in the [Powerline documentation](https://github.com/Lokaltog/powerline-fonts).

## Installation

* Clone this repository to the Oh My Zsh custom themes folder:
```sh
$ cd ~
$ git clone https://github.com/snackk/snackkster-zsh-theme
$ mv snackkster-zsh-theme/snackkster.zsh-theme .oh-my-zsh/custom/themes/
$ rm -rf snackkster-zsh-theme
```

* Change theme on the zshrc file:
```sh
$ cd ~
$ nano .zshrc
$ ZSH_THEME="snackkster"
```

## Update Oh My Zsh
 
If the installation went as supposed the built in upgrade for Oh My Zsh should work with the following: 
```sh
$ upgrade_oh_my_zsh
```

## Problems

Problems usually happens if we tempered with the original structure. 
```sh
$ cd ~/oh_my_zsh
$ git reset --hard
```

## Acknowledgements

This ZSH theme is based on this project [Agnoster](https://github.com/agnoster/agnoster-zsh-theme).

  Written by [@snackk](https://github.com/snackk)

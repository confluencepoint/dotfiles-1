# Dotfiles

My OS X configuration files and scripts.

## Installation

The installation requires [Git](http://git-scm.com) which comes standard with
[Xcode](https://developer.apple.com/xcode/) or the
[Command Line Developer Tools](https://developer.apple.com/downloads/index.action?=command%20line%20tools).

Starting with OS X Mavericks, the Command Line Developer Tools can be easily
installed using `xcode-select --install`.

Installing these dotfiles will overwrite already existing files in your home
directory. The `bootstrap` script will prompt you before installing the
dotfiles. Run the following commands to install:

```bash
git clone https://github.com/joeploijens/dotfiles.git ~/.dotfiles
cd ~/.dotfiles
source bootstrap
```

To update, `cd` into your local `dotfiles` repository and run the `bootstrap`
script again:

```bash
cd ~/.dotfiles
source bootstrap
```

## Features

### Homebrew Formulae

When setting up a new Mac, you may want to install some
[Homebrew](http://brew.sh/) formulae (after installing Homebrew first,
of course) by running the `brew.sh` script.

```bash
cd ~/.dotfiles/scripts
./brew.sh
```

### OS X Defaults

On a new Mac you may want to set some sane OS X defaults by running the
`osx-defaults` script.

```bash
cd ~/.dotfiles/scripts
./osx-defaults
```

### Vim Plug-Ins

- [vim-colors-solarized](https://github.com/altercation/vim-colors-solarized)


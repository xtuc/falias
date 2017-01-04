# falias

> When it's time to fuzzy-search into your bash aliases and functions

![demo](.github/demo.png)

## Installation

### Download the script

```sh
wget https://github.com/xtuc/falias/releases/download/v0.1.0/falias.zsh
```

### Move it into your home

```sh
mv falias.zsh ~/.falias.zsh
```

### Import the function in your shell

```sh
echo "source ~/.falias.zsh" >> ~/.zshrc
```

## Usage

The first time you will need to update ZSH: `source ~/.zshrc`

```sh
falias
```

The command will be run directly after selection.

## Requirements

* FZF
* ZSH

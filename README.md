My dotfiles:
===========
 - kubectl aliases
 - kubectl context in prompt

## Installation
clone this repository in your home directory
```
git clone git@github.com:ptemmer/dotfiles.git 
```

Add to ~/.bashrc or ~/.zsh:
```
for DOTFILE in $(find ~/.dotfiles -name .\*); do
   [ -f $DOTFILE ] && source $DOTFILE
done
```

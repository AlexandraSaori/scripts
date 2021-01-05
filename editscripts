#! /bin/zsh
# This script search and edit scripts
script=$(du -a ~/.config/scripts/* | awk '{print $2}' | fzf) && nvim $script

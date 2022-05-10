# git-config

git config --system
# machine level

git config --global
# user level

git config --local
# project level

## set default editor

git config --global core.editor code

## add wait param:
[core]
	editor = code --wait

## git shortcuts

git config --global --edit

## alias

[alias]
    s = !git status -s

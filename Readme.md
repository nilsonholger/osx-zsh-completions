OSX ZSH COMPLETIONS
===================
Provides zsh completions for selected OSX commands. This repository's main
purpose is to create quality auto completions, e.g. conditional flag aware
presentation and selection of choices, as well as up to date and feature
complete auto completions.

INSTALLATION
============
Clone:
	git clone git://github.com/nilsonholger/... .zsh/osx-zsh-completions
Modify `.zshrc`:
	fpath=(~/.zsh/osx-zsh-completions/ $fpath)
	autoload -Uz compinit
	compinit -d ~/.zcompdump

CONTRIBUTE
==========
Feel free to raise an issue. If you have already created a completion for a
particular command and would like to see it included, fork the repo and submit
a pull request, same goes for any bugs you might encounter.

**This is a work in progress...**

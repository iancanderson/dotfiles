iancanderson dotfiles
===============

I use [thoughtbot/dotfiles](https://github.com/thoughtbot/dotfiles) and
iancanderson/dotfiles together using the `*.local` convention described in
thoughtbot/dotfiles.

Install
-------

Clone onto your laptop:

    git clone git://github.com/iancanderson/dotfiles.git

Install:

    rcup -d dotfiles -x README.md

This will create symlinks for config files in your home directory.

You can safely run `rcup` multiple times to update.

What's in it?
-------------

Git configutation:

[git](http://git-scm.com/) configuration:

- My name and email
- git psed alias for finding/replacing across files in a repo

[zsh](http://zsh.sourceforge.net/FAQ/zshfaq01.html) configuration and aliases:

- autojump config
- GOPATH setup

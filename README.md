# TDD React

## Git config

- `git config --global --edit`

Pelo code

- `git config --global core.editor code`

## GIT

```
# This is Git's per-user configuration file.
[user]
	name = Erislandio
	email = erislandiosoares21@gmail.com
[credential]
	helper = store
[core]
	editor = code --wait

[alias]
	c = !git add --all && git commit -m
	s = !git status -s
	l = !git log --pretty=format:'%C(blue)%h%C(red)%d %C(white)%s - %C(cyan)%cn, %C(green)%cr'
	amend = !git add --all && git commit --amend --no-edit
	count = !git shortlog -s --grep

```

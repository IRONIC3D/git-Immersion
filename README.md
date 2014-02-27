git-Immersion
=============

Git Immersion training files

## A set of aliases being used
<code>
.gitignore
--------------
[alias]
	co = checkout
	ci = commit
	st = status
	br = branch
	hist = log --pretty=format:'%h %ad | %s%d [$an]' --graph --date=short
	type = cat-file -t
	dump = cat-file -p


.bash_profile
-------------------
alias gs='git status '
alias ga='git add '
alias gb='git branch '
alias gc='git commit'
alias gd='git diff'
alias go='git checkout '
alias gk='gitk --all&'

alias got='git '
alias get='git '
</code>
# Git

1. Ways of Rewriting History

1. Rebase
rebase on top of master

1. Interactive Rebase
(git rebase -i HEAD~4) Reword other commit messages

1. Squash
squash (s for short), which melds the commit into the previous one (the one in the line before)

1. Fixup
fixup (f for short), which acts like “squash”, but discards this commit’s message

1. Amend
(git commit --amend) reword the last commit message

1. What is the difference between git pull and git fetch?
git pull = git fetch + git merge 


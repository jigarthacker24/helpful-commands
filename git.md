# Settings for 'git branch' output

## List branch column wise
git config --global column.ui auto

## Sort branch as per commit date
git config --global branch.sort -committerdate

## After rebase, to do git push forcefully
git push --force-with-lease

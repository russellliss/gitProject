# quick notes

- git revert: removes just that commit, unless it comes across a merge conflict, will see how to resolve that later

- git reset
  - by default it is mixed mode, so the same as git reset --mixed, this will undo commits, and unstage any files affected
  - --soft: git reset --soft does the same as mixed, but leaves the files staged
  - --hard: git reset --hard, will remove commits till that point, no going back.  Changes deleted permanently
  
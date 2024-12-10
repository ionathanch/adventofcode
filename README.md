# Advent of Code

This is a monorepo for all my advent of code solutions;
each branch is named after its year.
To add an existing year (20xx):

```sh
$ git switch main            # root
$ git branch -c 20xx         # create branch from root named 20xx
$ git switch 20xx            # switch to 20xx branch
$ git remote add 20xx <url>  # add remote repo as 20xx
$ git fetch --all            # 20xx/main points to main branch of 20xx
$ git rebase 20xx 20xx/main  # rebase remote branch on top of root
$ git branch 20xx -f         # move branch pointer 20xx to rebased commit
$ git log                    # take a browse just to check
```

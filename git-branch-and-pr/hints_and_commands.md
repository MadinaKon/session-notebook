# Most used git commands

1. git switch -c <branchname> create a new branch and switch to it
2. git status to check the current branch and status of the changes
3. git add .
4. git commit -m "descriptive message"
5. git push -u origin <branchname>

## Another useful commands

git branch -d [branch-name] Deletes the specified branch
git log browse and inspect the evolution of project files

<img src="https://media.giphy.com/media/YPhs6YoPXEJgFxERoG/giphy.gif?v=4&h=300&w=300&fit=cover&mask=circle&maxage=7d" />

### Errors, which might occur while working with git

git pull

There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

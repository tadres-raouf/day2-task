# Git Commands Used in Task

## 4-Tell me how to remove them locally and remotely:
    git branch -d dev
    git branch -d test
    git push origin --delete dev
    git push origin --delete test

## 5-Tell me how to checkout another branch without commit changes:
    git checkout dev
    git status
    git stash
    git checkout master
    git checkout dev
    git stash pop
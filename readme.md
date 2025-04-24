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

## 8- Tell me how to list tags:
    git tag
    result:v1.7

## 9-Tell me how to delete tag locally and remotely.
	Locally:
		git tag -d v1.7
	remotely:
		git push origin --delete tag v1.7
		git push origin  :tag v1.7

## 10- Add an image in the README.md file.
![photo](sad.png)

## INITIAL CONFIGS

git config --global user.name "User"
git config --global user.email "user@email.com.br"

git config --list

git config --global --list

## START

git init

git status

git add .

git add -A

git add --all

git commit -m "message"

## STATES

1 - Working Directory

2 - Staging area (staged)

3 - Commited

## DIFERENCES

git diff

git diff --cached

git diff --staged

## HISTORY

git log

git log --oneline

## CHANGES

git checkout "namefile"

git reset 

git reset --hard (delete all files)

## CHANGES UNTRACKED

git clean -f 

## CLONES

git clone http://git..

git clone source/ another-folder/

## GITHUB

git pull

git push

## BRANCH

git branch

git branch develop (create)

git checkout develop

git checkout -b TASK-1 (create)

git push --set-upstream origin develop

git push -u origin develop (shortcut up)

git branch -d develop (delete local)

git push --delete origin develop (remote) 

git branch -m develop1 (rename)

git branch -m develop develop1 (rename not checked)

## 

git mergetool 

## STASH (MEMORY)

git stash

git stash list

git stash save "stash test"

git stash apply (get first stack)

git stash pop

git stash drop stash@[position]

## REVERT COMMIT (local)

git reset --hard HEAD~1 (come back 1 commit)

## CHANGES IN COMMIT

git commit --amend

## FETCH (similar git pull but dont merge)

git pull (git fetch + git merge)

git fetch (after)

git merge


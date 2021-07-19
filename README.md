## INITIAL CONFIGS

git config --global user.name "User"
git config --global user.email "user@email.com.br"

git config --list

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

git init

git clone <url of the repo> <folder where to clone the repo> : to clone locally

git status : current state

git add : add file(s)

git commit : takes a snapshot of your source code and allows you to keep a tracking of all the changes

git log : history of commits

git branch : list of branches

git checkout -b features/1234-new-killing-feature : create a new branch and switch to it

git branch features/1234-new-killing-feature : switch to a branch

git branch -d features/1234-new-killing-feature : delete a branch

git remote add origin <url> : set remote url for a local repo

git remote set-url origin <url> : update remote url for a local repo

git Fetch : get all repository update

git Pull : get update in code (fetch + merge)

git push --set-upstream origin <branch> : add remote information for a local branch

git push : push update to the repository

gh pr create --base main --head <branch> --title '<title>' --body '<description>' : create a pr to merge <branch> into main
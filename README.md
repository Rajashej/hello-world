Rollback
revert unstaged file
  572  git checkout bashfile1.sh
 
Revert staged files
git restore -- staged filename
git checkout filename

Revert commit id
git revert HEAD
git revert commitid

Revert and remove history
git reset --hard commitid


git pull
make changes
git add .
git commit -m ""
git push origin branchname

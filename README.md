# git-tutorial

git reset --hard
+
git clean -fd


git fetch (for updating the status, not changing any file)
(oposite of push)

pull = fetch + merge

git log newbranch

git tag -a tagname -m "my tag message"

git rm removes the file in the next commit but it keeps the local

sourcetree graphical tool

git fast-forward

git log origin/branchname (to log a remote branch)
git branch -vv (branches + corresponding upstreams)

## not recommended, to turn back a branch into an old commit (we will lose the commits in the middle) ###
git reset --hard commitishId
git push -f
## end of not recommended ###


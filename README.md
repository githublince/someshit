# someshit
echo "# someshit" > README.md
git add .
git commit -m 'SOME TEXT'
git branch -m main (renaming branch name )
git remote add origin https://github.com/githublince/someshit.git
git push -u origin main (to push to the github)


…or push an existing repository from the command line
git remote add origin https://github.com/githublince/someshit.git
git branch -M main
git push -u origin main


>>> to see all branches including remote branch
    git branch -a

>>> to see all  local branches 
    git branch 

>>> to see all remote branches 
    git branch -r

>>> to push branch to github
    git push origin NEW_branch

>>> To pull github all branch
    1) git fetch origin (to fetch all branches remotly present)
    2) git branch -a (to see all available branches)
    3) git branch --track <branchname> <origin/branchname>

>>> to push branch to github
    git push origin NEW_branch
    
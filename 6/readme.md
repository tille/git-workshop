branches
========

git-branch - List, create, or delete branches
- usualmente se usan como features

git checkout -b login
git push -u
touch login.html
git add login.html
git commit -m 'Add login page.'
git push origin login


delete local and remote branches
git branch --delete branch_name
git push origin :branch_name
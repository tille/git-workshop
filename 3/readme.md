using github
============

git-remote - Manage set of tracked repositories
git remote
create repo using github UI
git remote add origin <repo_url>
git remote

git-push - Update remote refs along with associated objects
git push origin master

create another repo
git remote add origin2 <another_repo>
git push origin2 master

**undoing pushed commits**
git commit --amend -m 'new description'
git push
- Error
git push -f
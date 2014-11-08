#multiple users

**another user**
touch multiple_users
git push

**me**
git pull
touch another_change && git add another_change && git commit -m 'Multiple users.' && git push


Git stash
touch stash.txt
echo 'Timon' >> stash.txt
git stash
git stash list

**another user**
touch stash.txt
git add .
git commit -m 'Stashing.'
git push
----------------

git stash apply
solve conflicts
echo 'pumba' >> stash.txt
git add .
git commit -m 'Timon and pumba.'
git push


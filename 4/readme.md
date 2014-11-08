#Multiple users

**another user**
```bash
touch multiple_users
git add multiple_users
git commit -m 'Multiple users.'
git push
```

**me**
```bash
git pull
echo 'Another user' >> multiple_users
git add multiple_users
git commit -m 'Another user.'
git push
```

----
**git-stash - Stash the changes in a dirty working directory away**

```bash
touch stash.txt
echo 'Timon' >> stash.txt
git add stash.txt
git stash
git stash list
```

```bash
touch stash.txt
echo '&&' >> stash.txt
git stash apply
- error
git add stash.txt
git stash apply
solve conflicts
```

```bash
git stash list
git stash clear
echo 'pumba' >> stash.txt
git add stash.txt
git commit -m 'Timon and pumba.'
git push
```


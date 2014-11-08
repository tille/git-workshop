# Using Branches

<blockquote>
git-branch - List, create, or delete branches
</blockquote>

```git
git checkout -b login
git push -u
touch login.html
git add login.html
git commit -m 'Add login page.'
git push origin login
```

**pure way**
```git
git branch --track branch_name origin/branch_name
```

**lazy-coders**
```git
gem install grb
grb new branch_name
```

----
**delete local and remote branches**
```git
git branch --delete branch_name
git push origin :branch_name
```

----
Using fetch
-----------

**another user**
```git
grb new logout
touch logout.html
git add logout.html
git commit -m 'Add logout page'
git push
git co master
```

```git
git fetch
git co logout
```

You can add aliases for every git command to .bashrc

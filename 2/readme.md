reverting changes
=================

<blockquote>
Use "git checkout -- <file>..." to discard changes in working directory<br>
Use checkout only when the file is commited otherwise use reset
</blockquote>


```bash
touch new_file
git add new_file
git commit -m 'Add new file'
echo 'tales' >> new_file
git checkout -- new_file
```

---- 
**delete files from versioning**

```bash
git rm new_file
```
----

**undoing things with amend**
```bash
git add new_file
git commit --amend
- vim :x to exit and save
git commit --amend -m 'new message'
```

emacs .gitignore

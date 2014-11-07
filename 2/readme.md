reverting changes
=================

git checkout -- <file_name>
use "git checkout -- <file>..." to discard changes in working directory, only when the file is commited already otherwise use reset


touch new_file
git add new_file
git commit -m 'Add new file'
--
echo 'tales' >> new_file
git checkout -- new_file


**delete files from versioning**
git rm new_file


**undoing things with amend**
git add new_file
git commit --amend
- vim :x to exit and save
git commit --amend -m 'new message'

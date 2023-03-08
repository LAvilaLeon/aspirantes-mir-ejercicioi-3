# aspirantes-mir-ejercicioi-3

Clink v1.4.21 is available.
- To apply the update, run 'clink update'.
- To stop checking for updates, run 'clink set clink.autoupdate false'.
- To view the release notes, visit the Releases page:
  https://github.com/chrisant996/clink/releases

C:\Users\ACER\Downloads\cmder (1) (master)
λ cd ../..

C:\Users\ACER (master)
λ cd ../..

C:\
λ cd MAKE\

C:\MAKE
λ cd S3

C:\MAKE\S3 (develop)
λ ls -al
total 8
drwxr-xr-x 1 ACER 197121 0 mar.  7 18:33 ./
drwxr-xr-x 1 ACER 197121 0 mar.  7 17:47 ../
drwxr-xr-x 1 ACER 197121 0 mar.  7 18:38 .git/
-rw-r--r-- 1 ACER 197121 0 mar.  7 18:33 index.html

C:\MAKE\S3 (develop)
λ touch index-html

C:\MAKE\S3 (develop)
λ touch index.html

C:\MAKE\S3 (develop)
λ git add .

C:\MAKE\S3 (develop)
λ git commit -m "Primer commit"
[develop 7f84285] Primer commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index-html

C:\MAKE\S3 (develop)
λ git branch
* develop
  master

C:\MAKE\S3 (develop)
λ touch .env

C:\MAKE\S3 (develop)
λ git status
On branch develop
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index-html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env
        .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

C:\MAKE\S3 (develop)
λ git add index.html

C:\MAKE\S3 (develop)
λ git commit -m "Cambios en la rama develop"
On branch develop
Changes not staged for commit:
  (use "git add/rm <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        deleted:    index-html

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        .env
        .gitignore

no changes added to commit (use "git add" and/or "git commit -a")

C:\MAKE\S3 (develop)
λ git log --oneline
7f84285 (HEAD -> develop) Primer commit
126c1e0 (master) primer commit

C:\MAKE\S3 (develop)
λ git checkout MAKE
error: pathspec 'MAKE' did not match any file(s) known to git

C:\MAKE\S3 (develop)
λ Git checkout MAKE Switched to branch 'MAKE'
error: pathspec 'MAKE' did not match any file(s) known to git
error: pathspec 'Switched' did not match any file(s) known to git
error: pathspec 'to' did not match any file(s) known to git
error: pathspec 'branch' did not match any file(s) known to git
error: pathspec ''MAKE'' did not match any file(s) known to git

C:\MAKE\S3 (develop)
λ Git checkout
D       index-html

C:\MAKE\S3 (develop)
λ cat index.html

C:\MAKE\S3 (develop)
λ git merge develop
Already up to date.

C:\MAKE\S3 (develop)
λ cat index.html

C:\MAKE\S3 (develop)
λ git ls-files --other --ignored --exclude-standard .env

C:\MAKE\S3 (develop)
λ

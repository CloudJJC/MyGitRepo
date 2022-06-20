Valentine@DESKTOP-NNBVI4H MINGW64 ~
$ mkdir Shopping

Valentine@DESKTOP-NNBVI4H MINGW64 ~
$ cd Shopping

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping
$ ls

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping
$ ls -a
./  ../

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping
$ git status
fatal: not a git repository (or any of the parent directories): .git

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping
$ git init
Initialized empty Git repository in C:/Users/Valentine/Shopping/.git/

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ pwd
/c/Users/Valentine/Shopping

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ touch yard.txt groceries.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ ls
groceries.txt  yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ ls -a
./  ../  .git/  groceries.txt  yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git add groceries.txt yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ ls
groceries.txt  yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ start .

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   groceries.txt
        new file:   yard.txt


Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git commit -m 'create yard and groceries lists'
[master (root-commit) 49d015d] create yard and groceries lists
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 groceries.txt
 create mode 100644 yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git log
commit 49d015dffb80a431cb0a3a785216085ba152b286 (HEAD -> master)
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:13:29 2022 -0400

    create yard and groceries lists

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git add groceries.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   groceries.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   yard.txt


Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git commit -m "add ingredients for tomato soup"
[master 4c4900e] add ingredients for tomato soup
 1 file changed, 3 insertions(+)

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git add yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   yard.txt


Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git commit -m "add items needed for garden box"
[master 374c340] add items needed for garden box
 1 file changed, 2 insertions(+)

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   groceries.txt
        modified:   yard.txt

no changes added to commit (use "git add" and/or "git commit -a")

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git add groceries.txt yard.txt

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   groceries.txt
        modified:   yard.txt


Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git commit -m 'add items needed to grow potatoes'
[master 9cd0466] add items needed to grow potatoes
 2 files changed, 3 insertions(+), 2 deletions(-)

Valentine@DESKTOP-NNBVI4H MINGW64 ~/Shopping (master)
$ git log
commit 9cd0466f5fe2aef11222590658cc308eb0e2a466 (HEAD -> master)
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:21:30 2022 -0400

    add items needed to grow potatoes

commit 374c340c1eb0244c161a4d77e2edeb12f8987593
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:18:34 2022 -0400

    add items needed for garden box

commit 4c4900e1c4018ebd0ef3b174af2bc9ded8e16e35
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:17:46 2022 -0400

    add ingredients for tomato soup

commit 49d015dffb80a431cb0a3a785216085ba152b286
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:13:29 2022 -0400

    create yard and groceries lists
:...skipping...
commit 9cd0466f5fe2aef11222590658cc308eb0e2a466 (HEAD -> master)
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:21:30 2022 -0400

    add items needed to grow potatoes

commit 374c340c1eb0244c161a4d77e2edeb12f8987593
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:18:34 2022 -0400

    add items needed for garden box

commit 4c4900e1c4018ebd0ef3b174af2bc9ded8e16e35
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:17:46 2022 -0400

    add ingredients for tomato soup

commit 49d015dffb80a431cb0a3a785216085ba152b286
Author: CloudJJC <valentine.okonkwo@mail.mcgill.ca>
Date:   Mon Jun 20 10:13:29 2022 -0400

    create yard and groceries lists


User@DESKTOP-575V4K5 MINGW64 ~
$ cd Gym-Git-Exercise-Solutions/

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions
$ git init
Initialized empty Git repository in C:/Users/User/Gym-Git-Exercise-Solutions/.git/

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (master)
$ git branch -m master main

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m"my first commit "
[main (root-commit) 60116cd] my first commit
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 README.md
 create mode 100644 exer2

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git remote add origin https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 229 bytes | 229.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git branch dev

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout dev
Switched to branch 'dev'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git branch test

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git branch -d test
Deleted branch test (was 60116cd).

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git branch -d test^C
                                                                  




								  User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ pwd
/c/Users/User/Gym-Git-Exercise-Solutions

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ touch home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ ls
README.md  exer2  home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit-m "added a file with a content"
git: 'commit-m' is not a git command. See 'git --help'.

The most similar command is
        commit-tree

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git push origin dev
Everything up-to-date

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ ls
README.md  exer2  home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ rm -r home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m" deleting my file "
On branch dev
nothing to commit, working tree clean

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git push origin dev
Everything up-to-date

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ ls
README.md  exer2

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash
No local changes to save

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m"my 3 commit"
[dev a1272c4] my 3 commit
 2 files changed, 1 insertion(+)
 create mode 100644 home
 create mode 100644 home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash
warning: in the working copy of 'home.html', LF will be replaced by CRLF the next time Git touches it
Saved working directory and index state WIP on dev: a1272c4 my 3 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi about

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash push -m"my second stash"
No local changes to save

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ rm  about

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash push -m"my 3 commit "
Saved working directory and index state On dev: my 3 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash list
stash@{0}: On dev: my 3 commit
stash@{1}: WIP on dev: a1272c4 my 3 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ vi home.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash push -m"my 4 commit"
Saved working directory and index state On dev: my 4 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ stash list
bash: stash: command not found

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash list
stash@{0}: On dev: my 4 commit
stash@{1}: On dev: my 3 commit
stash@{2}: WIP on dev: a1272c4 my 3 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop 1
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
Dropped refs/stash@{1} (0364dcc4bc132e5ad6a418c96efa9e0a61462bed)

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop  1
error: Your local changes to the following files would be overwritten by merge:
        home.html
Please commit your changes or stash them before you merge.
Aborting
On branch dev
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git commit -m "my 5 commit "
[dev 3649b05] my 5 commit
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git push origin dev
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (6/6), 529 bytes | 529.00 KiB/s, done.
Total 6 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
   ac9729e..3649b05  dev -> dev

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git stash pop 0
Auto-merging home.html
CONFLICT (content): Merge conflict in home.html
On branch dev
Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add <file>..." to mark resolution)
        both modified:   home.html

no changes added to commit (use "git add" and/or "git commit -a")
The stash entry is kept in case you need it again.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git log
commit 3649b05f767397cd93dbdaf86b1cbfb77524e53c (HEAD -> dev, origin/dev)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon May 15 20:05:17 2023 +0300

    my 5 commit

commit a1272c40cfe63568c18ce8a187ce21ce2f7e0c4e
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon May 15 19:51:41 2023 +0300

    my 3 commit

commit ac9729ebe45f53f073596a05c885d42559990bf6
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon May 15 13:34:41 2023 +0300

    my second commit

commit 60116cdc0c93a32d9112d14a915df06e31c7f781 (origin/main, main)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon May 15 13:24:23 2023 +0300

    my first commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ ^C

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git reset --hard 3649b05f767397cd93dbdaf86b1cbfb77524e53c
HEAD is now at 3649b05 my 5 commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$


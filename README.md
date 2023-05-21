User@DESKTOP-575V4K5 MINGW64 ~
$ cd Gym-Git-Exercise-Solutions

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git branch ft/bundle-2

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (dev)
$ git switch ft/bundle-2
Switched to branch 'ft/bundle-2'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ vi service.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add .
warning: in the working copy of 'service.html', LF will be replaced by CRLF the next time Git touches it

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git commit -m"this the first commit of the 1st exercise in the second bundle"
[ft/bundle-2 78090be] this the first commit of the 1st exercise in the second bundle
 1 file changed, 12 insertions(+)
 create mode 100644 service.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 498 bytes | 166.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/bundle-2 -> ft/bundle-2








User@DESKTOP-575V4K5 MINGW64 ~ (main)
$ cd Gym-Git-Exercise-Solutions

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ vi team.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m " the first commit in 3rd bundle exer 1"
On branch ft/team-page
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        team.html

nothing added to commit but untracked files present (use "git add" to track)

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git add .
warning: in the working copy of 'team.html', LF will be replaced by CRLF the next time Git touches it

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git commit -m " the first commit in 3rd bundle exer 1"
[ft/team-page 1579f75]  the first commit in 3rd bundle exer 1
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git push origin ft/team-page
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 476 bytes | 476.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
   6c6977b..1579f75  ft/team-page -> ft/team-page

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git branch ft/contact-page

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/team-page
Switched to branch 'ft/team-page'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git log
commit 1579f75e87880d5e93c0fc23562fc77d796ad3bb (HEAD -> ft/team-page, origin/ft/team-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Sun May 21 20:29:24 2023 +0300

     the first commit in 3rd bundle exer 1

commit 6c6977b9dac81e547cf055f7ebd2151564ef79bf (origin/main, main, ft/contact-page)
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Fri May 19 14:47:11 2023 +0300

    the commit of second exercise in the second bundle

commit 05b18f596e6adbdb25f324f8a4de869c5a986c63
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Fri May 19 10:26:18 2023 +0300

    deleting the branches I did not create well

commit 60116cdc0c93a32d9112d14a915df06e31c7f781
Author: kevin-gram <k.nyiringan@alustudent.com>
Date:   Mon May 15 13:24:23 2023 +0300

    my first commit

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout ft/team-page
Already on 'ft/team-page'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry ^C

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry-pick 1579f75e87880d5e93c0fc23562fc77d796ad3bb
[ft/contact-page 62556b4]  the first commit in 3rd bundle exer 1
 Date: Sun May 21 20:29:24 2023 +0300
 1 file changed, 12 insertions(+)
 create mode 100644 team.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m "this my 4 commit in exer 1 bundle 3"
On branch ft/contact-page
nothing to commit, working tree clean

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push origin  ft/team-page
Everything up-to-date

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push origin  main
Everything up-to-date

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git branch ft/contact-page
fatal: a branch named 'ft/contact-page' already exists

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m "this my 4 commit in exer 1 bundle 3"
On branch ft/contact-page
nothing to commit, working tree clean

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git branch ft/faq-page

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ vi faq.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .
warning: in the working copy of 'faq.html', LF will be replaced by CRLF the next time Git touches it

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m "the 5th commit  in exer 1 bundle 3"
[ft/contact-page 5d047ac] the 5th commit  in exer 1 bundle 3
 1 file changed, 17 insertions(+)
 create mode 100644 faq.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git push origin ft/contact-page
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (6/6), done.
Writing objects: 100% (6/6), 915 bytes | 915.00 KiB/s, done.
Total 6 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), done.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git revert ^C

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git revert  05b18f596e6adbdb25f324f8a4de869c5a986c63

CONFLICT (modify/delete): service.html deleted in parent of 05b18f5 (deleting the branches I did not create well) and modified in HEAD.  Version HEAD of service.html left in tree.
error: could not revert 05b18f5... deleting the branches I did not create well
hint: After resolving the conflicts, mark them with
hint: "git add/rm <pathspec>", then run
hint: "git revert --continue".
hint: You can instead skip this commit with "git revert --skip".
hint: To abort and get back to the state before "git revert",
hint: run "git revert --abort".

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git revert  1579f75e87880d5e93c0fc23562fc77d796ad3bb
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git status
On branch ft/contact-page
You are currently reverting commit 05b18f5.
  (fix conflicts and run "git revert --continue")
  (use "git revert --skip" to skip this patch)
  (use "git revert --abort" to cancel the revert operation)

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md

Unmerged paths:
  (use "git restore --staged <file>..." to unstage)
  (use "git add/rm <file>..." as appropriate to mark resolution)
        deleted by them: service.html


User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git revert 05b18f596e6adbdb25f324f8a4de869c5a986c63
error: Reverting is not possible because you have unmerged files.
hint: Fix them up in the work tree, and then use 'git add/rm <file>'
hint: as appropriate to mark resolution and make a commit.
fatal: revert failed

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git revert 05b18f596e6adbdb25f324f8a4de869c5a986c63
error: your local changes would be overwritten by revert.
hint: commit your changes or stash them to proceed.
fatal: revert failed

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page|REVERTING)
$ git revert --skip

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git commit -m" the last commit in exer 1 bundle 3"
On branch ft/contact-page
nothing to commit, working tree clean

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$


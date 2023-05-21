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













User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git switch ft/faq-page
Switched to branch 'ft/faq-page'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git branch ft/home-page-redesign

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/faq-page)
$ git switch main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ ls
README.md  exer2  service.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ vi service.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "the changes on the main branch in exer 2 bundle 3"
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   service.html

no changes added to commit (use "git add" and/or "git commit -a")

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git add service.html

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git commit -m "the changes on the main branch in exer 2 bundle 3"
[main 7d9bea4] the changes on the main branch in exer 2 bundle 3
 1 file changed, 1 insertion(+), 1 deletion(-)

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 313 bytes | 313.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
   6c6977b..7d9bea4  main -> main

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (main)
$ git switch ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git rebase main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add .

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add ^C

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add ft/home-page-redesign
fatal: pathspec 'ft/home-page-redesign' did not match any files

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git commit -m "the changes on the 2nd exer in bundle 3"
On branch ft/home-page-redesign
nothing to commit, working tree clean

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 476 bytes | 476.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/Kevin-gram/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push origin ft/home-page-redesign
Everything up-to-date

User@DESKTOP-575V4K5 MINGW64 ~/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$


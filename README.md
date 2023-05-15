
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


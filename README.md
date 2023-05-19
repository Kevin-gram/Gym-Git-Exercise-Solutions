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


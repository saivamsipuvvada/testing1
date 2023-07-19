# testing1 file
it took some time for the remote origin command
all mistake i made was to not changed the name  like it is "main" but i typed "master".


the below are the mistakes i made.


$ git remote set-url origin https://github.com/saivamsipuvvada/testing3.git

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$ git remote add new-remote-name https://github.com/saivamsipuvvada/testing1.git
error: remote new-remote-name already exists.

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$ git remote set-url origin https://github.com/saivamsipuvvada/testing1.git

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$ git remote add new testing3.git

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$ git remote add origin https://github.com/saivamsipuvvada/testing1.git
error: remote origin already exists.

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$ git push --set-upstream origin main
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 8 threads
Compressing objects: 100% (23/23), done.
Writing objects: 100% (24/24), 7.80 MiB | 2.61 MiB/s, done.
Total 24 (delta 10), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (10/10), done.
To https://github.com/saivamsipuvvada/testing1.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.

hp@DESKTOP-TLGFG1R MINGW64 ~/Desktop/myproject (main)
$

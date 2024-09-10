$ ssh-keygen -t ed25519 -C "ttuyet1504@gmail.com"

$ eval "$(ssh-agent -s)"

$ ssh-add git
local repo -> remote repo


devadmin@SEA-VM-DEVWIN06 MINGW64 ~/gitnew (master)
$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 2 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 315 bytes | 315.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/PandaDeveloper154/gitlesson.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

devadmin@SEA-VM-DEVWIN06 MINGW64 ~/gitnew (master)
$ git status
On branch master
Your branch is up to date with 'origin/master'.

nothing to commit, working tree clean

devadmin@SEA-VM-DEVWIN06 MINGW64 ~/gitnew (master)
$

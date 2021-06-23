# Shopping

Here you can find various shopping items



Here are the commands I used:

casje@DESKTOP-3PO00QU MINGW64 ~
$ cd /c/Users/casje/Documents/gitbash/shopping

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git add .

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git commit --m "Here is an update"
[main ad99fa2] Here is an update
 1 file changed, 3 insertions(+), 1 deletion(-)

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 332 bytes | 332.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Sebjennings/Shopping
   22b2fcb..ad99fa2  main -> main

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git add .

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git commit --m "Here is an update2"
[main 4ad95ca] Here is an update2
 1 file changed, 4 insertions(+)
 create mode 100644 Clothes/Groceries.txt

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (4/4), 397 bytes | 397.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Sebjennings/Shopping
   ad99fa2..4ad95ca  main -> main

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git add .

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git commit --m "Here is an update2"
[main 16a42d0] Here is an update2
 7 files changed, 19 insertions(+)
 create mode 100644 Clothes/Hats#.txt
 create mode 100644 Clothes/Outfits.txt
 create mode 100644 Food/Bakery.txt
 create mode 100644 Food/Dairy.txt
 rename {Clothes => Food}/Groceries.txt (100%)
 create mode 100644 Presents/Nish.txt
 create mode 100644 Presents/Zoe.txt

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git push
Enumerating objects: 13, done.
Counting objects: 100% (13/13), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (11/11), 852 bytes | 852.00 KiB/s, done.
Total 11 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Sebjennings/Shopping
   4ad95ca..16a42d0  main -> main

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git pull
From https://github.com/Sebjennings/Shopping
 * [new branch]      Seb        -> origin/Seb
Already up to date.

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git checkout seb
Switched to a new branch 'seb'
Branch 'seb' set up to track remote branch 'seb' from 'origin'.

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git add .

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git commit --m "Here is an update3"
[seb a481394] Here is an update3
 1 file changed, 2 insertions(+), 2 deletions(-)

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 347 bytes | 347.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'seb' on GitHub by visiting:
remote:      https://github.com/Sebjennings/Shopping/pull/new/seb
remote:
To https://github.com/Sebjennings/Shopping
 * [new branch]      seb -> seb

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git granch -d seb
git: 'granch' is not a git command. See 'git --help'.

The most similar command is
        branch

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git gbranch -d seb
git: 'gbranch' is not a git command. See 'git --help'.

The most similar command is
        branch

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git branch -d seb
error: Cannot delete branch 'seb' checked out at 'C:/Users/casje/Documents/GitBash/Shopping'

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git branch
  main
* seb

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (seb)
$ git checkout main
Switched to branch 'main'
Your branch is up to date with 'origin/main'.

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git branch -d seb
warning: deleting branch 'seb' that has been merged to
         'refs/remotes/origin/seb', but not yet merged to HEAD.
Deleted branch seb (was a481394).

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git branch
* main

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$ git branch -d seb^C

casje@DESKTOP-3PO00QU MINGW64 ~/Documents/gitbash/shopping (main)
$
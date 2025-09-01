Administrator@DESKTOP-AV2PARO MINGW64 ~
$ cd Desktop

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop
$ mkdir Sanrojo_IT120_Activity1

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop
$ cd Sanrojo_IT120_Activity1

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1
$ git init
Initialized empty Git repository in C:/Users/Administrator/Desktop/Sanrojo_IT120_Activity1/.git/

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.tx Test.py

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git add .

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git commit -m "Initial commit"
[master (root-commit) 97d2cf0] Initial commit
 5 files changed, 15 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.tx
 create mode 100644 Test.py

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git remote add origin https://github.com/louie20041217/Sanrojo_IT120_Act1.git

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git remote -v
origin  https://github.com/louie20041217/Sanrojo_IT120_Act1.git (fetch)
origin  https://github.com/louie20041217/Sanrojo_IT120_Act1.git (push)

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git branch -M master

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
fatal: A task was canceled.


Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git push -u origin master
info: please complete authentication in your browser...
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (7/7), 656 bytes | 131.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/louie20041217/Sanrojo_IT120_Act1.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout master
Already on 'master'
Your branch is up to date with 'origin/master'.

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout -b Sanrojo_B1
Switched to a new branch 'Sanrojo_B1'

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B1)
$ git branch
* Sanrojo_B1
  master

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B1)
$ git add Profile.txt

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B1)
$ git commit -m "Ammend Data"
[Sanrojo_B1 e6ede31] Ammend Data
 1 file changed, 7 insertions(+)

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B1)
$ git push origin Sanrojo_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 453 bytes | 226.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Sanrojo_B1' on GitHub by visiting:
remote:      https://github.com/louie20041217/Sanrojo_IT120_Act1/pull/new/Sanrojo_B1
remote:
To https://github.com/louie20041217/Sanrojo_IT120_Act1.git
 * [new branch]      Sanrojo_B1 -> Sanrojo_B1

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B1)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout -b Sanrojo_B2
Switched to a new branch 'Sanrojo_B2'

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B2)
$ git add Education.txt

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B2)
$ git commit -m "Ammend Data"
[Sanrojo_B2 e500cc4] Ammend Data
 1 file changed, 5 insertions(+), 1 deletion(-)

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B2)
$ git push origin Sanrojo_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Sanrojo_B2' on GitHub by visiting:
remote:      https://github.com/louie20041217/Sanrojo_IT120_Act1/pull/new/Sanrojo_B2
remote:
To https://github.com/louie20041217/Sanrojo_IT120_Act1.git
 * [new branch]      Sanrojo_B2 -> Sanrojo_B2

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B2)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout Sanrojo_B3
error: pathspec 'Sanrojo_B3' did not match any file(s) known to git

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout -b Sanrojo_B3
Switched to a new branch 'Sanrojo_B3'

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B3)
$ git add Background.txt

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B3)
$ git rm Test.py
rm 'Test.py'

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B3)
$ git commit -m "Ammend Data and removed Test.py"
[Sanrojo_B3 415c619] Ammend Data and removed Test.py
 2 files changed, 4 insertions(+), 4 deletions(-)
 delete mode 100644 Test.py

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B3)
$ git push origin Sanrojo_B3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 362 bytes | 181.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Sanrojo_B3' on GitHub by visiting:
remote:      https://github.com/louie20041217/Sanrojo_IT120_Act1/pull/new/Sanrojo_B3
remote:
To https://github.com/louie20041217/Sanrojo_IT120_Act1.git
 * [new branch]      Sanrojo_B3 -> Sanrojo_B3

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (Sanrojo_B3)
$ git checkout master
Switched to branch 'master'
Your branch is up to date with 'origin/master'.

Administrator@DESKTOP-AV2PARO MINGW64 ~/Desktop/Sanrojo_IT120_Activity1 (master)
$ git checkout -b Sanrojo_B4
Switched to a new branch 'Sanrojo_B4'

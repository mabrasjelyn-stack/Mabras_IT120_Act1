sky@DESKTOP-1N94H8R MINGW64 ~
$ cd Desktop
bash: cd: Desktop: No such file or directory

sky@DESKTOP-1N94H8R MINGW64 ~
$ mkdir Mabras_IT120_Act1

sky@DESKTOP-1N94H8R MINGW64 ~git
$ cd Mabras_IT120_Act1

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1
$ git init
Initialized empty Git repository in C:/Users/sky/Mabras_IT120_Act1/.git/

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git remote add origin https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ touch Profile.txt Education.txt Background.txt Readme.txt Test.py

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$  git remote add origin https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
error: remote origin already exists.

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git add .
warning: in the working copy of 'Test.py', LF will be replaced by CRLF the next
time Git touches it

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git commit -m "Initial commit with all files"
[master (root-commit) beb3937] Initial commit with all files
 5 files changed, 34 insertions(+)
 create mode 100644 Background.txt
 create mode 100644 Education.txt
 create mode 100644 Profile.txt
 create mode 100644 Readme.txt
 create mode 100644 Test.py

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git remote add origin https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
error: remote origin already exists.

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git push origin master
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 4 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (7/7), 927 bytes | 463.00 KiB/s, done.
Total 7 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
 * [new branch]      master -> master

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git checkout -b Mabras_B1
Switched to a new branch 'Mabras_B1'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B1)
$  git branch
* Mabras_B1
  master

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B1)
$ git add Profile.txt

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B1)
$ git commit -m "Amend: added Birth of Place, Religion, Father's Occupation, Mother's Name, Occupation"
[Mabras_B1 db85ab5] Amend: added Birth of Place, Religion, Father's Occupation,
Mother's Name, Occupation
 1 file changed, 8 insertions(+), 1 deletion(-)

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B1)
$ git push origin Mabras_B1
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 504 bytes | 504.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Mabras_B1' on GitHub by visiting:
remote:      https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1/pull/new/Mab
ras_B1
remote:
To https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
 * [new branch]      Mabras_B1 -> Mabras_B1

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B1)
$ git checkout master
Switched to branch 'master'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git checkout -b Mabras_B2
Switched to a new branch 'Mabras_B2'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B2)
$ git add Education.txt

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B2)
$ git commit -m "Amend: updated Education.txt with details"
[Mabras_B2 c525ab9] Amend: updated Education.txt with details
 1 file changed, 5 insertions(+), 1 deletion(-)

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B2)
$ git push origin Mabras_B2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 462 bytes | 462.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Mabras_B2' on GitHub by visiting:
remote:      https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1/pull/new/Mab
ras_B2
remote:
To https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
 * [new branch]      Mabras_B2 -> Mabras_B2

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B2)
$ git checkout master
Switched to branch 'master'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git checkout -b Mabras_B3
Switched to a new branch 'Mabras_B3'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B3)
$ git add Background.txt

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B3)
$ git rm Test.py
rm 'Test.py'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B3)
$ git commit -m "Amend: updated Background.txt and removed Test.py"
[Mabras_B3 84565ed] Amend: updated Background.txt and removed Test.py
 2 files changed, 4 insertions(+), 4 deletions(-)
 delete mode 100644 Test.py

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B3)
$ git push origin Mabras_B3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 404 bytes | 404.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Mabras_B3' on GitHub by visiting:
remote:      https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1/pull/new/Mab
ras_B3
remote:
To https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
 * [new branch]      Mabras_B3 -> Mabras_B3

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B3)
$ git checkout master
Switched to branch 'master'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (master)
$ git checkout -b Mabras_B4
Switched to a new branch 'Mabras_B4'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B4)
$ git add Readme.txt

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B4)
$ git rm Test.py
rm 'Test.py'

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B4)
$ git commit -m "Amend: updated Readme.txt and removed Test.py"
[Mabras_B4 7ce28a1] Amend: updated Readme.txt and removed Test.py
 2 files changed, 148 insertions(+), 3 deletions(-)
 delete mode 100644 Test.py

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B4)
$ git push origin Mabras_B4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.40 KiB | 1.40 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'Mabras_B4' on GitHub by visiting:
remote:      https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1/pull/new/Mabras_
B4
remote:
To https://github.com/mabrasjelyn-stack/Mabras_IT120_Act1.git
 * [new branch]      Mabras_B4 -> Mabras_B4

sky@DESKTOP-1N94H8R MINGW64 ~/Mabras_IT120_Act1 (Mabras_B4)
$ git branch -a
  Mabras_B1
  Mabras_B2
  Mabras_B3
* Mabras_B4
  master
  remotes/origin/Mabras_B1
  remotes/origin/Mabras_B2
  remotes/origin/Mabras_B3
  remotes/origin/Mabras_B4
  remotes/origin/master

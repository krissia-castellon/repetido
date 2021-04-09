# repetido
tony@tony MINGW64 ~/Desktop
$ mkdir repetidosyp

tony@tony MINGW64 ~/Desktop
$ cd repetidosyp/

tony@tony MINGW64 ~/Desktop/repetidosyp
$ git remote set-url origin https://github.com/krissia-castellon/repetido.git
fatal: not a git repository (or any of the parent directories): .git

tony@tony MINGW64 ~/Desktop/repetidosyp
$ git init
Initialized empty Git repository in C:/Users/pastor/Desktop/repetidosyp/.git/

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git remote set-url origin https://github.com/krissia-castellon/repetido.git
error: No such remote 'origin'

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git remote add origin https://github.com/krissia-castellon/repetido.git

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git add.
git: 'add.' is not a git command. See 'git --help'.

The most similar command is
        add

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   syp.docx


tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ touch repetido.docx

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   repetido.docx
        new file:   syp.docx


tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git commit -m "Solucion parcial"
[master (root-commit) a2bf72b] Solucion parcial
 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 repetido.docx
 create mode 100644 syp.docx

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git push -u origin master
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 8.95 KiB | 1.12 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/krissia-castellon/repetido.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git commit -m "respuesta 1"
[master beb98c4] respuesta 1
 3 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 ~$petido.docx
 create mode 100644 ~WRL3951.tmp

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git push -u origin master
Enumerating objects: 6, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 10.19 KiB | 1.27 MiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/krissia-castellon/repetido.git
   a2bf72b..beb98c4  master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git branch rama2

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git branch
* master
  rama2

tony@tony MINGW64 ~/Desktop/repetidosyp (master)
$ git checkout rama2
Switched to branch 'rama2'

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git commit -m "respuesta 2"
[rama2 b548f0d] respuesta 2
 1 file changed, 0 insertions(+), 0 deletions(-)

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git push -u origin rama2
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.91 KiB | 497.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'rama2' on GitHub by visiting:
remote:      https://github.com/krissia-castellon/repetido/pull/new/rama2
remote:
To https://github.com/krissia-castellon/repetido.git
 * [new branch]      rama2 -> rama2
Branch 'rama2' set up to track remote branch 'rama2' from 'origin'.

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git branch rama 3
fatal: Not a valid object name: '3'.

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git branch rama3

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git branch
  master
* rama2
  rama3

tony@tony MINGW64 ~/Desktop/repetidosyp (rama2)
$ git checkout rama3
Switched to branch 'rama3'

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git commit -m "respuesta 3"
[rama3 d87be0e] respuesta 3
 1 file changed, 0 insertions(+), 0 deletions(-)

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git push -u origin rama3
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 3.21 KiB | 548.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'rama3' on GitHub by visiting:
remote:      https://github.com/krissia-castellon/repetido/pull/new/rama3
remote:
To https://github.com/krissia-castellon/repetido.git
 * [new branch]      rama3 -> rama3
Branch 'rama3' set up to track remote branch 'rama3' from 'origin'.

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git branch rama4

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git branch
  master
  rama2
* rama3
  rama4

tony@tony MINGW64 ~/Desktop/repetidosyp (rama3)
$ git checkout rama4
Switched to branch 'rama4'

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git commit -m "respuesta 4"
[rama4 795388e] respuesta 4
 1 file changed, 0 insertions(+), 0 deletions(-)

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git push -u origin rama4
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 18.36 KiB | 3.06 MiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'rama4' on GitHub by visiting:
remote:      https://github.com/krissia-castellon/repetido/pull/new/rama4
remote:
To https://github.com/krissia-castellon/repetido.git
 * [new branch]      rama4 -> rama4
Branch 'rama4' set up to track remote branch 'rama4' from 'origin'.

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git branch rama5

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git branch
  master
  rama2
  rama3
* rama4
  rama5

tony@tony MINGW64 ~/Desktop/repetidosyp (rama4)
$ git checkout rama5
Switched to branch 'rama5'
M       repetido.docx

tony@tony MINGW64 ~/Desktop/repetidosyp (rama5)
$ git add .

tony@tony MINGW64 ~/Desktop/repetidosyp (rama5)
$ git commit -m "respuesta 5"
[rama5 5e8a7b1] respuesta 5
 1 file changed, 0 insertions(+), 0 deletions(-)

tony@tony MINGW64 ~/Desktop/repetidosyp (rama5)
$ git push -u origin rama5
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 2.96 KiB | 505.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'rama5' on GitHub by visiting:
remote:      https://github.com/krissia-castellon/repetido/pull/new/rama5
remote:
To https://github.com/krissia-castellon/repetido.git
 * [new branch]      rama5 -> rama5
Branch 'rama5' set up to track remote branch 'rama5' from 'origin'.

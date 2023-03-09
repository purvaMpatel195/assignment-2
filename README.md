# assignment-2
assignment 2
Purva@LAPTOP-48VFS045 MINGW64 ~
$ cd desktop

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop
$ mkdir patronus

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop
$ cd patronus

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus
$ touch patronus.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus
$ git add patronus.txt
fatal: not a git repository (or any of the parent directories): .git

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus
$ git init
Initialized empty Git repository in C:/Users/Purva/Desktop/patronus/.git/

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git add patronus.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git commit -m 'add empty patronus file'
Author identity unknown

*** Please tell me who you are.

Run

  git config --global user.email "you@example.com"
  git config --global user.name "Your Name"

to set your account's default identity.
Omit --global to set the identity only in this repository.

fatal: unable to auto-detect email address (got 'Purva@LAPTOP-48VFS045.(none)')

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git config -- user.email "purvamp1905@gmail.com"

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git config -- user.name "purva"

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git commit -m 'add empty patronus file'
[master (root-commit) 86542d8] add empty patronus file
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 patronus.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git branch harry

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git branch snape

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (master)
$ git checkout harry
Switched to branch 'harry'

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (harry)
$ git checkout snape
Switched to branch 'snape'
M       patronus.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (snape)
$ git branch lily

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (snape)
$ git checkout lily
Switched to branch 'lily'
M       patronus.txt

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (lily)
$ git add .

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (lily)
$ git commit -m 'add lilys doe patronus'
[lily 9bd4af0] add lilys doe patronus
 1 file changed, 45 insertions(+)

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (lily)
$ git branch -a
  harry
* lily
  master
  snape

Purva@LAPTOP-48VFS045 MINGW64 ~/desktop/patronus (lily)
$

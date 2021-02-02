```bash

hansu@TABLE MINGW64 ~
$ pwd
/c/Users/hansu

hansu@TABLE MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

hansu@TABLE MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

hansu@TABLE MINGW64 ~
$ pwd
/c/Users/hansu

hansu@TABLE MINGW64 ~
$ cd downloads

hansu@TABLE MINGW64 ~/downloads
$ cd desktop
bash: cd: desktop: No such file or directory

hansu@TABLE MINGW64 ~/downloads
$ cd..
bash: cd..: command not found

hansu@TABLE MINGW64 ~/downloads
$ pwd
/c/Users/hansu/downloads

hansu@TABLE MINGW64 ~/downloads
$ ls
Git-2.30.0.2-64-bit.exe*                   VC_redist.x64.exe*  desktop.ini                       typora-setup-x64.exe*
OBS-Studio-26.1.1-Full-Installer-x64.exe*  ZoomInstaller.exe*  theme-6574856553230835089.xml
Radmin_Viewer_3.5.2.1_EN.msi               cpu-z_1.95-en.zip   tp_compact_keyboard_1.5.6.0.exe*

hansu@TABLE MINGW64 ~/downloads
$ cd..
bash: cd..: command not found

hansu@TABLE MINGW64 ~/downloads
$ cd ..

hansu@TABLE MINGW64 ~
$ md a
bash: md: command not found

hansu@TABLE MINGW64 ~
$ mkdir hello

hansu@TABLE MINGW64 ~
$ ls
'3D Objects'/
 AppData/
'Application Data'@
 Contacts/
 Cookies@
 Documents/
 Downloads/
 Favorites/
 IntelGraphicsProfiles/
 Links/
'Local Settings'@
 Music/
'My Documents'@
 NTUSER.DAT
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TM.blf
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000001.regtrans-ms
 NTUSER.DAT{53b39e88-18c4-11ea-a811-000d3aa4692b}.TMContainer00000000000000000002.regtrans-ms
 NetHood@
 OneDrive/
 Pictures/
 PrintHood@
 Recent@
'Saved Games'/
 Searches/
 SendTo@
'Start Menu'@
 Templates@
 Videos/
 hello/
 ntuser.dat.LOG1
 ntuser.dat.LOG2
 ntuser.ini

hansu@TABLE MINGW64 ~
$ rm -r hello/

hansu@TABLE MINGW64 ~
$ mkdir test

hansu@TABLE MINGW64 ~
$ cd test

hansu@TABLE MINGW64 ~/test
$ pwd
/c/Users/hansu/test

hansu@TABLE MINGW64 ~/test
$ git init
Initialized empty Git repository in C:/Users/hansu/test/.git/

hansu@TABLE MINGW64 ~/test (master)
$ ls

hansu@TABLE MINGW64 ~/test (master)
$ ls -a
./  ../  .git/

hansu@TABLE MINGW64 ~/test (master)
$ cd .git

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ ls
HEAD  config  description  hooks/  info/  objects/  refs/

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ git --help
usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
           [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
           [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
           [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
           <command> [<args>]

These are common Git commands used in various situations:

start a working area (see also: git help tutorial)
   clone             Clone a repository into a new directory
   init              Create an empty Git repository or reinitialize an existing one

work on the current change (see also: git help everyday)
   add               Add file contents to the index
   mv                Move or rename a file, a directory, or a symlink
   restore           Restore working tree files
   rm                Remove files from the working tree and from the index
   sparse-checkout   Initialize and modify the sparse-checkout

examine the history and state (see also: git help revisions)
   bisect            Use binary search to find the commit that introduced a bug
   diff              Show changes between commits, commit and working tree, etc
   grep              Print lines matching a pattern
   log               Show commit logs
   show              Show various types of objects
   status            Show the working tree status

grow, mark and tweak your common history
   branch            List, create, or delete branches
   commit            Record changes to the repository
   merge             Join two or more development histories together
   rebase            Reapply commits on top of another base tip
   reset             Reset current HEAD to the specified state
   switch            Switch branches
   tag               Create, list, delete or verify a tag object signed with GPG

collaborate (see also: git help workflows)
   fetch             Download objects and refs from another repository
   pull              Fetch from and integrate with another repository or a local branch
   push              Update remote refs along with associated objects

'git help -a' and 'git help -g' list available subcommands and some
concept guides. See 'git help <command>' or 'git help <concept>'
to read about a specific subcommand or concept.
See 'git help git' for an overview of the system.

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ cd..
bash: cd..: command not found

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ cd ..

hansu@TABLE MINGW64 ~/test (master)
$ rm -r .git

hansu@TABLE MINGW64 ~/test
$ git status
fatal: not a git repository (or any of the parent directories): .git

hansu@TABLE MINGW64 ~/test
$ git init
Initialized empty Git repository in C:/Users/hansu/test/.git/

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ ls -a
./  ../  .git/

hansu@TABLE MINGW64 ~/test (master)
$ cd .git

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ touch a.txt

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ ls
HEAD  a.txt  config  description  hooks/  info/  objects/  refs/

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ git status
fatal: this operation must be run in a work tree

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ cd ..

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ touch a.txt

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        a.txt

nothing added to commit but untracked files present (use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ git add a.txt

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   a.txt


hansu@TABLE MINGW64 ~/test (master)
$ git config --global user.email "hansung.shin@gmail.com"

hansu@TABLE MINGW64 ~/test (master)
$ git config --global user.email
hansung.shin@gmail.com

hansu@TABLE MINGW64 ~/test (master)
$ git config --global user.name "Hansung Shin"

hansu@TABLE MINGW64 ~/test (master)
$ git config --global user.name
Hansung Shin

hansu@TABLE MINGW64 ~/test (master)
$ git commit
Aborting commit due to empty commit message.

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "First commit"
[master (root-commit) 67dc209] First commit
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 a.txt

hansu@TABLE MINGW64 ~/test (master)
$ git log
commit 67dc209907628087e6b5a46ab7dd6bf559bf2f36 (HEAD -> master)
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 01:43:08 2021 -0500

    First commit

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
nothing to commit, working tree clean

hansu@TABLE MINGW64 ~/test (master)
$ cd .git

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ rm a.txt

hansu@TABLE MINGW64 ~/test/.git (GIT_DIR!)
$ cd ..

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
nothing to commit, working tree clean

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git diff
diff --git a/a.txt b/a.txt
index e69de29..32f95c0 100644
--- a/a.txt
+++ b/a.txt
@@ -0,0 +1 @@
+hi
\ No newline at end of file

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add a.txt

hansu@TABLE MINGW64 ~/test (master)
$ gist status
bash: gist: command not found

hansu@TABLE MINGW64 ~/test (master)
$ gist status
bash: gist: command not found

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   a.txt


hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Add greeting"
[master 5aabeb2] Add greeting
 1 file changed, 1 insertion(+)

hansu@TABLE MINGW64 ~/test (master)
$ git log
commit 5aabeb290f8530d6d5b4f72c89f2663248675abc (HEAD -> master)
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:22:47 2021 -0500

    Add greeting

commit 67dc209907628087e6b5a46ab7dd6bf559bf2f36
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 01:43:08 2021 -0500

    First commit

hansu@TABLE MINGW64 ~/test (master)
$ ^C

hansu@TABLE MINGW64 ~/test (master)
$ git checkout 67dc209
Note: switching to '67dc209'.

You are in 'detached HEAD' state. You can look around, make experimental
changes and commit them, and you can discard any commits you make in this
state without impacting any branches by switching back to a branch.

If you want to create a new branch to retain commits you create, you may
do so (now or later) by using -c with the switch command. Example:

  git switch -c <new-branch-name>

Or undo this operation with:

  git switch -

Turn off this advice by setting config variable advice.detachedHead to false

HEAD is now at 67dc209 First commit

hansu@TABLE MINGW64 ~/test ((67dc209...))
$ git checkout master
Previous HEAD position was 67dc209 First commit
Switched to branch 'master'

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add
Nothing specified, nothing added.
hint: Maybe you wanted to say 'git add .'?
hint: Turn this message off by running
hint: "git config advice.addEmptyPathspec false"

hansu@TABLE MINGW64 ~/test (master)
$ git add a.txt

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Name added"
[master 0136e3d] Name added
 1 file changed, 2 insertions(+), 1 deletion(-)

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
nothing to commit, working tree clean

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add "a.txt"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Major added"
[master 645070a] Major added
 1 file changed, 2 insertions(+), 1 deletion(-)

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add "a.txt"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Hobby added"
[master 197748a] Hobby added
 1 file changed, 2 insertions(+), 1 deletion(-)

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add "a.txt"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Address added"
[master 32c08e0] Address added
 1 file changed, 2 insertions(+), 1 deletion(-)

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   a.txt

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add "a.txt"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Age added"
[master 4c5c142] Age added
 1 file changed, 2 insertions(+), 1 deletion(-)

hansu@TABLE MINGW64 ~/test (master)
$ git log
commit 4c5c142a333c05e9d439f496abf32fd78fb277c7 (HEAD -> master)
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:36:10 2021 -0500

    Age added

commit 32c08e018900f0ed3e2508cd0c685a60208fcd50
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:34:50 2021 -0500

    Address added

commit 197748a2ce5943c5917e57da05359cd62ad8f8d8
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:33:55 2021 -0500

    Hobby added

commit 645070a44354cc709f362c5dc855dfd2fcbca869
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:32:50 2021 -0500

    Major added

commit 0136e3d799323ecc5c4dc20c6849fd3543c036b7
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:31:42 2021 -0500

    Name added

commit 5aabeb290f8530d6d5b4f72c89f2663248675abc
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 02:22:47 2021 -0500

    Add greeting

commit 67dc209907628087e6b5a46ab7dd6bf559bf2f36
Author: Hansung Shin <hansung.shin@gmail.com>
Date:   Mon Feb 1 01:43:08 2021 -0500

    First commit

hansu@TABLE MINGW64 ~/test (master)
$ git log --oneline
4c5c142 (HEAD -> master) Age added
32c08e0 Address added
197748a Hobby added
645070a Major added
0136e3d Name added
5aabeb2 Add greeting
67dc209 First commit

hansu@TABLE MINGW64 ~/test (master)
$ ^C

hansu@TABLE MINGW64 ~/test (master)
$ git remote

hansu@TABLE MINGW64 ~/test (master)
$ git remote add https://github.com/lmnopo/test.git
usage: git remote add [<options>] <name> <url>

    -f, --fetch           fetch the remote branches
    --tags                import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --track <branch>  branch(es) to track
    -m, --master <branch>
                          master branch
    --mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from


hansu@TABLE MINGW64 ~/test (master)
$ git remote add origin https://github.com/lmnopo/test.git

hansu@TABLE MINGW64 ~/test (master)
$ git remote
origin

hansu@TABLE MINGW64 ~/test (master)
$ git remote -v
origin  https://github.com/lmnopo/test.git (fetch)
origin  https://github.com/lmnopo/test.git (push)

hansu@TABLE MINGW64 ~/test (master)
$ git push origin master
Enumerating objects: 21, done.
Counting objects: 100% (21/21), done.
Delta compression using up to 6 threads
Compressing objects: 100% (7/7), done.
Writing objects: 100% (21/21), 1.57 KiB | 267.00 KiB/s, done.
Total 21 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/lmnopo/test.git
 * [new branch]      master -> master

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        Github TIL.md

nothing added to commit but untracked files present (use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ git add "Github TIL.md"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "First commit"
[master 61ea784] First commit
 1 file changed, 146 insertions(+)
 create mode 100644 Github TIL.md

hansu@TABLE MINGW64 ~/test (master)
$ git remote add origin https://github.com/lmnopo/TIL.git
error: remote origin already exists.

hansu@TABLE MINGW64 ~/test (master)
$ git remote set-url origin https://github.com/lmnopo/TIL.git

hansu@TABLE MINGW64 ~/test (master)
$ git push origin master
Enumerating objects: 24, done.
Counting objects: 100% (24/24), done.
Delta compression using up to 6 threads
Compressing objects: 100% (10/10), done.
Writing objects: 100% (24/24), 3.17 KiB | 180.00 KiB/s, done.
Total 24 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/lmnopo/TIL.git
 * [new branch]      master -> master

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        "00_\354\213\240\355\225\234\354\204\261.md"
        "01_\354\213\240\355\225\234\354\204\261.md"

nothing added to commit but untracked files present (use "git add" to track)

hansu@TABLE MINGW64 ~/test (master)
$ git add -a
error: unknown switch `a'
usage: git add [<options>] [--] <pathspec>...

    -n, --dry-run         dry run
    -v, --verbose         be verbose

    -i, --interactive     interactive picking
    -p, --patch           select hunks interactively
    -e, --edit            edit current diff and apply
    -f, --force           allow adding otherwise ignored files
    -u, --update          update tracked files
    --renormalize         renormalize EOL of tracked files (implies -u)
    -N, --intent-to-add   record only the fact that the path will be added later
    -A, --all             add changes from all tracked and untracked files
    --ignore-removal      ignore paths removed in the working tree (same as --no-all)
    --refresh             don't add, only refresh the index
    --ignore-errors       just skip files which cannot be added because of errors
    --ignore-missing      check if - even missing - files are ignored in dry run
    --chmod (+|-)x        override the executable bit of the listed files
    --pathspec-from-file <file>
                          read pathspec from file
    --pathspec-file-nul   with --pathspec-from-file, pathspec elements are separated with NUL character


hansu@TABLE MINGW64 ~/test (master)
$ git add -all
error: did you mean `--all` (with two dashes)?

hansu@TABLE MINGW64 ~/test (master)
$ git add --all

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   "00_\354\213\240\355\225\234\354\204\261.md"
        new file:   "01_\354\213\240\355\225\234\354\204\261.md"


hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "First commit"
[master d269842] First commit
 2 files changed, 252 insertions(+)
 create mode 100644 "00_\354\213\240\355\225\234\354\204\261.md"
 create mode 100644 "01_\354\213\240\355\225\234\354\204\261.md"

hansu@TABLE MINGW64 ~/test (master)
$ git remote add origin master
error: remote origin already exists.

hansu@TABLE MINGW64 ~/test (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 7.81 KiB | 571.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/lmnopo/TIL.git
   61ea784..d269842  master -> master

hansu@TABLE MINGW64 ~/test (master)
$ git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   Github TIL.md

no changes added to commit (use "git add" and/or "git commit -a")

hansu@TABLE MINGW64 ~/test (master)
$ git add "Github TIL.md"

hansu@TABLE MINGW64 ~/test (master)
$ git commit -m "Update how to change repository"
[master d600951] Update how to change repository
 1 file changed, 6 insertions(+)

hansu@TABLE MINGW64 ~/test (master)
$ git push origin master
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 361 bytes | 361.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/lmnopo/TIL.git
   d269842..d600951  master -> master

hansu@TABLE MINGW64 ~/test (master)
$

```


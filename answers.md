answer 1:  git version 2.28.0 

answer 2: credential.helper=osxkeychain
user.name=Tracey
user.email=tc400617@ohio.edu

answer 3: GIT-ADD(1)                        Git Manual                        GIT-ADD(1)

NAME
       git-add - Add file contents to the index

SYNOPSIS
       git add [--verbose | -v] [--dry-run | -n] [--force | -f] [--interactive | -i] [--patch | -p]
                 [--edit | -e] [--[no-]all | --[no-]ignore-removal | [--update | -u]]
                 [--intent-to-add | -N] [--refresh] [--ignore-errors] [--ignore-missing] [--renormalize]
                 [--chmod=(+|-)x] [--pathspec-from-file=<file> [--pathspec-file-nul]]
                 [--] [<pathspec>...]

DESCRIPTION
       This command updates the index using the current content found in the
       working tree, to prepare the content staged for the next commit. It
       typically adds the current content of existing paths as a whole, but
       with some options it can also be used to add content with only part of
       the changes made to the working tree files applied, or remove paths
       that do not exist in the working tree anymore.

answer 4: On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    README.md
    answerd.md

nothing added to commit but untracked files present (use "git add" to track)

answer 5: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
    answerd.md

answer 6: On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
    new file:   README.md
    new file:   answerd.md

answer 7: [master (root-commit) decb490] Intital commit
 2 files changed, 52 insertions(+)
 create mode 100644 README.md
 create mode 100644 answerd.md
traceycopeland@Traceys-MacBook-Air git-lab % git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
    modified:   answerd.md

no changes added to commit (use "git add" and/or "git commit -a")

answer 8: commit decb4906c2c9dcf11c9b3e36a15af756091d699b (HEAD -> master)
Author: Tracey <tc400617@ohio.edu>


    Intital commit

answer 9: Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (4/4), 1003 bytes | 501.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/tcope1610/git-lab.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.

answer 10: Tracey Copeland

tcope1610

tc400617@ohio.com

answer 11:  ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/tcope1610/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

answer 12: Tracey Copeland

tcope1610

<<<<<<< HEAD
tc400617@ohio.com
=======
cs2400 109
>>>>>>> 6b34198018f4a04b4eeb4af9a3a7b9cf66f4d95e

answer 13: .        .DS_Store    git-lab
..        .git        git-lab-2




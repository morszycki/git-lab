Answer 1: 
git version 2.24.3 (Apple Git-128)

Answer 2: 
credential.helper=osxkeychain
user.name=Mark Orszycki
user.email=mo509316@ohio.edu
filter.lfs.clean=git-lfs clean -- %f
filter.lfs.smudge=git-lfs smudge -- %f
filter.lfs.process=git-lfs filter-process
filter.lfs.required=true

Answer 3: 
git --help displays common Git commands used in various situations such as start a working area, work on the current change, examine the history and state, grow mark and tweak your common history, and collaborate.

Answer 4:
On branch master
No commits yet
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        README.md
        answers.md
nothing added to commit but untracked files present (use "git add" to track)

Answer 5: 
On branch master
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
Untracked files:
  (use "git add <file>..." to include in what will be committed)
        answers.md

Answer 6:
On branch master
No commits yet
Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   README.md
        new file:   answers.md

Answer 7: 
On branch master
Changes not staged for commit:
        modified:   answers.md
no changes added to commit

Answer 8:
commit 24be2ef7adac7f2528bb633382cf0bf53225f1ff (HEAD -> master)
Author: Mark Orszycki <mo509316@ohio.edu>
Date:   Wed Sep 2 16:35:18 2020 -0400
    Initial commit

Answer 9:
On branch master
Your branch is up to date with 'origin/master'.
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   answers.md
no changes added to commit (use "git add" and/or "git commit -a")

Answer 10:
The changes were not reflected in my local copy.

Answer 11: 
The push attempt is rejected as I need to fetch the origin and update the ReadME.md file (as it wasn't updated localy) before being able to commit.

Output: To https://github.com/morszycki/git-lab.git
 ! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/morszycki/git-lab.git'

Answer 12:
Yes, the changes were reflected in my local copy.

Answer 13:
.               ..              .git            .gitignore      README.md


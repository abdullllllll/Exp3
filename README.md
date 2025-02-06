C:\Users\student.RCOESRV\Documents\SEPM Exp 3>cd "EXP 3"

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git init
Initialized empty Git repository in C:/Users/student.RCOESRV/Documents/SEPM Exp 3/EXP 3/.git/

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add .

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "First Commit"
[master (root-commit) 85338a5] First Commit
 Committer: Student <student@rcoesrv.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.html
 create mode 100644 style.css

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git remote add origin https://github.com/abdullllllll/Exp3.git

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git remote -v
origin  https://github.com/abdullllllll/Exp3.git (fetch)
origin  https://github.com/abdullllllll/Exp3.git (push)

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git branch
* master

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git status
On branch master
nothing to commit, working tree clean

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git branch
* master

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin master
info: please complete authentication in your browser...
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 225 bytes | 28.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abdullllllll/Exp3.git
 * [new branch]      master -> master

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout -b anas
Switched to a new branch 'anas'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3>git checkout -b faiz
Switched to a new branch 'faiz'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout anas
Switched to branch 'anas'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3>git branch -d faiz
Deleted branch faiz (was 85338a5).

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin anas
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'anas' on GitHub by visiting:
remote:      https://github.com/abdullllllll/Exp3/pull/new/anas
remote:
To https://github.com/abdullllllll/Exp3.git
 * [new branch]      anas -> anas

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit
On branch anas
nothing to commit, working tree clean

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add . 

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3>git commit -m "Commit in second branch"
On branch anas
nothing to commit, working tree clean

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout master
Switched to branch 'master'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git branch -m main

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add .

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "Serial Commiter"
On branch main
nothing to commit, working tree clean

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git branch
  anas
* main

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin main
Total 0 (delta 0), reused 0 (delta 0), pack-reused 0
remote: 
remote: Create a pull request for 'main' on GitHub by visiting:
remote:      https://github.com/abdullllllll/Exp3/pull/new/main
remote:
To https://github.com/abdullllllll/Exp3.git
 * [new branch]      main -> main

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "Final Commit(I Guess)" 
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.html
        modified:   style.css

no changes added to commit (use "git add" and/or "git commit -a")

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in style.css.
The file will have its original line endings in your working directory

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "Final Commit (I Hope So)"
[main b8f0499] Final Commit (I Hope So)
 Committer: Student <student@rcoesrv.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 32 insertions(+)

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin main
Enumerating objects: 7, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 596 bytes | 119.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abdullllllll/Exp3.git
   85338a5..b8f0499  main -> main

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git branch
  anas
* main

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout anas
error: Your local changes to the following files would be overwritten by checkout:
        index.html
Please commit your changes or stash them before you switch branches.
Aborting

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3>git commit -m "BLAH BLAH BLAH"
[main 2248c38] BLAH BLAH BLAH
 Committer: Student <student@rcoesrv.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 1 file changed, 1 insertion(+)

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin anas
Everything up-to-date

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "NICE"
On branch main
nothing to commit, working tree clean

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout anas
Switched to branch 'anas'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git add .
warning: LF will be replaced by CRLF in index.html.
The file will have its original line endings in your working directory
warning: LF will be replaced by CRLF in style.css.
The file will have its original line endings in your working directory

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git commit -m "HEHEHE"
[anas 6ca1c95] HEHEHE
 Committer: Student <student@rcoesrv.com>
Your name and email address were configured automatically based
on your username and hostname. Please check that they are accurate.
You can suppress this message by setting them explicitly. Run the
following command and follow the instructions in your editor to edit
your configuration file:

    git config --global --edit

After doing this, you may fix the identity used for this commit with:

    git commit --amend --reset-author

 2 files changed, 33 insertions(+)

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git push origin anas
Enumerating objects: 7, done.
Counting objects: 100% (6/6), done.
Delta compression using up to 4 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 598 bytes | 85.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/abdullllllll/Exp3.git
   85338a5..6ca1c95  anas -> anas

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git checkout main
Switched to branch 'main'

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git pull origin main
remote: Enumerating objects: 10, done.
remote: Counting objects: 100% (10/10), done.
remote: Compressing objects: 100% (4/4), done.
remote: Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (4/4), 1.84 KiB | 60.00 KiB/s, done.
From https://github.com/abdullllllll/Exp3
 * branch            main       -> FETCH_HEAD
   b8f0499..4e32fed  main       -> origin/main
Merge made by the 'recursive' strategy.
 style.css | 2 +-
 1 file changed, 1 insertion(+), 1 deletion(-)

C:\Users\student.RCOESRV\Documents\SEPM Exp 3\EXP 3> git --version
git version 2.33.1.windows.1

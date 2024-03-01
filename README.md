
Aloks-MacBook-Air:proj aloksingh$ git init
Reinitialized existing Git repository in /Users/aloksingh/Documents/gittest/proj1/proj/.git/
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

nothing to commit, working tree clean
Aloks-MacBook-Air:proj aloksingh$ touch text.sh
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	text.sh

nothing added to commit but untracked files present (use "git add" to track)
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git add .
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   text.sh

Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git commit -m "commit1" 
[main 9b4f610] commit1
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 text.sh
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git rmote add origin https://github.com/Alok93singh/proj.git
git: 'rmote' is not a git command. See 'git --help'.

The most similar command is
	remote
Aloks-MacBook-Air:proj aloksingh$ git remote add origin https://github.com/Alok93singh/proj.git
error: remote origin already exists.
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git push origin master
error: src refspec master does not match any
error: failed to push some refs to 'https://github.com/Alok93singh/proj.git'
Aloks-MacBook-Air:proj aloksingh$ git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 269 bytes | 134.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Alok93singh/proj.git
   1ec05da..9b4f610  main -> main
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 

## Add repo with different name

Aloks-MacBook-Air:proj aloksingh$ git remote add origin12 https://github.com/Alok93singh/proj.git
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   text.sh

no changes added to commit (use "git add" and/or "git commit -a")
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git add .
Aloks-MacBook-Air:proj aloksingh$   git merge -m "second merge"
Already up to date.
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git push origin12 main
Everything up-to-date
Aloks-MacBook-Air:proj aloksingh$ cat text.sh 
bhdcbdhcds
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git ststus
git: 'ststus' is not a git command. See 'git --help'.

The most similar command is
	status
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   text.sh

Aloks-MacBook-Air:proj aloksingh$ git add .
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   text.sh

Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git push origin main
Everything up-to-date
Aloks-MacBook-Air:proj aloksingh$ git add .
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ touch sec.sh
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   text.sh

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	sec.sh

Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git add .
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git commit -m "secondmerge"
[main 332225c] secondmerge
 2 files changed, 1 insertion(+)
 create mode 100644 sec.sh
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ git push origin12 main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 4 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 314 bytes | 104.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/Alok93singh/proj.git
   9b4f610..332225c  main -> main
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 
Aloks-MacBook-Air:proj aloksingh$ 

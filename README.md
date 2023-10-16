git init
<br>
git add README.md
<br>
git commit -m "first commit"
<br>
git branch -M main
<br>
git remote add origin https://github.com/devopspranshul/boston.git
<br>
git push -u origin main
<br>
git remote add origin https://github.com/devopspranshul/boston.git
<br>
git branch -M main
<br>
git push -u origin main
<br>
Last login: Mon Oct 16 18:31:43 on ttys000
Pranshuls-MacBook-Air:~ pranshulsingh$ git --version
git version 2.37.1 (Apple Git-137.1)
Pranshuls-MacBook-Air:~ pranshulsingh$ git config --global user.name "devopspranshul"
Pranshuls-MacBook-Air:~ pranshulsingh$ git config --global user.email "rishi33.iti@gmail.com"
Pranshuls-MacBook-Air:~ pranshulsingh$ cd boston
Pranshuls-MacBook-Air:boston pranshulsingh$ git init
Initialized empty Git repository in /Library/PostgreSQL/boston/.git/
Pranshuls-MacBook-Air:boston pranshulsingh$ ls
Pranshuls-MacBook-Air:boston pranshulsingh$ ls -l
total 0
Pranshuls-MacBook-Air:boston pranshulsingh$ touch index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ ls -l
total 0
-rw-r--r--  1 pranshulsingh  staff  0 Oct 16 19:17 index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ vi index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ ls
index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	index.html

nothing added to commit but untracked files present (use "git add" to track)
Pranshuls-MacBook-Air:boston pranshulsingh$ git add index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ touch README.md
Pranshuls-MacBook-Air:boston pranshulsingh$ vi README.md
Pranshuls-MacBook-Air:boston pranshulsingh$ git add README.md
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ touch bluestyle.css
Pranshuls-MacBook-Air:boston pranshulsingh$ vi bluestyle.css
Pranshuls-MacBook-Air:boston pranshulsingh$ git add bluestyle.css
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   bluestyle.css
	new file:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ vi index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   bluestyle.css
	new file:   index.html

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ git add index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   README.md
	new file:   bluestyle.css
	new file:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ git add -all
error: did you mean `--all` (with two dashes)?
Pranshuls-MacBook-Air:boston pranshulsingh$ git commit -m "First Commit release"
[main (root-commit) 27de3c9] First Commit release
 3 files changed, 39 insertions(+)
 create mode 100644 README.md
 create mode 100644 bluestyle.css
 create mode 100644 index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status --short
Pranshuls-MacBook-Air:boston pranshulsingh$ -a
-sh: -a: command not found
Pranshuls-MacBook-Air:boston pranshulsingh$ git log
commit 27de3c9167599be4f0a7653d99c140c1d2e716f2 (HEAD -> main)
Author: devopspranshul <rishi33.iti@gmail.com>
Date:   Mon Oct 16 19:40:29 2023 +0530

    First Commit release
Pranshuls-MacBook-Air:boston pranshulsingh$ git branch master
Pranshuls-MacBook-Air:boston pranshulsingh$ git branch
* main
  master
Pranshuls-MacBook-Air:boston pranshulsingh$ git checkout master
Switched to branch 'master'
Pranshuls-MacBook-Air:boston pranshulsingh$ git branch
  main
* master
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch master
nothing to commit, working tree clean
Pranshuls-MacBook-Air:boston pranshulsingh$ git checkout main
Switched to branch 'main'
Pranshuls-MacBook-Air:boston pranshulsingh$ vi index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
	modified:   index.html

no changes added to commit (use "git add" and/or "git commit -a")
Pranshuls-MacBook-Air:boston pranshulsingh$ git add index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ git add --all
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ git commit -m "Second commit release"
[main 3b663bb] Second commit release
 1 file changed, 3 insertions(+)
Pranshuls-MacBook-Air:boston pranshulsingh$ git staus
git: 'staus' is not a git command. See 'git --help'.

The most similar command is
	status
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
nothing to commit, working tree clean
Pranshuls-MacBook-Air:boston pranshulsingh$ ls
README.md	bluestyle.css	index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ vi index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git add index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   index.html

Pranshuls-MacBook-Air:boston pranshulsingh$ git commit -m "Second commit release modified"
[main d1f28d0] Second commit release modified
 1 file changed, 2 deletions(-)
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch main
nothing to commit, working tree clean
Pranshuls-MacBook-Air:boston pranshulsingh$ git checkout master
Switched to branch 'master'
Pranshuls-MacBook-Air:boston pranshulsingh$ git branch
  main
* master
Pranshuls-MacBook-Air:boston pranshulsingh$ touch img_hello_world.jpg
Pranshuls-MacBook-Air:boston pranshulsingh$ vi img_hello_world.jpg
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)
	img_hello_world.jpg

nothing added to commit but untracked files present (use "git add" to track)
Pranshuls-MacBook-Air:boston pranshulsingh$ git add img_hello_world.jpg
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   img_hello_world.jpg

Pranshuls-MacBook-Air:boston pranshulsingh$ git add -all
error: did you mean `--all` (with two dashes)?
Pranshuls-MacBook-Air:boston pranshulsingh$ git status
On branch master
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   img_hello_world.jpg

Pranshuls-MacBook-Air:boston pranshulsingh$ git commit -m "Third commit reease added img"
[master f95d966] Third commit reease added img
 1 file changed, 16 insertions(+)
 create mode 100644 img_hello_world.jpg
Pranshuls-MacBook-Air:boston pranshulsingh$ git status -ls
error: unknown switch `l'
usage: git status [<options>] [--] <pathspec>...

    -v, --verbose         be verbose
    -s, --short           show status concisely
    -b, --branch          show branch information
    --show-stash          show stash information
    --ahead-behind        compute full ahead/behind values
    --porcelain[=<version>]
                          machine-readable output
    --long                show status in long format (default)
    -z, --null            terminate entries with NUL
    -u, --untracked-files[=<mode>]
                          show untracked files, optional modes: all, normal, no. (Default: all)
    --ignored[=<mode>]    show ignored files, optional modes: traditional, matching, no. (Default: traditional)
    --ignore-submodules[=<when>]
                          ignore changes to submodules, optional when: all, dirty, untracked. (Default: all)
    --column[=<style>]    list untracked files in columns
    --no-renames          do not detect renames
    -M, --find-renames[=<n>]
                          detect renames, optionally set similarity index

Pranshuls-MacBook-Air:boston pranshulsingh$ ls
README.md		bluestyle.css		img_hello_world.jpg	index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git checkout main
Switched to branch 'main'
Pranshuls-MacBook-Air:boston pranshulsingh$ git branch
* main
  master
Pranshuls-MacBook-Air:boston pranshulsingh$ ls
README.md	bluestyle.css	index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ git checkout master
Switched to branch 'master'
Pranshuls-MacBook-Air:boston pranshulsingh$ ls
README.md		bluestyle.css		img_hello_world.jpg	index.html
Pranshuls-MacBook-Air:boston pranshulsingh$ 
Pranshuls-MacBook-Air:boston pranshulsingh$ 
Pranshuls-MacBook-Air:boston pranshulsingh$ 
Pranshuls-MacBook-Air:boston pranshulsingh$ git remote add origin https://github.com/devopspranshul/boston.git
Pranshuls-MacBook-Air:boston pranshulsingh$ git push --set-upstream origin master
Enumerating objects: 8, done.
Counting objects: 100% (8/8), done.
Delta compression using up to 4 threads
Compressing objects: 100% (8/8), done.
Writing objects: 100% (8/8), 1.11 KiB | 228.00 KiB/s, done.
Total 8 (delta 1), reused 0 (delta 0), pack-reused 0
remote: Resolving deltas: 100% (1/1), done.
remote: 
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/devopspranshul/boston/pull/new/master
remote: 
To https://github.com/devopspranshul/boston.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
Pranshuls-MacBook-Air:boston pranshulsingh$ 

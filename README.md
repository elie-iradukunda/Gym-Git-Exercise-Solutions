# Gym-Git-Exercise-Solutions

## Bangle 1
## exercise 1

...bash

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ git --version
git version 2.50.0.windows.1

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ git clone https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
Cloning into 'Gym-Git-Exercise-Solutions'...
fatal: unable to access 'https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git/': Could not resolve host: github.com

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ cd GYM-GIT EXERCISE
bash: cd: too many arguments

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ CD .
bash: CD: command not found

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ git config --global
error: no action specified

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ git config --global email iradukundaelie71@gmail.com
error: key does not contain a section: email

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$
 *  History restored 



user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ cd 'c:/Users/user/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git branch
* main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git branch -m main master

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (master)     
$ git branch -m master main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git commit -m 'first file index.html to main' 
[main 764f545] first file index.html to main
 1 file changed, 11 insertions(+)
 create mode 100644 index.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git checkout -b dev
Switched to a new branch 'dev'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git checkout -b test
Switched to a new branch 'test'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (test)       
$ git switch dev
Switched to branch 'dev'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git branch -d <test>
bash: syntax error near unexpected token `newline'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git branch -D <test>
bash: syntax error near unexpected token `newline'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git branch -D test
Deleted branch test (was 764f545).
...

##  bandle1
## exercises 2 solutions commangs

...bash

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git branch
* dev
  main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git checkout main n
error: pathspec 'n' did not match any file(s) known to git

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git checkout main
Switched to branch 'main'
Your branch is ahead of 'origin/main' by 1 commit.
  (use "git push" to publish your local commits)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git push
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads        
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 450 bytes | 450.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
   689b3da..764f545  main -> main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git cheout dev
git: 'cheout' is not a git command. See 'git --help'.

The most similar command is
        checkout

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)       
$ git checkout dev
Switched to branch 'dev'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'home.html pagee'
No local changes to save

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'home.html pagee'
No local changes to save

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'home.html pagee'
Saved working directory and index state On dev: home.html pagee

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'about.html page'
No local changes to save

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git add about.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'about.html page'
Saved working directory and index state On dev: about.html page

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git add team.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'team.html page'
Saved working directory and index state On dev: team.html page

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash list
stash@{0}: On dev: team.html page
stash@{1}: On dev: about.html page
stash@{2}: On dev: home.html pagee

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{0}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (b3731b92c9bb791e77bfb764679a9c1c05d6288e)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash save 'team.html page'
Saved working directory and index state On dev: team.html page

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html

Dropped stash@{1} (6266fa1cedec4d3028cc0d88e46b19568ef91e18)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{2}
fatal: log for 'stash' only has 2 entries

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash list
stash@{0}: On dev: team.html page
stash@{1}: On dev: home.html pagee

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{1}
On branch dev
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   about.html
        new file:   home.html

Dropped stash@{1} (70e95fdeca0e5d68c479364f2f0b7f726e605e9b)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git commit -m 'changes on home page and about page'
[dev 00fa2a0] changes on home page and about page
 2 files changed, 23 insertions(+)
 create mode 100644 about.html
 create mode 100644 home.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git push
fatal: The current branch dev has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin dev

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git push --set-upstream origin dev
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads        
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 580 bytes | 580.00 KiB/s, done.
Total 4 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (1/1), done.     
remote:
remote: Create a pull request for 'dev' on GitHub by visiting:
remote:      https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions/pull/new/dev
remote:
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
 * [new branch]      dev -> dev
branch 'dev' set up to track 'origin/dev'.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash list
stash@{0}: On dev: team.html page

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)        
$ git stash pop stash@{0}
On branch dev
Your branch is up to date with 'origin/dev'.    

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   team.html

Dropped stash@{0} (6a387692b7fe2dea334028bb60bc362f771dd8ec)
user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)
$ git stash list

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (dev)
$ rm team.html
...
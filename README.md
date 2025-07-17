# Gym-Git-Exercise-Solutions



```bash

## Bandle 1
## exercise 1

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


##  bandle1
## exercises 2 solutions commangs



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


## bandle 2
##   exercise1

$ git checkout -b ft/bundle-2
Switched to a new branch 'ft/bundle-2'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git add service.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git commit -m 'service.html page created'
[ft/bundle-2 d7ee4e9] service.html page created
 1 file changed, 11 insertions(+)
 create mode 100644 service.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/bundle-2)
$ git push origin ft/bundle-2
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 435 bytes | 435.00 KiB/s, done.
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)        
remote: Resolving deltas: 100% (1/1), completed with 1 local object. 
remote:
remote: Create a pull request for 'ft/bundle-2' on GitHub by visiting:
remote:      https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions/pull/new/ft/bundle-2
remote:
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git 
 * [new branch]      ft/bundle-2 -> ft/bundle-2

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/bundle-2)


## bandle 2
## exercises 2


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise
$ cd 'c:/Users/user/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git fetch origin
git pull origin main         # Get the latest updates from main branch 
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
   e0a8fb1..fcf512f  ft/service-redesign -> origin/ft/service-redesign
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD
Updating e0a8fb1..8e16377
Fast-forward
 service.html | 3 +++
 1 file changed, 3 insertions(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git merge main
Already up to date.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git commit -m "Merge main into ft/service-redesign"
[ft/service-redesign 66c95f1] Merge main into ft/service-redesign
 3 files changed, 47 insertions(+), 23 deletions(-)
 delete mode 100644 services.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)
$ git push origin ft/service-redesign
Enumerating objects: 7, done.
Counting objects: 100% (7/7), done.
Delta compression using up to 16 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 823 bytes | 823.00 KiB/s, done.
Total 4 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.  
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git   
   fcf512f..66c95f1  ft/service-redesign -> ft/service-redesign        

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/service-redesign)

## bandle 3 
## exercise 1

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/team-page)
$ git checkout ft/contact-page
Switched to branch 'ft/contact-page'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry-pick b3f3ec8
On branch ft/contact-page
You are currently cherry-picking commit b3f3ec8.
  (all conflicts fixed: run "git cherry-pick --continue")
  (use "git cherry-pick --skip" to skip this patch)  
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Untracked files:
use "git add" to track)
The previous cherry-pick is now empty, possibly due to conflict resolution.
use "git add" to track)
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page|CHERRY-PICKING)
$ git cherry-pick --skip

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git cherry-pick b3f3ec8
On branch ft/contact-page
You are currently cherry-picking commit b3f3ec8.
  (all conflicts fixed: run "git cherry-pick --continue")       
  (use "git cherry-pick --skip" to skip this patch)
  (use "git cherry-pick --abort" to cancel the cherry-pick operation)

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        t commit and copy its hash- Checkout again using git cherry-pick get the changes from the last commit on the branch.- Add new changes for the contact page and commit, push them- Create a new PR for the contact page

nothing added to commit but untracked files present (use "git add" to track)
The previous cherry-pick is now empty, possibly due to conflict resolution.
If you wish to commit it anyway, use:

    git commit --allow-empty

Otherwise, please use 'git cherry-pick --skip'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page|CHERRY-PICKING)
$ git cherry-pick --skip

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .
error: open("t commit and copy its hash- Checkout again using git cherry-pick get the changes from the last commit on the branch.- Add new changes for the contact page and commit, push them- Create a new PR for the contact page"): Filename too long        
error: unable to index file 't commit and copy its hash- Checkout again using git cherry-pick get the changes from the last commit on the branch.- Add new changes for the contact page and commit, push them- Create a new PR for the contact page'
fatal: adding files failed

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)
$ rm "t commit and copy its hash- Checkout again using git cherry-pick get the changes from the last commit on the branch.- Add new changes for the contact page and commit, push them- Create a new PR for the contact page"

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)
$ git add .
git commit -m "feat: add contact page content"
git push origin ft/contact-page
[ft/contact-page c2a10ec] feat: add contact page content
 1 file changed, 11 insertions(+)
 create mode 100644 contact.html
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 441 bytes | 441.00 KiB/s, done.    
Total 3 (delta 1), reused 0 (delta 0), pack-reused 0 (from 0)   
remote: Resolving deltas: 100% (1/1), completed with 1 local object.
remote:
remote: Create a pull request for 'ft/contact-page' on GitHub by visiting:
remote:      https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions/pull/new/ft/contact-page
remote:
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/contact-page -> ft/contact-page

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/contact-page)



## bandle3 
## exercise2


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/team-page) 
$ git checkout ft/faq-page
Switched to branch 'ft/faq-page'
Your branch is up to date with 'origin/ft/faq-page'.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/faq-page)  
$ git checkout -b ft/home-page-redesign
Switched to a new branch 'ft/home-page-redesign'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git checkout main 
Switched to branch 'main'
Your branch is up to date with 'origin/main'.    

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git pull origin main 
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.      
remote: Compressing objects: 100% (2/2), done.   
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (2/2), 1.75 KiB | 256.00 KiB/s, done.
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD    
   7222623..67f0eb8  main       -> origin/main
Updating 7222623..67f0eb8
Fast-forward
 README.md    | 85 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 contact.html | 11 ++++++++
 faq.html     | 11 ++++++++
 3 files changed, 106 insertions(+), 1 deletion(-)
 create mode 100644 contact.html
 create mode 100644 faq.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git commit -m"some changes in main"
[main 5ac4193] some changes in main
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
   67f0eb8..5ac4193  main -> main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git fetch origin
git rebase origin/main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git commit -m"changes for home page"
[ft/home-page-redesign c9cf803] changes for home page
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push 
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$





##bandle 4 exercise 1
user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git pull origin main 
remote: Enumerating objects: 2, done.
remote: Counting objects: 100% (2/2), done.      
remote: Compressing objects: 100% (2/2), done.   
remote: Total 2 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (2/2), 1.75 KiB | 256.00 KiB/s, done.
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD    
   7222623..67f0eb8  main       -> origin/main
Updating 7222623..67f0eb8
Fast-forward
 README.md    | 85 +++++++++++++++++++++++++++++++++++++++++++++++++++++++++++-
 contact.html | 11 ++++++++
 faq.html     | 11 ++++++++
 3 files changed, 106 insertions(+), 1 deletion(-)
 create mode 100644 contact.html
 create mode 100644 faq.html

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git commit -m"some changes in main"
[main 5ac4193] some changes in main
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 334 bytes | 334.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
   67f0eb8..5ac4193  main -> main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git checkout ft/home-page-redesign
Switched to branch 'ft/home-page-redesign'

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git fetch origin
git rebase origin/main
Successfully rebased and updated refs/heads/ft/home-page-redesign.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git commit -m"changes for home page"
[ft/home-page-redesign c9cf803] changes for home page
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push 
fatal: The current branch ft/home-page-redesign has no upstream branch.
To push the current branch and set the remote as upstream, use

    git push --set-upstream origin ft/home-page-redesign

To have this happen automatically for branches without a tracking
upstream, see 'push.autoSetupRemote' in 'git help config'.


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git push --set-upstream origin ft/home-page-redesign
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 371 bytes | 371.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
remote:
remote: Create a pull request for 'ft/home-page-redesign' on GitHub by visiting:
remote:      https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions/pull/new/ft/home-page-redesign
remote:
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
 * [new branch]      ft/home-page-redesign -> ft/home-page-redesign
branch 'ft/home-page-redesign' set up to track 'origin/ft/home-page-redesign'.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (ft/home-page-redesign)
$ git checkout main 
M       README.md
Switched to branch 'main'
Your branch is up to date with 'origin/main'.    

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git pull origin main 
remote: Enumerating objects: 1, done.
remote: Counting objects: 100% (1/1), done.      
remote: Total 1 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (1/1), 905 bytes | 452.00 KiB/s, done.
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD    
   5ac4193..adce3da  main       -> origin/main
Updating 5ac4193..adce3da
Fast-forward
 home.html | 1 +
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git status 
On branch main
Your branch is up to date with 'origin/main'.    

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        modified:   README.md


user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git pull origin main 
From https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions
 * branch            main       -> FETCH_HEAD    
Already up to date.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add .

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git commit -m"readme updated for bandle 3 solution"
[main 59c2780] readme updated for bandle 3 solution
 1 file changed, 107 insertions(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 1.04 KiB | 1.04 MiB/s, done.
-iradukunda/git-exercise-copy.git

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git remote -v
git-copy        https://github.com/elie-iradukunda/git-exercise-copy.git (fetch)
git-copy        https://github.com/elie-iradukunda/git-exercise-copy.git (push)
origin  https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git (push)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add .
git commit -m "chore: update home page for bundle 4"
[main 493da10] chore: update home page for bundle 4
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push origin main
git push git-copy main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 359 bytes | 89.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
   59c2780..493da10  main -> main
To https://github.com/elie-iradukunda/git-exercise-copy.git
 ! [rejected]        main -> main (fetch first)
error: failed to push some refs to 'https://github.com/elie-iradukunda/git-exercise-copy.git'
hint: Updates were rejected because the remote contains work that you do not
hint: have locally. This is usually caused by another repository pushing to
hint: the same ref. If you want to integrate the remote changes, use
hint: 'git pull' before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git pull git-copy main --rebase
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 867 bytes | 108.00 KiB/s, done.
From https://github.com/elie-iradukunda/git-exercise-copy
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> git-copy/main
Auto-merging README.md
CONFLICT (add/add): Merge conflict in README.md
error: could not apply 689b3da... Initial commit
hint: Resolve all conflicts manually, mark them as resolved with
hint: "git add/rm <conflicted_files>", then run "git rebase --continue".
hint: You can instead skip this commit: run "git rebase --skip".
hint: To abort and get back to the state before "git rebase", run "git rebase --abort".
hint: Disable this message with "git config set advice.mergeConflict false"
Could not apply 689b3da... # Initial commit

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main|REBASE 1/21)
$ git push git-copy main
To https://github.com/elie-iradukunda/git-exercise-copy.git
 ! [rejected]        main -> main (non-fast-forward)
error: failed to push some refs to 'https://github.com/elie-iradukunda/git-exercise-copy.git'
hint: Updates were rejected because a pushed branch tip is behind its remote
hint: counterpart. If you want to integrate the remote changes, use 'git pull'
hint: before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main|REBASE 1/21)
$ git rebase --continue
README.md: needs merge
You must edit all merge conflicts and then
mark them as resolved using git add

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main|REBASE 1/21)
$ git push git-copy main --force
Enumerating objects: 82, done.
Counting objects: 100% (82/82), done.
Delta compression using up to 16 threads
Compressing objects: 100% (80/80), done.
Writing objects: 100% (82/82), 19.41 KiB | 1.94 MiB/s, done.
Total 82 (delta 41), reused 3 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (41/41), done.
To https://github.com/elie-iradukunda/git-exercise-copy.git
 + f265307...493da10 main -> main (forced update)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main|REBASE 1/21)
$ git rebase --abort

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git remote add git-copy https://github.com/elie-iradukunda/git-exercise-copy.git
error: remote git-copy already exists.

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git remote -v
git-copy        https://github.com/elie-iradukunda/git-exercise-copy.git (fetch)
git-copy        https://github.com/elie-iradukunda/git-exercise-copy.git (push)
origin  https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git (fetch)
origin  https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git (push)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git add home.html
git commit -m "chore: update homepage with new paragraph"
[main 929db27] chore: update homepage with new paragraph
 1 file changed, 1 insertion(+)

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elie-iradukunda/Gym-Git-Exercise-Solutions.git
   493da10..929db27  main -> main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$ git push git-copy main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 369 bytes | 369.00 KiB/s, done.    
Total 3 (delta 2), reused 0 (delta 0), pack-reused 0 (from 0)   
remote: Resolving deltas: 100% (2/2), completed with 2 local objects.
To https://github.com/elie-iradukunda/git-exercise-copy.git     
   493da10..929db27  main -> main

user@LAPTOP-V9PT987N MINGW64 ~/Desktop/gym-git-exercise/Gym-Git-Exercise-Solutions (main)
$



```



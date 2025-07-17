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
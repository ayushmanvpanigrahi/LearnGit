# Learn Git
Learning git commands

============================================================================================================================================================================================

what is Git?
Git is a version control system.
It is a tool that helps to track changes in code.

featues:-
popular 
free and open source
fast and scalable

purpose:-
track the history 
save and revert changes
save completly in the GitHub.

============================================================================================================================================================================================


--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

Implementation:-

1) How create a new repo through the GitHub.

2) How To check the version of the git: ~> git --version

3) How to clone the repository in our local machine: ~> git clone "repo link"

4) how to check the hidden folder of the git :- (gitbash) ~> ls -a

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------



5) How to Configuring the Git : ~> git config --global user.name "enter github name"
                                   git config --global user.email "enter register email of the github"
			           git config --list



--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

State And Types of State :- 
untracked or modified -> Staged(git add .) -> 
(if you see that some files is untracked or new files are created or if you see that in some files the code is modified and you satisfied with the modified files or code then you can add the changes.)

modified -> Staged(git commit -m "some message"): "It will save the updated files or codes 
(if you satisfied with the Updated code or files but you want to make more modifications in the code or files then you can commit to save the changes which is correct.) -> 

what is mean by origin ?
-> origin is a name of the folder that we have specified for the specific repository that we can get help to save the files or folders or contents in the specific repository.

modified -> save in github (git push origin main): "it will upload modified content,codes or files to the github from local" ->
(if you satisfied with the output of the code or files then you can push the code in the GitHub).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

6) How to display the state of the code or project state: ~> git status

7) How to make "Changes not staged for commit" the code or project state if modified or untracked: ~> git add .

8) How to make "Changes to be committed" the code or project state if "Changes is staged for commit" is done: ~> git commit -m "some message"

8) How to upload all changes that you have made so that the project will save or stay up to date in the github or upload modify content to the github from local: ~> git push origin main
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

9) if you make the new folder in the local system and you make the folder into git repo then how can you do using the git command : ~> git init

10) How to see the name of the remote or specific repository name or specific folder name (which when making any changes that we can push with the help of that name) that we can check using git command :- git remote -v

11) And How if we want to define the name of the folder and for the specific repository using git command : ~> git remote add "any name like origin " "repo link"
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

12) how if i want to upload the files or folders in GitHub with the new repository, i can start by using this command : 
                     ~> git init
                     >  create a new repository in GitHub
                     ~> git remote add "any name like origin " "repo link"
		             ~> git push "any name" main

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

13) how to check which branch currently you are in : ~> git branch

14) i you want to rename the branch name then how can you do that : ~> git branch -M "enter new name of the current branch"

15) how to create a new branch : ~> git checkout -b "enter name of the new branch"

16) how to switch in any branch : ~> git checkout "if exits enter branch name that you want to navigate"

17) how to delete the branch : ~> git branch -d "if exits enter branch name that you want to delete new changes in branch "two" "

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

18) how to do if you make some changes in the new branch and you want to save the new changes on the GitHub you can use this command:
~> git add .
~  git commit -M "new branch commit"
~  git push origin "if exits enter the new branch name in which you want to save the changes"
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

19) how to check the changes in two different branches: ~> git diff "if exits enter the name of the branch that you want to check the difference"

20) how to merge the two branches : ~> git merge "if exits enter the name of the branch that you want to merge with"
(option 2) : you can use "compare and pull request" in GitHub to merge and save the changes in the main branch.

21) if you use option 2 then you have to use one more git command to see the changes in the main branch on local machine: ~> git pull origin main
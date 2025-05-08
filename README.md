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

State means :- 
untracked or modified -> Staged(git add .) -> 
(if you see that some files is untracked or new files are created or if you see that in some files the code is modified and you satisfied with the modified files or code then you can add the changes.)

Commit(git commit -m "some message"): "It will save the updated files or codes 
(if you satisfied with the Updated code or files but you want to make more modifications in the code or files then you can commit to save the changes which is correct.) -> 

push(git push origin main): "it will upload modified content,codes or files to the github from local" ->
(if you satisfied with the output of the code or files then you can push the code in the GitHub).

--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

6) How to display the state of the code or project state: ~> git status

7) How to make "Changes not staged for commit" the code or project state if modified or untracked: ~> git add .

8) How to make "Changes to be committed" the code or project state if "Changes is staged for commit" is done: ~> git commit -m "some message"

8) How to upload all changes that you have made so that the project will save or stay up to date in the github or upload modify content to the github from local: ~> git push origin main
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

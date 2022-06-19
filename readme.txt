# Trivia_Game
Link to Gitlab Beginners Guide

Commands/ Shortcuts:
ls (lists the current directory contents)
vim (Creates and Edits Files Efficiently)

rm -rf -- <file/folder you want to remove> (When you want to remove a file/folder)

Other Git Commands
.gitignore </config> (If you dont want to add file/folder in git commits)


These are the steps I took to create this game.
1. Created new Directorycalled "Trivia_Game"

2. Create new Git  Repository
  a. git status (Tells you the current status of the Git Repo)
    b. git init (This initializes a new git repository in the "Trivia_Game" directory)
      
      3. Configuring Git
        Note: This will allow others to see who you are and who made changes in the Git repository
	  Git Global Setup
	    a. git config --global user.name "rthavixay23" 
	      b. git config --global user.email "rthavixay@ucsd.edu" 
	        c. git add . (Stage changes for commit note: Including the "." to add)
		  d. git commit (This creates a snapshot and commits staged changes)
		    

		    4. Setting up SSH Keys for GitHub
		      Note: SSH Keys (For security) 
		        a. ssh-keygen -t ed25519 -C rthavixay@ucsd.edu
			  b. eval "$(ssh-agent -s)"
			    c. ~/.ssh/config (Check if ssh folder exists)
			      d. touch ~/.ssh/config ("touch" Create the ssh config directory) 
			        Note: ~/. (means home directory)
				  e. vim ~/.ssh/config (this will let us edit the file we created)
				      NOTE: WE WILL EDIT THE FILE TO ADD PRIVATE KEY IN THE SSH AGENT
				          i. HOST *
					           AddKeysToAgent yes
						            NOTE: Remember to press [ESC] then type [:wq] (this will save and exit out the text file editor)
							       
							         
								   


								   5. Pushing to an existing folder





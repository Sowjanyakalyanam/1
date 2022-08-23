# Testing Github

## Commands for git:
- cloning a repository
	- git clone "https://github.com/Sowjanyakalyanam/1.git"
- Go to the path to create a file:
	- ```cd Sowjanyakalyanam/1```
- create a new branch:
	- ```git checkout -b <branch_name>```: -b used when we create a new branch
	- ```git checkout <branch_name>```: to checkout already existing branch
- Need to create a file:
	- Editors used: vim <file_name>
	- command: touch <file_name>
- Adding file to git:
	- ```git add <file_name>```
- check status of a added file:
	- ```git status```
- commit the file:
	- ```git commit -m "message"```
- push the branch
	- ```git push origin <branch_name>```
- create a pull request:
	- We can create it either in the chrome from pull request tab or from the link we get from the git push origin <branch_name> command
- Merge the Pull request:
	- Merge the pull request if it doesn't have any conflicts.

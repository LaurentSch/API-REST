# Version Control Assignment

## Documentation of steps followed to complete this assignment

### Created a new directory with:
	mkdir Assignment_Version_Control
### Initialized a git repository with:
	git init
### Download the Node.gitignore file from the gitignore repo
### Stage the Node.gitignore file:
	git add Node.gitignore
#### (Use git status to make sure it worked)
### Add origin:
	git remote add origin https://github.com/LaurentSch/API-REST.git
### Create a github token and use:
	git push -u origin master
### Create dev branch
	git branch dev
#### (Check if it worked "git log --oneline --decorate")
### Change the HEAD pointer from the master to the dev branch
	git checkout dev
### Unpacked the provided .zip and staged the myapp folder:
	git add myapp/


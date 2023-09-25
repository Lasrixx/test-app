# Instructions for Git
* git clone url.com // to clone the repository
* cd into the folder you have cloned
* git status // to see the status of our folder
* git add readme.md // to prepare file for commit
* git status
* git commit -m "Readme file updated" // to commit the file
* git remote add origin https://github.com/Lasrixx/test-app.git // say we want all commits to go to this location
* git push -u origin main // to push the committed changes to repo
## Extra Comments
* git add can have multiple endings:
	* git add readme.md
		* This will add a single file to the staging area
	* git add readme.md index.ts
		* This will add 2 files to the staging area
	* git add .
		* This will add all changed files to the staging area
	* git add *
		* This will add all changes in the current directory but not the sub-directory
	* git add -all OR git add -A
		* This will add hidden files (usually beginning with .) but try not to add hidden files 

# VS Studio demonstration
* Using the git changes window, we can use a GUI instead of command line for git commits
* Find in view -> git changes

# Branching
* Create new branch: git branch branchname
* Move to new branch: git checkout branchname
* Push to new branch: git push --set-upstream origin branchname
## To merge branches
* git checkout main // to go back to main branch
* git merge branchname // to merge branches
* git push origin main // to push merge
* git branch -d branchname // to delete unneeded branch
* git branch -D branchname // force delete branch even if there are unmerged changes

# Other features
## Issues
* For raising tickets
## Projects
* For managing the project, with kanban boards or to-do lists...
## Actions
* For automating parts of the project
* For example, checking if unit tests exist / pass, checking if the product can deploy
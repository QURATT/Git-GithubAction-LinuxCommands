# Git-GithubAction-LinuxCommand

## Getting & Creating Projects

    git init
    git clone ssh://git@github.com/[username]/[repository-name].git
    
## Branching & Merging
List branches (the asterisk denotes the current branch)
	
	git branch   
List all branches (local and remote)    

    git branch -a
Create a new branch    

	git branch [branch name]
Delete a branch

    git branch -d [branch name]
 Create a new branch and switch to it
 
    git checkout -b [branch name]
Switch to a branch

	git checkout [branch name]
Merge a branch into the active branch

	git merge [branch name]
Merge a branch into a target branch

	git merge [source branch] [target branch

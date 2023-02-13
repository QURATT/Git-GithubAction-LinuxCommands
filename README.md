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
	
## File and directory commands

**1. pwd:** The pwd(Present Working Directory) command is used to print the name of the present/current working directory starting from the root.
	
	$ pwd
	/home/sj/Desktop/Linux

**2. mkdir:** The mkdir(make directory) command allows users to create directories or folders.
	
	$ mkdir ubuntu
	$ ls
	ubuntu
The option '-p' is used to create multiple directories or parent directories at once.

	$ mkdir -p dir1/dir2/dir3
	$ cd dir1/dir2/dir3
	~/Desktop/Linux/dir1/dir2/dir3$

**3. rmdir:** The rmdir(remove directories) is used to remove empty directories. Can be used to delete multiple empty directories as well. Safer to use compared to rm -r FolderName. This command can also be forced to delete non-empty directories.

 a. Remove empty directory:

	rmdir FolderName
  b. Remove entire directory tree. This command is similar to rmdir a/b/c a/b a:
  
	rmdir -p a/b/c
  c. Remove multiple directories:

	rmdir FolderName1 FolderName2 FolderName3

  d. Remove non-empty directories:

	rmdir FolderName1 --ignore-fail-on-non-empty

# linux
linux commands

echo :echo is a command that output the strings that are passed to it as arguments.
echo "hello world"

whoami: to check current user in linux machine

pwd: to check current path directory you are working in

git init:	Initialize a local Git repository
git clone: ssh://git@github.com/[username]/[repository-name].git	Create a local copy of a remote repository

git status:	Check status

git add [file-name.txt]	Add a file to the staging area
git add -A	Add all new and changed files to the staging area
git commit -m "[commit message]"	Commit changes
git rm -r [file-name.txt]	Remove a file (or folder)

Branching & Merging
git branch	List branches (the asterisk denotes the current branch)
git branch -a	List all branches (local and remote)
git branch [branch name]	Create a new branch
git branch -d [branch name]	Delete a branch
git push origin --delete [branch name]	Delete a remote branch
git checkout -b [branch name]	Create a new branch and switch to it
git checkout -b [branch name] origin/[branch name]	Clone a remote branch and switch to it
git branch -m [old branch name] [new branch name]	Rename a local branch
git checkout [branch name]	Switch to a branch
git checkout -	Switch to the branch last checked out
git checkout -- [file-name.txt]	Discard changes to a file
git merge [branch name]	Merge a branch into the active branch
git merge [source branch] [target branch]	Merge a branch into a target branch
git stash	Stash changes in a dirty working directory
git stash clear	Remove all stashed entries

Sharing & Updating Projects
git push origin [branch name]	Push a branch to your remote repository
git push -u origin [branch name]	Push changes to remote repository (and remember the branch)
git push	Push changes to remote repository (remembered branch)
git push origin --delete [branch name]	Delete a remote branch
git pull	Update local repository to the newest commit
git pull origin [branch name]	Pull changes from remote repository
git remote add origin ssh://git@github.com/[username]/[repository-name].git	Add a remote repository
git remote set-url origin ssh://git@github.com/[username]/[repository-name].git	Set a repository's origin branch to SSH



Inspection & Comparison
git log	View changes
git log --summary	View changes (detailed)
git log --oneline	View changes (briefly)
git diff [source branch] [target branch]	Preview chan



$ ls <flag>
ls <path name> : By specifying the path after ls, the content in that path will be displayed

ls –l: Using ‘l’ flag, lists all the contents along with its owner settings, permissions & time

ls –a:Using ‘a’ flag, lists all the hidden contents in the specified directory


sudo:This command executes only that command with root/ superuser privileges.
syntax:
$ sudo <command>
sudo useradd <username>:Adding a new user
sudo passwd <username>:Setting a password for the new user
sudo userdel <username>:Deleting the user
sudo groupadd <groupname>:Adding a new group
sudo groupdel <groupname>: Deleting the  group
sudo usermod -g <groupname> <username>:Adding a user to a primary group



$cat
This command can read, modify or concatenate text files. It also displays file contents.
$ cat <flag> {filename}

Description
cat -b:This adds line numbers to non-blank lines

cat -n:This adds line numbers to all lines

cat -s:This squeezes blank lines into one line


$grep:This command searches for a particular string/ word in a text file. This is similar to “Ctrl+F” but executed via a CLI.
$ grep <flag or element_to_search> {filename}
grep -i:Returns the results for case insensitive strings

grep -n:Returns the matching strings along with their line number

grep -v:Returns the result of lines not matching the search string

grep -c:Returns the number of lines in which the results matched the search string



$sort
This command sorts the results of a search either alphabetically or numerically. It also sorts files, file contents, and directories.
$ sort <flag> {filename}

sort -r:the flag returns the results in reverse order;

sort -f:the flag does case insensitive sorting

sort -n:the flag returns the results as per numerical order





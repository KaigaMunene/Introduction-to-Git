# Introduction to Git and GitHub
## Setting up a repository
+ A git repository is a virtual storage for your project. Allows you to save versions of your code which you can access when needed.
+ To initialize a Git repository use **git init** command. Executing this command will create a new .git subdirectory in your current working directory. This will also create a new main branch. 
+ Clone an existing repository ($ git clone ssh://user@domain.com/repo.git)

## Basic git commands
+ git status- command tells you about how your project is progressing in comparison to your Git repository.
+ git add - add all current changes to staging area/ to the next commit.
+ git diff - show changes to tracked files.
+ git commit -m "the message" -commit previously staged changes. (git commit -a commit all changes on tracked files)
+ git log - show all the commits starting with the newest.
+ git branch <new branch> creates a new branch based on your current HEAD.
+ git push <remote> <branch> -publish local changes on a remote
+ git pull - download changes from the repository
+ rm -rf .git - to undo a git init if you did it in a wrong folder.   
+ git rebase - rebasing is the process of moving or combining a sequence of commits to a new base commit.

## Other minnor commands
+ $ pwd Cprint working directory)- It will return the path to a local folder on your computer's disk.
+ Change directory(cd) - command in terminal to change this current working directory.
  $ cd .. - to move one directory upwards into the current folder's parent folder.
  $ cd name-of-subfolder/sub-subfolder/ to move subfolders.
  $ cd ~ - to your user account home folder.
+ ls - command that lists the file contents of a directory. Use this command with two additional options: "-l" formats the output list a little more structured and "-a" also lists "hidden" files ($ ls -la).
+ To remove a file ($ rm path/to/file.ext)
+ When trying to delete a folder, however, please note that you'll have to add the "-r" flag (which stand for "recursive"):($ rm -r path/to/folder).
+ To move a file ($ mv path/to/file.ext different/path/file.ext) the "mv" command can also be used to rename a file ($ mv old-filename.ext new-filename.ext)
+ To copy a file you can use the "cp" command instead of "mv".
+ To make a new folder directory (mkdir new-folder).
+ The "cat" command outputs the whole file in one go: ($ cat file.ext)  the "head" command displays the file's first 10 lines, while "tail" shows the last 10 lines. You can simply scroll up and down in the output like you're used to from other applications.
+ ($ less file.ext) - Although it's also used to display output, it controls page flow itself. This means that it only displays one page full of content and then waits for your explicit instructions. You'll know you have "less" in front of you if the last line of your screen either shows the file's name or just a colon (":") that waits to receive orders from you. Hitting SPACE will scroll one page forward, "b" will scroll one page backward, and "q" will simply quit the "less" program.
+ CTRL key - pressing CTRL+A moves the caret to the beginning of the line, while CTRL+E moves it to the end of the line.

## Why git ?
+ Saves time - its quite fast.
+ You can work offline because you have a local repository in your machine you dont have to be connected to the server.
+ Undo mistakes - A good thing about Git is that there's a little "undo" command for almost every situation. Correct your last commit because you forgot to include that small change. Revert a whole commit because that feature isn't necessary, anymore. And when the going gets tough you can even restore disappeared commits with the Reflog - because, behind the scenes, Git rarely really deletes something.
+ don't worry 
+ Make useful commits.
+ Work in your own way.
+ Don't mix things up.
+ work with the flow.

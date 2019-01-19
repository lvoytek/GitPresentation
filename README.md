# Git and Version Control Concepts
## Presented by Lena Voytek
### Firmware Developer, JACOBS Engineering
### Email: dvoytek@email.arizona.edu



## Installing Git:

Windows: [Git SCM for Windows](https://git-scm.com/download/win) or Ubuntu Subsystem on the Microsoft Store  
Mac: [Git SCM for Mac](https://git-scm.com/download/mac) or typing __git --version__ in Terminal  
Ubuntu: __sudo apt install git__ on command line


## Git Commands:

### Init
Initialize a Git repository locally
Usage: __git init__

### Clone
Download a git project from an external repository
Usage: __git clone [URL]__

### Add
Add a set of files staging in preparation for a commit
Usage: __git add [List of Files]__

### Commit
Commit all files that are currently staged, using a given commit message
Usage: __git commit -m "Commit Message"__

### Push
Send all commited items to the origin repository
Usage: __git push__

### Pull
Get new changes from a remote repository
Usage: __git pull__

### Branch 
List, create, or delete repository branches
Usage: __git branch -<Option> [branch name]__

### Checkout
Change your working directory into a given branch
Usage: __git checkout [branch name]__

### Merge
Merge diverged branch with original
Usage: __git merge [diverged branch name]__
For more info on Branch Handling see [this site](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell)


For further details on git command type __git [command name] --help__ or see the git man page using __man git__


## Handling Merge Conflicts
More information on conflicting files can be found [here](https://help.github.com/articles/resolving-a-merge-conflict-using-the-command-line/#platform-all)

## Markdown Files
General Syntax available [here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

## Other Version Control Systems
[SVN](https://subversion.apache.org/)
[Mercurial](https://www.mercurial-scm.org/)
[TFS](https://visualstudio.microsoft.com/tfs/)

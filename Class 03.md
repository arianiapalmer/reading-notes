# Class 03
* Class notes for Code 102 with code fellows, starting May 23, 2022 ending May 27, 2022
## Class 03 - May 24, 2022
### *Reading 3: Revisions and The Cloud - GitHub.*
### **Github**
Github is a Distributed Version Control system (DVCS). It allows a team of developers to work on a single file or a set of files on a single server, which can be asccessed by various clients. The DVCS allows clients to create mirroed repositories, which serve as data backups than can be placed on the servier to replace any lost information should the server go down. This helps to prevent any catastrophic loss of content.
Files in Git can reside in three main states :
1. Commited - data is securely stored in a database
2. Modified - files have beenc hanged but not committed to the database
3. Staged - flageged a file's changed version to be commmited in the next snapshot

<sub> github can be installed on Mac, Widnows, and Linux</sub>

**Using Github**

Customization
* git config allows the setting of configuration variabled that control Git's operation and look
* using the option --global allow the settings to be applied to anything on the system. tp use different config settings for a specific project, you can change the working directory and use config without --global

Default Text Eidtor
* Git will use the system's default text editor but to configure a differetn one, use the command $ git config --global core.editor "nameofeditor"

Check settings
* use git config --list to check your settings

Setting up Git Repository
To Import an existing project 
> - Switch directory to target project
> - Use the git init command
> - To track reposity files perform ana dditional commit 
> > $ git add * . c (without the spaces)
> > $ git add LICENSE
> > $ git commit -m "any message here"

You can clone an existing repository by use the clone command with a repository's URL
> $ git clone https:/ /github. com/test
To clone into a directory with another name of your choosing
> $ git clone https: // github.com /test my directory

Local Repository
> Local Git repository has three components
> - Working directory : where the actual files reside
> - Index: the area used for staging
> - Head: points to the most recent commit

Tracked and Untracked States
> - Tracked - tracked files can be modified, unmodified , or staged; they were part of the most recent file snapshot
> - Untracked - Untracked files were not in the lst snapshot and do not currently reside in the staging area

Life Cycle of File Status 
> - After you edit a file, Git flags it as modified because of changes made after the previous commit.
> - You stage the modified file.
> - Then, you commit staged changes.

Check File Status
> $ git status

Tracking and Staging a New File
> git add filename
> $ git add *

Committing a File
> commmit changes and recored what you changed
> $ git commit -m “made change x,y,z”
> $ git commit -a

Stashing Changes
> For when you're not ready to commit to a change but don't want to lose them either use:
> - git stash
> 
> When ready to commit, use:
> 
> - git stash apply

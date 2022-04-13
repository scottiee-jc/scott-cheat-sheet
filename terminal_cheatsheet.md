# Cheat de la Sheet

### This is a cheat sheet developed by scottie for the use of command line codes.

#### Basic Command-Line Code

Command-line code is used to enter commands to the operating system and so bypasses a graphical user interface (gui). This makes it easy and accessible to move, create, delete and duplicate files and folders, as well as to help interact with community resources such as github.

Here is a list of some easy-to-follow command-lines to get started using terminal.

**pwd** is used in order to locate which directory you are in within your operating system. For instance, a folder directory within a larger root folder would read /Users/scottc. The parent folder comes first, followed by the baby folder.

**ls** is a list command, which brings up the list of folders within its parent folder. From here, you can use commands that will request further detail:

  *ls -l* stands for "long-list" and this gives more information about the location and changes to each folder and file

  *ls -a* brings up all files and folders, including hidden ones

  *ls -al* brings up a long list of everything within the root directory

**Clear** is a useful command that moves your previous command lines above the current screen, without removing it, so you have a nice clear space to work within

**cd** means to "change directory". To select the folder / directory you want to edit / look within, you need simply type in "cd *name of folder*" and this will allow you to access the files within this folder/directory. If you type in a space and leave it blank, i.e. "cd ", it will simply take you back to the root directory. If you add in ".." after "cd", it will take you one level back up the root tree, e.g. from "scottc" to "Users".

**mkdir** will create a new directory or folder. When creating a new file, it is highly useful to use an underscore between the words, i.e. "scottie_folder" and remember it is case sensitive! You cannot use forward dashes or a dot, as these indicate file extension (.) or will search for a file (/)

**touch** is a command for creating a *file*. When creating a file, there are three key components. The touch command, the file name, and the extension. An example is "touch file_name.txt". A space is left between touch and the file, which is seperated by an underscore, and finally superceded by a ".txt, .png, .md" etc. depending on what file attachement you are creating.

**mv** is a command to either move or rename a file. To move a file, you'll need to type "mv" the name of the file, add a space and then the name of the folder you're attempting to move the file to. Alternatively, to rename the the file, you simply type 'mv' and the name of the file after, e.g. "mv name_of_file.txt"

**rm** this command fully removes a file from the system.

  *rm -r* is used to remove a folder or directory from the operating system FOREVER! So, be warned...

#### Creating a repository

##### A repository is a storage location that, for the purposes of git, tracks and saves the history of all changes made to the files in a Git project.

**init** is a command line that initialises something, so **git init** will initialise a git repository.

**git add** includes a feature in which git has to pay specific attention to a file.

At this point, a yellow "x" may appear, which indicates that an action, such as update/save has not yet been committed by git.

**git commit -m** helps indicate to git that something has been updated in a file that needs to be saved. Follow this with "first commit" to save the first changes.

**git push origin main** is the command we use to upload something to github. When you do this, you need three lines of code that has been created when you create a repository on github, allowing the terminal to communicate with github. It follows the general pattern:

    git remote add origin git@github.com:<your_github_name>/<your_repo>.git
    git branch -M main
    git push -u origin main 

Hopefully this is helpful for anyone reading! :)






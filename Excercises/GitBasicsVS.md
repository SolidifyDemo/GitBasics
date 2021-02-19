# Git basics



## Excercise 1, creating a repo

* Create a remote repository **on your own GitHub account**, named **GitBasics**. You can make it public or private.
* Initialize it with a readme.md file. The readme file should be your kind of table of content.
* Use this repo to for the labs
* Decide a place on your PC, **a base  folder**, below this all your repositories should be placed. On my machine, I have a "D:\repos".   
 
It is wise to keep this base path short.  (The default for VS is to place this under your own user folder, down under Documents and so on, that will in many cases lead to path problems)
 
* Clone this repository to your local machine under the selected folder.  That way it is easier to work on with your local editor.  
* Open Visual Studio, click on "Git" menu and choose Clone repor, select where and what you want to clone.
 


## Excercise 2, add and commit your code

* Use Visual Studio to create a Small project sample in the cloned folder:
* Open "Git Changes" view your changes and note what files are shown
* Go to [gitignore.io](https://gitignore.io) and create a gitignore for your language of choice  (e.g. *csharp* for dotnet). For non-dev, choose *csharp* too. A course this can be done when you create the repo in GitHub as well.
* Add that to a file named **.gitignore**  (note the **dot** in front)
* Check "Git Changes" view again, and note again what files are shown
* Run the git status command again, and note again what files are shown.
 
* Stage and commit the code/files you have.
 
* To change from unstaged to staged click on the "+" sign and add a commit message "My first commit" and click "Commit All/Commit Staged"
 
 
### Note

All repos you create should always have the following files
 
*  readme.md
*  .gitignore
 
These should be added before you add anything else.
 
Make a habit of creating these as your initial commit.
 


## Excercise 3, branching

* Create a new branch using Git in Visual Studio
* To start using the new branch you need to check it out
* Do change to for example README file or any other file
* Check Status
* Commit your changes
 
## Excercise 4, merge
* Create a new branch
* In the main branch Changed README file content and commit changes
* Checkout the previously created branch 
* Use Visual Studio "Git" to merge main changes to the checked out branch
 
* If there are conflicts during merge, those need to be resolved.
 
## Excercise 5, pull requests
* Do a code change in  Visual Studio
* Commit your changes to a new branch with the name of your choice and push those to remote
* Create a Pull Request with a title and description in Github.com or use Github extension from Visual Studio
* Notice the different tabs and that you can review and comment files changed.
* Merge the PR and remove the branch
 
## Excercise 6, issues
* Go to the Issues tab
* Create a new issue or two
* Attach a picture by dragg and drop or paste
* Assign it to yourself
* Go to the Projects tab and create a project with a name and a decription. Note that you can use templates, select the automated Kanban template
* See the cards in the To do column, read them and remove them.
* Add your issues to the To do column
* Note that you can change automation at the bottom of each column
* Add a new column or two
 
## Excercise 7, wikis
* Go to the wiki tab and create the first page
* Enter some text and try out the different markdown text features
* Try adding a link and and image
 
[More about Mark Down](https://guides.github.com/features/mastering-markdown/)
 
 
 

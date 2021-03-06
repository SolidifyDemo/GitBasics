# Git basics


## Excercise 1, creating a repo

* Create a remote repository **on your own GitHub account**, named **GitBasics**. You can make it public or private.
* Initialize it with a readme.md file. The readme file should be your kind of table of content.
* Use this repo to for the labs
* Decide a place on your PC, **a base  folder**, below this all your repositories should be placed. On my machine, I have a "D:\repos".   

It is wise to keep this base path short.  (The default for VS is to place this under your own user folder, down under Documents and so on, that will in many cases lead to path problems)

* Clone this repository to your local machine under the selected folder.  That way it is easier to work on with your local editor.  


## Excercise 2, add and commit your code

* use dotnet to create a small code sample, standing in your cloned folder:

```
dotnet new nunit
```

* Run the git status command, and note what files are shown.

```
git status
```

* Go to [gitignore.io](https://gitignore.io) and create a gitignore for your language of choice  (e.g. *csharp* for dotnet). For non-dev, choose *csharp* too. A course this can be done when you create the repo in GitHub as well.
* Add that to a file named **.gitignore**  (note the **dot** in front)
* Run the git status command again, and note again what files are shown.
* Stage and commit the code/files you have. 
```
git add *
git commit -m "My first commit"
git push
```

### Note

All repos you create should always have the following files

*  readme.md
*  .gitignore

These should be added before you add anything else.

Make a habit of creating these as your initial commit.

## Excercise 3, branching

* Create a new branch
* To start using the new branch you need to check it out
* Do change to for example README file or any other file
* Check Status
* Commit your changes

```
git branch name-of-branch
git checkout newly-create-branch-name

git add .
git status
git commit -m "Updated Readme and commiting to new branch"
```

* Now there is a local branch and local commit which has not been pushed to the remote because the new branch has no upstream branch yet.


* to get help for the '__branch__' command:
```
git branch -h
```

## Excercise 4, remotes

* To find what 'remotes' are set up for your current repo
```
git remote
```

* Or see the remote name with the url 
```
git remote -v
```

* Lets see how we can add new remotes
* Add new remote to the with the same url
* Check remotes 
* As we dont need duplicate remotes we can remove the newly creatd one
* Check remotes that only the origin exists

```
git remote add gitbasics 'url-to-git-repo'
git remote -v
git remote remove gitbasics
git remote -v
```

* In the previous excerise we did some changes and commited those but never pushed to the remote
* To do that lets checkout the branch that was created in previous excerise
* Push previously created commit to remote using '-u' or '--set-upstream'

```
git checkout 'previously-created-branch-name'
git push origin 'previously-created-branch-name'
```

Notes:
It is good practise to use '__-u__' or '__--set-upstream__' in the command when first time pushing a local branch to remote as it sets associations to the remote:
```
git push -u origin branch-name
```

## Excercise 5, merge

* From previous excerise we have two branches and now we can merge them

* Checkout '__main__' branch
* Pull latest changes
* Merge new branch to '__main__'

```
git checkout main
git pull origin
git merge 'previously-created-branch-name'
```

* If there are conflicts during merge, those need to be resolved.

## Excercise 6, pull requests
* Do a code change in code or mark down, you can do that from commandline, Visual Studio or directly from GitHub.com
* Commit your changes to a new branch with the name of your choice and push those to remote
* Create a Pull Request with a title and description in Github.com
* Notice the different tabs and that you can review and comment files changed.
* Merge the PR and remove the branch

## Excercise 7, issues
* Go to the Issues tab
* Create a new issue or two
* Attach a picture by dragg and drop or paste
* Assign it to yourself
* Go to the Projects tab and create a project with a name and a decription. Note that you can use templates, select the automated Kanban template
* See the cards in the To do column, read them and remove them.
* Add your issues to the To do column
* Note that you can change automation at the bottom of each column
* Add a new column or two

## Excercise 8, wikis
* Go to the wiki tab and create the first page
* Enter some text and try out the different markdown text features
* Try adding a link and and image

[More about Mark Down](https://guides.github.com/features/mastering-markdown/)




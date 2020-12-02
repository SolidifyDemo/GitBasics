# Git basics


## Excecise 1, creating a repo

* Create a remote repository **on your own GitHub account**, named **GitBasics**. 
* Initialize it with a readme.md file. The readme file should be your kind of table of content.
* Use this repo to for the labs
* Decide a place on your PC, **a base  folder**, below this all your repositories should be placed. On my machine, I have a "D:\repos".   

It is wise to keep this base path short.  (The default for VS is to place this under your own user folder, down under Documents and so on, that will in many cases lead to path problems)

* Clone this repository to your local machine under the selected folder.  That way it is easier to work on with your local editor.  


## Excecise 2

* use dotnet to create a small code sample:

```
dotnet new nunit
```

* Run the git status command, and note what files are shown.

```
git status
```

* Go to [gitignore.io](https://gitignore.io) and create a gitignore for your language of choice  (e.g. *csharp* for dotnet). For non-dev, choose *csharp* too. 
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





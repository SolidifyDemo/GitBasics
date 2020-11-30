# Git basics


**Excecise 1**

Create a remote repository **on your own GitHub account**, named **GitBasics**. 

Initialize it with a readme.md file.  

The readme file should be your kind of table of content.

Use this repo to for the labs.


Decide a place on your PC, **a base  folder**, below this all your repositories should be placed.

On my machine, I have a "D:\repos".   

It is wise to keep this base path short.  (The default for VS is to place this under your own user folder, down under Documents and so on, that will in many cases lead to path problems)

Clone this repository to your local machine under the selected folder.  That way it is easier to work on with your local editor.  

**Excecise 2   Team work**   

Create a Github organisation for your team.  

*Could be named SEB-Team-A and so on*

Add your team members to the organisation.

Create a Notes repository here, and all team members should clone this repository down.  

**Excecise 3**

Ensure you have dotnet core , and the .net core 3.1 SDK installed.

Just write  (you can do this anywhere, it is just a check):

```
dotnet
dotnet --list-sdks
```

Check that you have 3.1 in that list.

If not [install .net core 3.1 SDK](https://dotnet.microsoft.com/download).

Create a new local repo,  name it 'TaskSystem':

```
md taskSystem
cd TaskSystem
git init
```

Note:  Make sure you don't create this below another git repo, always start from the basepath.

#### Developer/.Net

use dotnet to create a small code sample:

```
dotnet new nunit
```

#### All

Run the git status command, and note what files are shown.

Go to [gitignore.io](https://gitignore.io) and create a gitignore for your language of choice  (e.g. *csharp* for dotnet). For non-dev, choose *csharp* too. 

Add that to a file named **.gitignore**  (note the **dot** in front)

Run the git status command again, and note again what files are shown.

Explain in your own Notes document what the 'git status' command shows, and what is possibly the effect and purpose of the .gitignore file.

Are you sure your untracked files are what you really want inside your repo ?

What folders and files are not included ?

When sure:  Stage and commit the code/files you have.  


**Excecise 4**

On your own Github account, create a repo, but don't initialize it !!

Add a remote connection from your own local repo (in the TaskSystem folder) to this new remote repo.

Push the local repo to the remote.

Note down what the different parts of these two commands mean.


#### All

Push the repo.




### Note

All repos you create should always have the following files

*  readme.md
*  .gitignore

These should be added before you add anything else.

Make a habit of creating these as your initial commit.


### Extra questions  (given time)

* What is the originator source for .gitignore ?   Give the location.

* How often is gitignore changed ?

* Does it matter if you use a built-in method for getting gitignore?   E.g. Visual Studio when you create a repo from that, or adding one by GitHub.  Try one of these and verify for yourselves

* What is really gitignore.io ?



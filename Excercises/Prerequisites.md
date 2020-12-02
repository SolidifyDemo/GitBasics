## Prerequisites

### Check git on command line

You should have git itself installed, and available on command line.

If not [Install Git](https://git-scm.com/downloads)

The Git documentation can be found here:  https://git-scm.com/docs


Open a command prompt, and run:
```
git --version
```
 You should see version 2.28 or higher for Windows, 2.23 or higher for Mac.
 If not, [download it](https://git-scm.com/downloads)

First check your configuration

```
git config user.name
git config user.email
```


If nothing, then configure it with

```
git config --global user.name "Your name"
git config --global user.email "Your email"
```

### Choose an Editor

Choose an editor, preferably one that understands git.

E.g:

* Visual Studio Visual (Windows) (.net * languages)
* Studio Code  (Windows, Mac, Linux) (Any language) 
* Eclipse (Window, Mac, Linux)  (Java ++)

Link for downloading [VSCode](https://code.visualstudio.com/download) 
Install for linux, see https://code.visualstudio.com/docs/setup/linux 


### DotNet
Ensure you have dotnet core , and the .net core 3.1 SDK installed.

Just write  (you can do this anywhere, it is just a check):

```
dotnet
dotnet --list-sdks
```

Check that you have 3.1 in that list.

If not [install .net core 3.1 SDK](https://dotnet.microsoft.com/download).

## Establish a remote

We're using [GitHub](https://github.com) as remote storage.

You need an account on Github.  

If you don't have an account, create a new one.  You have both a Github account identifier and Name.  Imho both should be readable, and not a 'funny' name :-)

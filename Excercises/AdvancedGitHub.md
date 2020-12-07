# Create Branch policies

* Go to Github.com
* Navigate to your repository
* Go to settings tab and click on branches.
* Create a new branch protection
* Add the policiies you think should be applied


# GitHub Actions

* Creat a simple dotnet core application

```
dotnet new webapp
```
* Push your changes in you repository
* Go to Actions Tab
* Generate a workflow based on the dotnet core action
* Commit your changes and see what the action does


# Migration from subversion
* Install subversion if needed: https://www.visualsvn.com/downloads/
* Install Git-filter repo: https://github.com/newren/git-filter-repo
  * Pyton is a prerequisite

* Run analyis
```
git filter-repo --analyze
```

* Clean up (in this case packages folder)
```
git filter-repo --path "Main/packages/" --invert-paths
```
* Run analysis again
```
git filter-repo --analyze
```
 
* If needed replace/remove secrets

* Create repo in GitHub Commit and push
```
git remote add origin https://github.com/SolidifyDemo/SvnDemo1.git
git branch -M main
git push -u origin main
```
Links: https://training.github.com/downloads/subversion-migration/

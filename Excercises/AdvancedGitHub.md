# GitHub Actions

# Migration from subversion
* Install subversion if needed: https://www.visualsvn.com/downloads/
* Install Git-filter repo: https://github.com/newren/git-filter-repo
  * Pyton is a prerequisite

* Run analyis
```
git filter-repo --analyze
```

* Clean up
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

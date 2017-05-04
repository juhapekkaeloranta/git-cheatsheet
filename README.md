# git-cheatsheet
List of useful git commands

* Add remote
```
git remote add origin https://github.com/user/repo.git
git remote -v
```

* Checkout remote branch
```
git fetch remotename
git checkout -b newlocalbranchname remotename/remotebranchname
```

* Update .gitignore

```
nano .gitignore //do your edits
git rm --cached -r .
git add .
git commit -am "Remove ignored files"
```

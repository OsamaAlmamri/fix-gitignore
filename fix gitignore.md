Untrack files which are already added in gitignore file
======
1. Commit all your changes

2. Remove everything from the repository cache. Go to your repo directory and run this command.
```
git rm -r --cached .
```

It will only clear the cache. Your files and git history will stay.

3. Re add everything
```
git add .
```

4. Commit the fix
```
git commit -m 'fix .gitignore'
```

Sit back and relax. It'd done.
![](https://media.giphy.com/media/igDIvcIMMGIne/giphy.gif)

### Written Instructions to Connect to This Repository:

1. FORK this repository, creating a copy on your own GitHub account

2. Then clone your fork down to your local computer
```
git clone https://github.com/[yourusername]/NTL-DS-080723.git
```

3. Add the `/flatiron-school/` version as the `upstream` (to pull future changes)
```
git remote add upstream https://github.com/flatiron-school/NTL-DS-080723.git
```

4. You can make changes to the notebooks now! Remember to push your changes to your forked version of the repo (to put your local changes up online):
```
git add [filename]
git commit -m 'message here'
git push
```

### Whenever you want to get updated notes:

5. Grab the changes from the upstream repo
```
git fetch upstream
```

6. Merge new changes onto your local repo
```
git merge upstream/main -m "meaningful message about what you're updating"
```

7. Push these changes from your local repo on your machine, to your GitHub repo in the cloud.
```
git push origin main
```
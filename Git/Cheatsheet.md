# Git Cheatsheet
### Remote
```
git remote -v
```

### Branching
```
git branch
git checkout -b new_branch
git checkout branch_name
```

### Merge Conflicts

### Tagging
Used for versioning
```
git tag v0.3.8
git tag v0.3.8 44a2a4a2bf8b85214551ce93227d4af7981e8eca
git tag --list
git push --tags
git push origin v0.3.8
```

### Stashing
You can stash your changes as a WIP and come back to them later. Branch goes back to being completely clean.
```
git stash
git stash apply 0
```

### Rebasing
Because nobody cares about all your commits. Although, makes sure that you keep the important commits.
```
git rebase -i HEAD~3
git rebase -i master
git push --force
```

### Log
Shows you all your commits.
```
git log
```

### Diff
```
git diff
```

### Other
* [Git presentation](https://ngh5026.github.io/git/#/)
* [Flight rules](https://github.com/k88hudson/git-flight-rules/blob/master/README.md)
* [SourceTree](https://www.sourcetreeapp.com/) is a good GUI for git
* Usage patterns: [Git-Flow](https://ngh5026.github.io/git/#/3/26)
* [gh-pages x reveal.js](http://aln787.github.io/revealGhPages/#/)
* [GH Wiki]()
* [GH Issues]()

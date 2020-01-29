---
title: git
date: 2020-01-29 13:59:52
tags:
---

### Git TAG
1. create tag
git tag <name>
2. delete tag
git tag -d <name>
3. push tag
1) push your tags
git push origin --tags
2) if you just want to push a single tag:
git push origin <tag name>

### git branch
1. create branch
git checkout -b <name>
2. delete branch
git delete -D <name>
3. delete remote branch
git push origin --delete <name>

### apply .gitignore on an existing repository
This removes everything from the index
 git rm -r --cached .

 Add them again
 git add .

 and do the commit,
 git commit -m ".gitignore is now working"

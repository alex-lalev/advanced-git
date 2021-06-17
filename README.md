### advanced-git
*Personal repository to test some handy & more advanced Git techniques.*

Global Git User Configuration Commands:
```
git config --global user.name "#"
git config --global user.email "#"
```
> Remove --global for local project specific config

Getting Detailed or One-line Git log history output:
```
git log --oneline
git log --patch
```

The three options of Git Reset:
```
git reset --soft (moving the changes to your staging area)
git reset --mixed $commitId (moving the changes to your working directory)
git reset --hard (moving the changes to your recycle bin)
```

Tagging and Releases:
```
git tag $tag_name $branch_name (lightweight)
git tag -a v0.1 -m "V0.1 Release" $commit_id (annotated)
git push --tags
``` 
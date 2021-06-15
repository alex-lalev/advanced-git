# advanced-git
Personal repository to test some handy everyday and more advanced Git techniques.

- Global Git User Configuration Commands:
git config --global user.name "#"
git config --global user.email "#"

(Remove --global for local project specific config)

- Getting Detailed or One line Git log history output:
git log --oneline
git log --patch

- The three options of Git Reset:
 $ git reset --soft (moving the changes to your staging area)
 $ git reset --mixed $commitId (moving the changes to your working directory)
 $ git reset --hard (moving the changes to your recycle bin)

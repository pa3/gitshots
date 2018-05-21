## What's that?

Git post-commit hook to make movies like [this one](https://youtu.be/qCDfesQhHQ4)

## Prerequisite

Node.js should be installed

## Installing

```
git clone https://github.com/pa3/gitshots.git ~/.git-hooks
git config --global core.hooksPath ~/.git-hooks
mkdir -p ~/.git-shots
sudo apt-get install fswebcam
sudo chmod a+x ~/.git-hooks/post-commit
```

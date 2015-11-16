# git demo : set up

## Set up user information

```
git config --global user.name "Yudong.Fang"
git config --global user.email ydfang@hotmail.com
```

## Set up basic tools

```
git config --global core.editor '"C:\Program Files\Sublime Text 3\sublime_text.exe" -w'
git config --global merge.tool kdiff3
git config --global mergetool.kdiff3.cmd '"C:\\Program Files\\KDiff3\\kdiff3" $BASE $LOCAL $REMOTE -o $MERGED'
```
- *Note*: Using '-w' option, so that after you write comments, you don't need to close sublime, jsut close the tab.
- Kdiff3 is a good tools for 3-way merge. ANother good tools: meld, opendiff, emerge.

## check setting
```shell
git help config
git config --list
```

# git demo : kindergarten
## Git Repository
```
git init
```

## Now add file to the folder, change that file using any code editor (such as sublime)
- Add file in OS (gitTriningScripts.md)
- Chang files OS

## add to the stage
- Add to stage
```
git add gitTriningScripts.md
```

- Commit
```
git commit –m “version 1”
```

- check status
```
git status
```

# Demo tools setting
## git
- install git and git gutter

*Note*: After install git gutter, yo can find int his file, it has plus or other sign inthe most left area.


## Markdown tools setting
- Install OmniMarkupPreviewer

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
git config --global diff.tool kdiff3
git config --global difftool.kdiff3.cmd '"C:\\Program Files\\KDiff3\\kdiff3" $BASE $LOCAL'
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

# git demo : Elementary
## Diff
1. generate a html file which not in the vesion control managemed. (ex, click right button and chose export html)
2. run command `git status` and check the status
    - The new create html is showing not in the control
    - The original showing eighter changed or commit
3 run copmmand `git status --staged` to check again
4. run command `git diff HEAD gitTriningScripts.md`
5. Set gui for git difftool
    - double check the git difftool has been set
    - run command 'git difftool gitTriningScripts.md -y'
    - - `-y` will save your time



# Demo tools setting
## git
- install git and git gutter

*Note*: After install git gutter, yo can find int his file, it has plus or other sign inthe most left area.


## Markdown tools setting
- Install OmniMarkupPreviewer

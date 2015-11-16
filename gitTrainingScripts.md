# set up

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

## check setting
```shell
git help config
git config --list
```

# git demo : kindergarten

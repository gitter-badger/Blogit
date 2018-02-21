## Git global setup

```
git config --global user.name "LinArcX"
git config --global user.email "linarcx@gmail.com"
```

### Set vim as default editor

```
git config --global core.editor vim
or
sudo git config --system core.editor vim
```


### Pull current project on github

```
git branch --set-upstream-to=origin/master master
or 
git pull origin master
```

### Existing folder:

```
cd existing_folder
git init
git remote add origin https://gitlab.com/LinArcX/Tvdoon.git
git add .
git commit -m "Initial commit"
git push -u origin master
```


### Existing Git repository

```
cd existing_repo
git remote rename origin old-origin
git remote add origin https://gitlab.com/LinArcX/Tvdoon.git
git push -u origin --all
git push -u origin --tags
```

### Create a new repository

```
git clone https://gitlab.com/LinArcX/Tvdoon.git
cd Tvdoon
touch README.md
git add README.md
git commit -m "add README"
git push -u origin master
```


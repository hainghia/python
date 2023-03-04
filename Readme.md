<p align="center">
<a href="/" target="_blank">
<img src="logo.svg" width="400" alt="Logo">
</a></p>

___

### Git Remote repository

```shell
git remote -v

git remote add origin git@github.com:hainghia/python.git
git remote add gitlab git@gitlab.com:hainghia/python.git
git remote add bitbucket git@bitbucket.org:hainghia/python.git

git checkout -b develop gitlab/develop

git pull origin main

git push origin main
git push gitlab main
git push bitbucket main

git add .; git commit -asm "Initial commit";git push origin main; git push gitlab main; git push bitbucket main
```

## Install python and Pip (PowerShell administrator)
```shell
choco install python
python -m pip install --upgrade pip
```

## Install lib (PowerShell administrator)
```shell
pip install requests
pip install beautifulsoup4
```

## Run program
```shell
python app.py
```
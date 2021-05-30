# Git-command-line-learning


### If we want to colne remote repository and commit the changes or add new files that made locally 

``` 
git config --global user.name "John Doe"
git config --global user.email johndoe@example.com

git clone  -> to copy repository 

git status  -> to check whether repository has been modified or not

git add  -> to put file in staging area (to make file commitable when new file is locally created) 

git commit -a -m "message" -> to commit all the changes in the repository

git remote

git log 

git push origin master
```


### If we want local repository to go on github 

```
git init -> to convert any repository into git repository

git add filename or foldername -> to put file in stagin area (to make file commitable) 

#now we have to cerate empty(without readme.md file) repository on github and copy url of that repository
git remote add origin copied url -> url of new github repository

git commit -a -m

git push origin master

git pull origin master -> If we have done updatation in github repository then reflect those changes into local repository
```


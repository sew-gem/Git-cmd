# Terms

- Repository (Repo)
    ex: name of project = Repo >> portfolio
- branch
- conflic 
- local >> data on your laptop
- remote >> data on server like github   
# ~~~
- git config -g user.name {user name} // -g short for -global
- git config -g user.email {user email}



# Comment  (ctrl + j)  
- clear >> clear terminal
- git init >> turn project into git repo
- git status >> status & all file in project
- git add + name file >> save file
- git add . >> save all file
- git reset >> delete all file from git
- git commit -m'initial commit' >> note to mark time scale of project
- git log >>  show time file's saved
- git log --oneline >> the same with git log but it's shorten
- git checkout {id commit} >> return to commit before
- git checkout  {branch name} >> return to present commit
- git branch >> show default / present branch
- git checkout -b {branch name} >> create new branch
- git merge {branch name} >> merge all branch 
- git branch -d {branch name} >> delete branch
- git push {link repo on github  + branch name} >> push code from local to github
// or we can use alies by assign link repo into a name
>> syntax: git remote add {name for alies + link repo}
// after that when want to up code to github we gonna type:
>>git push {name alies + branch name}


// we done upload code into github 
// the code be fixed & we wanna save changes to github
    >> git add .
    >> git commit 'new remote push'
    >> git push {link repo+ name branch}


// gonna use code from remote on local?
>> open terminal 
>> cd {link of folder you wanna save code in}
>> git clone {link repo from github}
 >> cd {name of file was showed below}
>> code .   => open file code with vsCode



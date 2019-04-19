### First time use git in local file
    git init <br>             //Create .git directory
    git add .                 //Add all existing file in the index 
    git commit -m "comment"   //Add the first comment
    git status <br>           //Check the status
### Clone the repository from github  
    git clone "URL.git"  
### Work with online repository  
    git remote -v                   //Check the repository  
    git remote add origin “URL”     //Add the new repository to local file   
    git pull origin master          //pull the file from master  
    git push -u origin master       //upload the file after add  

### Remote control
    git remote add origin URL <br>     
    git remote rm "name" <br> 
    git remote rename "origin" "new" <br>  
    git pull origin master  
    git push -u origin master <br> 

### Branch
    git branch branchName
    git checkout branchName
    (checkout to the master)
    git merge branchName

    git branch -d <branch> //Remove Branch

### Reset commit
    git reset --soft HEAD^  #uncommit and remain the change
    git reset --hard HEAD^  #uncommit and remove the change

### log
    git log --oneline
    git rebase 

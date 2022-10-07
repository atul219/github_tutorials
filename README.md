#### Git Tutorials
################################################################

### Steps
#### 1. create any repository
#### 2. create any file 
#### 3. initialize git 
        git init
#### 4 set user.name and user.email to track your name and email
        git config --global user.name "your name"
        git config --global user.email "your email"
#### 5 check status
        git status
#### 6 add files
        git add . 
        hint -> (. for all files)
        git add file_name 
        hint -> (file_name is the file name of single file)
#### 7 send all change files to staging environment
        git commit -m "commit message"
#### 8 check branch it should same branch
        git branch
#### 9 if not then change branch to main
        git branch -M main
#### 10 add remote origin 
        git remote add origin link 
        hint -> (link of your repository.git)
#### 11 push the code to main branch
        git push -u origin main

#### create different branch
        git branch developer1

#### to switch to developer branch
        git checkout developer1

#### to merge branches
        git merge developer1 
        this should be done from main branch.

#### to delete branches
        git branch -d developer1


  ### github  
    for clone -> git clone url
    for untrack file which is not push in github -> git status
    for track file->git add file name
    for change into github ->git commit -m "message"
    finally let github this arte the changes ->git push
    for cheack if file modified ->git status
    update the folder ->git pull

   ##### git project -> git init 
   ##### for hidden file in a directory -> ls -a
   ##### which file are gooing to git -> git status
   ##### need to added them into a commit stage -> git add -A (if we change file than we can use it)
   ##### make a commit ->  git commit -m "first commit " => last space is important
  ##### use github provides link + git push (for second push just use -> git push)
  
  
  
  
  ...............................
  
  Remote -> local :
  1. git diff -> show difference between work directory and staging area.
  2. git diff HEAD ->difference between local repository and working directory.



#### cheacked is git install correctly:
      1.go to comand promt
      2. type git --version
      
 ##### Git Bash:
    1. git init
    2. git status -> show all untrac file
    3. Stageg :
        * git add "file name"
        * for all file:
            1. git add --all /  git add .
     4. commit:
          1.git commit 
          2. press i button
          3. type  commit msg above.
          4. press esc button
          5. type :x below
         shortcart way:
            1. git commit -m "message"
      5. show all commit:
            1. git log
           * showing one line commit:
              1. git log --oneline
              
       6. for go to a stage :
            1. git checkout serial number
            
        7. for go to master stage:
             1. git checkout master
           
         8. for compare two commit:
             1. git log --online -> find the commit serial number
             2. git diff serialnumber serialnumber
             
          9. delete from git:
               1.git rm filename
             
   
 ##### Select username globally:
         1. git config --global user.name "abir10t"
         2. git config --global user.email "aabir.10t@gmail.com"
##### Select a particular username :
         1. git config user.name "abir10t"
         2. git config user.email "aabir.10t@gmail.com"
         
##### Cheacked which user name is saved in git
        1. git config --list
        
##### push in server :
        1. git remote add origin https://github.com/abir10t/flutter-_-ui_visiting_card.git
        2. git push -u origin master

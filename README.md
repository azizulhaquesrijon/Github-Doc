# Github-Doc

<h1>Github Documentation :</h1>
1. <b>Download and install git</b>

2. <b>Version Check</b> 

 ```PHP 
 git --version
 ```
 
3. <b>Check Configuration</b> 

 ```PHP 
 git config
 ```
 
 
4. <b>SET USER IDENTITY</b>

To set your account's default identity globally run below commands

 ```PHP 
 git config --global user.email "you@example.com"
 ```

 ```PHP 
 git config --global user.name "Your Name"
 ```
 
 ```PHP 
 git config --global user.password "your password"
 ```

To set the identity only in current repository , remove --global and run below commands in your Project/Repo root directory

 ```PHP 
 git config user.email "you@example.com"
 ```

 ```PHP 
 git config user.name "Your Name"
 ```
 
  ```PHP 
  git config user.password "your password"
 ```
 

5. <b>CREATE NEW BRANCH AND PUSH</b>


 ```PHP 
 git init
 ```

 ```PHP 
 git checkout -b srijon_new
 ```
 
  ```PHP 
  git remote add origin https://github.com/Crafty-Urban/Baazrr.git
 ```
 
  ```PHP 
 git add .
 ```
 
  ```PHP 
 git commit -m "Added"  
 ```
 
   ```PHP 
 git push -u origin srijon_new  
 ```


5. <b>WORK IN A BRANCH AND PUSH FROM ANOTHER(2 branch in local but 1 in github)</b>

 a. Check branch -
 
 ```PHP 
 git branch  
 ```

 b. Create new branch named srijon_new-

 ```PHP 
 git checkout -b srijon_new 
 ```
 
  b. Change branch (srijon_new changed branch name)-

 ```PHP 
 git checkout srijon_new 
 ```
 
 c. Merge from srijon_current to srijon_new branch-
  
   
  ```PHP 
 git add .
 ```
 
  ```PHP 
 git commit
 ```
 
  ```PHP 
 git commit -m "Added"  
 ```
 
   ```PHP 
 git checkout srijon_new    
 ```

  ```PHP 
  git merge srijon_current    
 ```
 
   ```PHP 
 git push -u origin srijon_new    
 ```
  
   ```PHP 
 git checkout srijon_current     
 ```




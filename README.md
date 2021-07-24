Steps to create a local git repository :-
#### 1 Check version git --version
#### 2 git init (this will initialise the local repositry  ) also it will create a database for stoing history of changes .git
#### 3 git add <file name> | .
#### 4 git commit -m "commit message "

---> Local Repository Created 
basic command to create a repository
echo "# MyStaticWebsite" >> README.md  [Ok]
git init   [Ok]
git add README.md [added all the file ] git add .
git commit -m "first commit" [Ok]
git branch -M main  // telling to create a main branch 
git remote add origin https://github.com/dheeraj-thedev/MyStaticWebsite.git
git push -u origin main
to deploy into netlify 

open grocery-bud-project into vs code 
open it's terminal 
git remote -v -> to check is there any other git repo is already present or not 
rm -rf .git   ->if already exist then remove it 
git init      -> otherwise  
git status 
git add .
git status
git commit -m "initial commit"
git remote add origin https://github.com/sgupt187/temp-grocery-bud.git
git branch -M main
git push -u origin main

after running all above steps your grocery-bud-project will be pushed into github 

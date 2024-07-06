# lab02 in Git
## Members
1. Meral
2. Yassmine
3. Hania
4. Ahmed Hany
5. Marwan
6. Mohamed Fawzy
## How to do merge form different branches to main

1. create branch
   ```
   git branch branchName
   ```
2. switch to branch
  ```
  git switch branchName
  ```
3. add your own modifiacrion to your branch then apply changes to your remote branch
```
git add .
git commit -m "your commit message"
git push --set-upstream origin branchName
```
4. switch to main
```
    git switch main
```
6. then merge your branch to main
```
git merge branchNmae main
git push
```
 


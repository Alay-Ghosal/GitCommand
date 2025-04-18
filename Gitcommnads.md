//BRANCH//
git branch(to check branch)
git branch -M <name> (to rename Branch)
git checkout <-branch name-> (to navigate to the another branch <>)
git chekout -b <new branch name> (to create a new branch)\
git branch -d <branch name> (to delete a branch)
//MERGE//
 git diff  <branch name>
  git mergre <branch name>
//PUll command//
git pull origin main
//UnDo changes//
git reset <file name> (to undo changes that just added and not commited
 git reset HEAD~1(to undo one commit)
 
//git reset <commit hash>(to undo any nunmber of commit each commit has it's own hash number )
  by using command [git log] we get record of all commit along with their hash eg->
[commit 49192550bc23201b23608387c2bcb6bb4e4dd966 (feature1)----->hash
Author: Alay Ghosal <alayghosal009@gmail.com>
Date:   Fri Apr 18 15:07:17 2025 +0530]
git reset 49192550bc23201b23608387c2bcb6bb4e4dd966 //
git reset --hard <commit hash>

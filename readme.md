

//Day2
<!-- Revert the changes -->
git reset --hard <hashCode>
git revert <hashcode>
<!-- git add . -->
<!-- git commit -m "next" -->

<!-- How to create a branch -->
git checkout -b <branch-name>


<!-- Delete a branch -->
git branch -d branch-name
git branch -D branch-name (unmerged also)

<!-- ESC :wq --> helpful(Escape the writing mode, save and quit)
<!-- i: insert mode -->


<!-- How to change the name of branch -->
git branch -m <branch_name>

<!-- Git stash -->
allows you to temporarily save your uncommitted changes (both staged and unstaged) in a "stash" and revert your working directory back to the last commit.

<!-- git stash -->
<!-- git stash list -->
<!-- git stash apply -->
<!-- git stash apply stash@{1} -->
<!-- git stash pop -->
<!-- git stash clear -->




//Day3
<!-- Working with Github -->
git remote add origin https://github.com/Satyam8409/Git_Learning.git
git branch -M main
git push -u origin main  (give this command when u r pushing for 1st time)
git push                 (when pushing for next time)

<!-- git pull origin main -->
<!-- git pull --rebase origin main-->

<!-- git branch -r -->

<!-- git push origin --delete feature -->






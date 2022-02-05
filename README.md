# Main repository created for Katas exercises
## katas-1 Basic Commits 
Done with the basic of command like -

git add</br>git commit
git commit -m "My commit message"</br>
git log </br>
git log -n 5</br>
git log --oneline</br>
git log --oneline --graph</br>
Also pushed some of commit to github.</br>
## Katas-2 basic-staging 
Practice command like git diff , git diff --staged on local repo .
</br>
also checked function of git restore , and , git checkout <file> command in local repo.</br>
## Katas-3 basic-branching 
Created new branch in local repo and pushed them to github also.</br>
Used command like git switch </br>
git switch -c is new command which works same as git checkout -b .</br>
Also used git diff <branch1> <branch2> to check difference
## Katas -4 FF merge
  Used below command to make new branch and made commit and pushed to remote  repo </br>
git branch <branch-name></br>
git branch -d <branch-name></br>
git switch</br>
git branch -v</br>
git add </br>
git merge <branch></br>
Fast forward doesnot create any new commit only Head starts pointing to both branch.</br> 

## Katas -5 3-way-merge
Understand the diff between 3-way merge and FF with the help of visualizer also attaching photo.</br>
3 way merge gives new commit with the merge message.</br>
attaching pic from gitschool visualizer https://git-school.github.io/visualizing-git </br>
![Screenshot (69)](https://user-images.githubusercontent.com/79358859/152655964-f5f22905-6b63-4e52-8973-76bc4ec0c3b9.png)

## Katas-6 Merge conflict
gone through the conflict occured while merging branch to master, fixed that conflict with editor and following instruction according to the status.
## Katas-7 Merge-mergesort
faced merged conflict and solved by editing actual code.</br>
taking help of git status at each step and resloved .or we can also use git mergetool --tool .........
## Katas-8 rebase-branch 
git checkout <branch-name></br>
git rebase <branch-name></br>
git log --oneline --graph --all</br>
git merge <branch-name></br>
By using above command practiced this using rebase its a alternate way of doing merge .but the problem is it doesnot store history so its not good to use rebase if you donot know about the branch and history of project.</br>
here is dry run of that command-</br>
![Screenshot (71)](https://user-images.githubusercontent.com/79358859/152656085-dbe14910-e730-4200-b677-ec3cc9137c0d.png)


## Katas-9 Basic revert
Practiced revert command on local repo .Used to revert any commit made earlier with creating a new commit after reverting. Its is much safer than reset command.  </br>
command I have used.</br>
git revert <ref></br>
git log --decorate --oneline</br>
git show <ref></br>
We can also use git revert Head~ to any of the commit which we made earlier. also tried out on local repo.

## Katas-10 Reset
Its slight dangerous command to use and powerful used to unstage history and go back to old commit.</br>
there are 3 types soft mixed hard the default reset type is mixed .</br>
checked effect of all these on local repo history.</br>
we can also use stash and other to do different things.</br>
command - git reset <commit>
## Katas-11 Basic cleaning
  Used when there and object files , generated files , and compiled files.</br>
git clean -n</br>
git clean -n -d</br>
git clean -f -d</br> these are some commands which is used.
## Katas-12 amend
Amend command used only when you have not pushed your commit to remote repo. else it will create conflict and create confusion having different commit messages.
If we simply want to modify your last commit message**,git commit --amend** is used and we will get new and improved commit.</br>
**we can't amend our last commit if we’ve already pushed it.**
## Katas-13 reorder-the-history 
git rebase -i <after-this-commit></br>
git log --oneline --graph</br>
git reflog </br>
using above command git rebase -i we can reorder our commit history in order we want **git rebase -i HEAD~3** using this command every commit in the range HEAD~3..HEAD with a changed message and all of its descendants will be rewritten. if something is pushed to server we can't commit this again.</br>
pick , edit , reword all command is used while reordering .

## Katas -14 Squashing
if we want to squash some of the commit into a new one and making good log show we use this command.</br>
![wzol8](https://user-images.githubusercontent.com/79358859/152656946-3f3a73bc-c051-4503-8afe-e77d906ba14e.gif)

## Katas -15 Advance Interactive rebase.
in Interactive rebasing we can do multiple thing like squash ,pick,reword,rewriting history all this with using single command git rebase -i or git rebase --interactive
</br>
Tried on local and got understanding of squashing.

## Katas-16  Basic stashing



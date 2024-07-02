# Welcome_github
This is my first git repository
<br>
Author - AMIT KUMAR NAIK
1. GO TO GITHUB.COM
2. Then go to right side cornor top and go to profile
3. after that go to repositories
4. then click new
5. after create click your repository and here is go..
6. if any changes then go to commit changes(right side top corner)
7. make changes then save

8. then go to vs code write git clone (paste the link from git in https )... then vs connect with the git repositories.
9. if any modify ocuurs then we have to first add then commit.
to add git add (new file name/modified file name).
ex -- git add index.html or  git add README.md  
to add multiple files we can use ex -- (git add .)
then (git status) to check the save..
to commit example - (git commit -m"add new paragraph")
Your branch is ahead of 'origin/main' by 2 commits. meaning in git hub that changes not reflect first you have to push to the git hub 
to push to github--(git push origin main)
if any changes occurs First have 
1. add
2.commit
3.push

git init /////
(local folder connect with the git )
cd .. for back one step directory
mkdir make new folder 
git init (intialize empty repository)
then go to repository create new repo 
then copy the link and write in vs terminal
git remote add origin <link>
to verify remote  (git remote -v)
to check branch (git branch)
to rename branch (git branch -M main)
next git push origin main or git push -u origin main

to create a new branch --  (git checkout -b branchname )
Switched to branch  -- (git checkout branchname)
delete branch -- (git branch -d branch name )  note:if you are in same branch 1st change the branch
what ever you write in a branch it will not show in another branch (to write anything in a branch select that branch and write )
then add,commit and push(git push origin  branchname)


///// merge branch (by adding features but in different lines )

to know diff -- git diff branchname  /// note: check which branh you are and branch name should be other which you right now..
 After know the differnce if want to merge then
 1. go to git hub and branch select to main //(where you want to merge other )//  then compare and pull request 
 2. then write title and then click create pull request.
 3. due to add features but in different lines so it shows no complicence 
 4. after that click merge pull request ...
 5. then confirm merge..
 6. then in git hub different branches show same code..
 7. but it will not reflect in vs code to the same we have to  --- git branch pull origin main


 ///// merge branch (by adding features but in same lines(resolving merge conflicts) )
1. to this we have to write something in same line vs code..
2. after that (git merge main)
3. it will shows some diff in screen then decide what you keep and then add commit in other branch ..
4. then switch to main and type  (git merge feature1(branch which want to merge in main))
5. then push to main to update in git hub


//// undo
1. only add then undo

(git reset  filename(index.html)) or git reset

2. add and commit
(git reset HEAD~1 )one step back head lets total 4 commits it will go to 3 

3. multiple changes 
(git reset hash example (git log(there is some number which commint you want go back copy that hash)))

4. for appear in vs code
git reset --hard hash


// Fork(it is a rough copy if you want to work in a project of others in this it use to copy to your repository from others)

1. first search or find the project
2. then go to fork option create fork 
3. then make some changes if want to merge the origin then create pull request..
## GIT ##

Autenticate using a Token

Login in your Git account and go to:

MyProfile/Settings/DeveloperSettings/personalAccesToken

generate a new one and copy it.

Later create a new repo from the home page and open a Terminal:

git clone "https://github.com/User/repoName"

touch Readme.md  

git add .

git commit -m "Readme.md"

git push

---

## Commands ##

** git –help comman ** ->see the git instructions of used of the command.

** git log -10 --all --graph --oneline ** —> to see a tree with the last 10 commits of all the branch, to exit press q.

** git branch ramaB ** —> :to create ramaB.

** git branch -d ramaB ** —> delete ramaB.

** git checkout ramaB ** -> move to ramaB.

** git checkout -b ramaB ** —> to create branch b and move to it.

** git merge ramaB -m "important" ** —> merge ramaB into the current branch tree with a comment “important”. (-s https://git-scm.com/docs/merge-strategies)

** git merge –-abort ** -> stop a merge, after a conflict before a commit.

** git branch -a ** ->see remote and local branchs.

** git branch –merge main ** ->see local branches merged with the main branch (delete candidates. git branch –d “branchName”). To delete a branch that is not merged and lost the work done in it writte: git branch –D “branchName”.

** git branch –move malnombre newnombre ** -> change name of a branch.

** git push origin –delete malnombre ** -> delete a branch in the remote repo.

** git reset ** —> remove all the file from the staged state. 

** git reset HEAD ./src/temporal.txt ** -> remove from stage only the file ./src/temporal.txt 

** git checkout --. ** —>  lost the last changes from the tracked files, we remove the file from the modified status.

** git clean -n --. ** —>  show files to delete (no tracked files) if we execute git git clean --force

** git commit -am “coment” ** —> to pass from Modified to Stage Area without have to write “git add .”.

** git stach + git pop ** —> to save without commit, the pass from Modified.

** git fetch - -prune ** -> delete all branches that are actually deleted in the remote repo.

---

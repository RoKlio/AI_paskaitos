# AI Courses

## Git Instructions
* To clone a repository run '$ git clone <link.git>' 
* To stage file/ files run '$ git add <files>'
* To commit staged files, run '$ git commit -m "message"'
* To push commit into remote repo run '$ git push origin <current_branch_name>'
* To create new branch run '$ git checkout -b <branch_name>'
* To rebase your branch first be in your new branch, then update git with '$ git fetch -p'.
Then run '$git rebase origin/master':
    * If there are merge conflicts, solve them, then run '$git add .' and '$ git rebase --continue'
    * If there are no conflicts or they are solved run '$ git push origin HEAD --force with lease'
* To not track files with git, create file '.gitignore'
* To remove cached files, run '$ git rm -rf . --cached'
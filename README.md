# git-tutor
Learning git

VCS - Version Control System

Learn Git actions (commands):
commit

push
git push --set-upstream
git push origin HEAD

pull
merge
branch
rebase
restore
cherry-pick
Clone repo:
$ git clone git@github.com:rafmio/Go.git

rm
All files are created, status needed
$ git status
Your branch is up to date ...
$ git rm <filename>
  Output: rm 'file1'
$ ls
  Output: in outputted list file was deleted
$ git commit -m "commit text"
$ git push
  Output: fatal: The current branch newRMswitch-c has no upstream branch.
  To push the current branch and set the remote as upstream, use
    git push --set-upstream origin newRMswitch-c

$ git -m commit "text of commit"
$ git push --set-upstream origin <branchName>
Success!

Git logs:
$ git log

Sources:
github tips: https://habr.com/ru/company/ruvds/blog/599929/
GODocs: Guide to Cloning Git Repos: https://golangdocs.com/cloning-git-repositories

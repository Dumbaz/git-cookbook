# git-cookbook
All the git CLI I tend to look up too many times

## Branch out, merge the branch back in and delete the branch

1. ###### Create a new Branch with specific branch name
  `git checkout -b branch_name`

2. ###### Merge the branch into the master
  ```
  git checkout master
  git merge branch_name
  ```

3. ###### Delete the branch
  `git branch -d branch_name`

## Configure a HTTP Proxy for git
`git config --global http.proxy $HTTP_PROXY`

## Undo one more more commits ##
http://stackoverflow.com/questions/927358/how-to-undo-last-commits-in-git

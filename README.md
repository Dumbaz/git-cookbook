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

## Show Commit history in CLI ##
`git log`
Last commits in reverse Order

`git log -p`
Differences introduced per commit

`git log --since=2.weeks`
Limit to commits of the last 2 weeks, other codewords are `2017-12-31` `2 years 1 day ago`

`git log --grep string`
Searches commit messages

`git log -S string`
Searches for changes in string in the code

## Show global git settings ##
`git config --list`
```
git config --global user.name "Dorian Lenzner"
git config --global user.email "dorian.lenzner@email.com"
```

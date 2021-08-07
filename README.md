# Test

## Important commands for Git

#### Download - Modify - Upload

- Download changes
  - `git pull`
- Add a new / changed file to a commit (put [.] instead of [file] to add everything)
  - `git add [file]`
- Remove a file
  - `git rm [file]`
- Commit the added files
  - `git commit -m "[message]"`
- Upload the commit(s) to Git
  - `git push`

#### Branches

- Create a new branch
  - `git branch [branch]`
- Change the current branch
  - `git checkout [branch]`
- Merge two branches (example: merge `hotfix` into `development`)
  - `git checkout development`
  - `git merge hotfix`
  - delete no longer needed branch `hotfix`: `git branch -d hotfix`

#### Helpful commands

- Automatically add all tracked files and commit
  - `git commit -am "[message]"`
- Show the current status
  - `git status`
- Reverse modifications to a file
  - `git checkout [file]`
- Download -> look at changes -> merge
  - `git fetch`
  - `git diff`
  - `git pull`

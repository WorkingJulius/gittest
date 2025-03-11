# gittest
# Hola este es un test
git add . = adds all the files changed to the staging area
git add "file.txt" = adds specific file to staging enviroment.
git reset "file.txt" = removes one file from staging
git status = print reposotory status
# Branches
git branch = Shows existing branches
git brach "New Branch Name" = Creates a new branch
git checkout "Branch Name" = Switches to the specified branch
git merge = merges two branches

# Checking status and inspecting commits
git log = shows commits history and their hashes
git show "Commit hash" = shows commit details
git show --name-only "Commit hash" = shows only the name of the files that were modified
git reflog = shows when we moved from one branch to another

# Undo and redo changes
git revert "Hash" =  undo the selected commit
git reset "Hash" = Go back to hash and ignore all the consequent commits
git reset --soft (default) = disregards subsequest commits but keeps all the changes they made
git reset --hard = disregards subsequest commits including changes.

# Pull requests

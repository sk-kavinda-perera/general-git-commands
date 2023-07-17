# GIT COMMANDS

## GIT DOCUMENTATION -https://git-scm.com/docs/git
 
* **git init**  : Initializes a new Git repository in the current directory. ex(git init)
* **git clone**: Creates a copy of a remote repository to your local machine. ex(git clone https://github.com/username/repo.git)
* **git add**: Adds changes in the working directory to the staging area, preparing them  ex(git add file1.txt ||git add .)
* **git status**: Shows the status of the working directory and staging area (changes to be committed). ex(git status)
* **git commit**: Records the changes in the staging area to the local repository, creating a new commit. ex:(git commit -m "Add new feature")
* **git pull**  : Fetches and merges changes from the remote repository to the local repository. ex:(git pull origin main)
* **git branch**  :Lists all branches in the repository.
* **git checkout <branch_name>**  :Switches to the specified branch
*  **git merge <branch_name>**  :Merges changes from the specified branch into the current branch.
*  **git log** : Displays the commit history of the repository
*  **git remote add <remote_name> <remote_url>** : Adds a remote repository.
*  **git remote -v** :  Lists all remote repositories.
*  **git fetch** :Fetches the latest changes from the remote repository without merging.
*  **git reset <commit>** : Discards commits, moving the branch pointer to a previous commit.
*  **git revert <commit>** : Reverts a commit by creating a new commit that undoes the changes.
*  **git rm <file>** :: Removes a file from the working directory and staging area.
*  **git tag <tag_name>** : Creates a lightweight tag for a specific commit.
*  **git branch -d <branch_name>** : Deletes a branch.
*  **git stash** : Temporarily saves changes that are not ready to be committed.
*  **git diff** : Shows the differences between the working directory and the staging area.
*  **git remote remove <remote_name>**:Removes a remote repository.
*  **git branch -a**:Lists all local and remote branches.
*  **git push -u <remote_name> <branch_name>**: Sets up tracking for a branch and pushes it to a remote repository.
*  **git fetch --prune**:Fetches the latest changes from the remote repository and removes any references to remote branches that have been deleted.
*  **git log --graph**: Displays the commit history with a graph showing the branching and merging of commits.
*  **git reset --hard <commit>**:Discards commits and any changes in the working directory, moving the branch pointer to a previous commit.
*  **git rebase <branch_name>** :  Moves or combines a sequence of commits to a new base commit, typically used to incorporate changes from one branch into another.
*  **git cherry-pick <commit>** Applies the changes introduced by a specific commit to the current branch.
*  **git branch -r:** Lists remote branches.
* **git push origin --delete <branch_name>:** Deletes a remote branch.
* **git remote prune origin:** Removes remote tracking branches that have been deleted on the remote repository.
* **git stash list:** Lists all stashed changes.
* **git stash apply:** Applies the most recent stash and keeps it in the stash list.
* **git stash pop:** Applies the most recent stash and removes it from the stash list.
* **git stash drop:** Discards the most recent stash.
* **git cherry-pick --continue:** Continues the cherry-pick operation after resolving conflicts.
* *8git cherry-pick --abort:** Aborts the cherry-pick operation and returns to the original state.
* **git config --global user.name "Your Name":** Sets the name associated with your Git commits.
* **git config --global user.email "your_email@example.com":** Sets the email associated with your Git commits.
* **git remote set-url origin <repository_url>:** Updates the URL of the remote repository.
* **git log --oneline:** Shows a compact commit history with each commit on a single line.
* **git blame <file>:** Displays the commit and author information for each line in a file.
* **git tag -l:** Lists all tags in the repository.
* **git tag -a <tag_name> -m "<tag_message>":** Creates an annotated tag for a specific commit with a message.
* **git push --tags:** Pushes all local tags to the remote repository.
* **git branch -m <new_branch_name>:** Renames the current branch.
* **git reflog:** Shows a log of all operations performed in the repository, including commits, merges, and branch updates.
* **git config --global alias.<alias_name> <command>:** Sets up an alias for a frequently used Git command.
* **git revert --no-commit <commit>:** Reverts a commit but doesn't create a new commit, allowing for further modifications before committing.
* **git clean -n:** Shows a list of untracked files in the working directory that can be safely removed using git clean -f.
* **git fetch --all:** Fetches all branches from the remote repository, including those that you don't have locally.
* **git reset --hard origin/<branch_name>:** Resets the local branch to match the remote branch, discarding any local changes.
* **git log --author="<author_name>":** Displays the commit history filtered by the specified author.
* **git log --grep="<search_pattern>":** Shows the commit history filtered by a specific search pattern.
* **git show <commit>:** Displays detailed information about a specific commit.
* **git revert --no-commit <commit>..<commit>:** Reverts a range of commits without creating new commits for each individual revert.
* **git cherry-pick --no-commit <commit>..<commit>:** Cherry-picks a range of commits without immediately creating new commits.
* **git clean -f:** Removes untracked files from the working directory.
* **git submodule update --init --recursive:** Initializes and updates all submodules in the repository.
* **git remote show <remote_name>:** Displays detailed information about a specific remote repository.
* **git log --since=<date>:** Displays the commit history since the specified date.
* **git log --until=<date>:** Displays the commit history until the specified date.
* **git log --graph --oneline --decorate --all:** Shows a compact and visually pleasing commit graph with decorations and all branches.
* **git revert --no-edit <commit>:** Reverts a commit without opening the default commit message editor.
* **git commit --amend:** Amends the previous commit by adding staged changes or modifying the commit message.
* **git reset HEAD <file>:** Unstages the changes made to a specific file.
* **git blame -L <start_line>,<end_line> <file>:** Displays the commit and author information for a specific range of lines in a file.
* **git remote prune <remote_name>:** Removes remote tracking branches that no longer exist on the remote repository.
* **git cherry-pick --edit <commit>:** Cherry-picks a commit and allows you to modify the commit message before creating the new commit.
* **git bisect start:** Starts the process of finding a specific commit that introduced a bug using a binary search algorithm.
* **git remote rename <old_name> <new_name>:** Renames a remote repository.
* **git blame -C <file>:** Shows commit and author information for each line in a file, even for lines copied from elsewhere.
* **git bisect bad:** Marks the current commit as "bad" during the binary search process.
* **git bisect good <commit>:** Marks a specific commit as "good" during the binary search process.
* **git commit --amend --no-edit:** Amends the previous commit without modifying the commit message.
* **git stash branch <branch_name>:** Creates a new branch and applies the most recent stash to it.
* **git revert --continue:** Continues the process of reverting commits after resolving conflicts.
* **git push --force:** Forces a push to override the remote repository with your local changes (use with caution).
* **git clean -df:** Removes untracked files and directories forcefully, including ignored files.
* **git submodule foreach <command>:** Executes a command in each submodule of the repository.
* **git bisect reset:** Terminates the binary search process started with git bisect and returns the repository to its original state.
* **git reflog delete:** Deletes reflog entries, which can help manage and clean up your repository's history.
* **git rebase -i <commit>:** Initiates an interactive rebase, allowing you to modify, reorder, squash, or delete commits interactively.
* **git tag -d <tag_name>:** Deletes a local tag.
* **git blame --since=<date>:** Shows commit and author information for each line in a file since the specified date.
* **git push --tags --force:** Forces a push to update existing tags in the remote repository with local tags.
* **git clean -n -d:** Shows a list of untracked files and directories in the working directory, including those in subdirectories.
* **git stash drop <stash>:** Removes a specific stash from the stash list.
* **git stash clear:** Removes all stashes from the stash list.
* **git submodule update --remote:** Updates all submodules to the latest commit on their respective remote branches.
* **git rebase --abort:** Aborts an ongoing rebase operation and restores the branch to its state before the rebase started.
* **git push origin <local_branch>:<remote_branch>:** Pushes a specific local branch to a remote branch with a different name.
* **git log --author="<author_name>" --grep="<search_pattern>":** Displays the commit history filtered by both author and search pattern.
* **git log --stat:** Shows the commit history along with the summary of changes made in each commit.
* **git stash show <stash>:** Shows the changes stored in a specific stash.
* **git stash apply --index:** Applies the most recent stash along with the staged changes.
* **git diff <commit_A>..<commit_B>:** Displays the differences between two specific commits.
* **git blame -w <file>:** Shows commit and author information for each line in a file while ignoring whitespace changes.
* **git remote prune --dry-run:** Simulates a remote pruning operation to show which remote branches would be removed.
* **git submodule sync:** Updates the URL of submodules to match the latest changes made in the .gitmodules file.
* **git bisect visualize:** Opens a graphical interface to visualize the commit history during the git bisect process.
* **git stash save "<stash_message>":** Creates a new stash with a descriptive message.
* **git stash drop stash@{n}:** Removes a specific stash identified by its reference number.
* **git reflog expire --expire-unreachable=now --all:** Expires all reflog entries that are no longer reachable from any branch or tag.
* **git rebase --interactive HEAD~n:** Initiates an interactive rebase for the last n commits, allowing you to modify, reorder, squash, or delete commits.
* **git config --global alias.<alias_name> <command>:** Sets up a custom alias for a frequently used Git command.
* **git cherry-pick --skip:** Skips the current cherry-pick operation and moves on to the next commit in the series.
* **git blame -M <file>:** Shows commit and author information for each line in a file, including lines that were moved or copied.
* **git push origin --delete <tag_name>:** Deletes a specific tag from the remote repository.
* **git pull --rebase:** Fetches changes from the remote repository and rebases the current branch on top of the fetched changes.
* **git bisect run <command>:** Automates the process of finding a specific commit that introduced a bug by running a specified command on each commit.
* **git cherry-pick --signoff <commit>:** Cherry-picks a commit and adds a "Signed-off-by" line to the commit message, indicating the cherry-picker's agreement with the commit.
* **git log --graph --all:** Displays a textual representation of the commit history graph, including all branches.
* **git remote set-url <remote_name> <new_url>:** Changes the URL of a remote repository.
* **git submodule foreach --recursive <command>:** Executes a command in each submodule and their nested submodules recursively.
* **git reflog show <ref_name>:** Shows the reflog for a specific branch, tag, or reference.
* **git merge --no-ff <branch_name>:** Performs a merge with a specified branch, preserving all commits and creating a merge commit even if a fast-forward merge is possible.
* **git tag -a <tag_name> <commit> -m "<tag_message>":** Creates an annotated tag for a specific commit with a message, allowing for detailed information about the tag.
* **git grep <search_pattern>:** Searches for a specified pattern in the contents of tracked files.
* **git rebase --onto <new_base> <old_base> <branch>:** Reapplies commits from a branch onto a new base, discarding the old base.
* **git commit --fixup=<commit>:** Creates a fixup commit that addresses a specific previous commit, often used for refactoring or bug fixes.
* **git commit --squash=<commit>:** Squashes a specific commit into the previous commit, combining their changes into a single commit.
* **git rebase --autosquash:** Automatically applies fixup or squash commits during a rebase, based on their commit messages.
* **git worktree add <path> <branch>:** Creates a new worktree at the specified path, allowing you to work on multiple branches simultaneously.
* **git worktree list:** Lists all linked worktrees in the repository.
* **git cherry-pick --no-commit <commit>..<commit>:** Cherry-picks a range of commits without creating intermediate commit objects, resulting in a single cherry-pick commit.
* **git reset --soft <commit>:** Moves the branch pointer to a specific commit, preserving the changes as staged changes.
* **git stash show -p <stash>:** Shows the changes stored in a specific stash as a patch.
* **git commit --fix=<commit>:** Creates a commit that fixes a specific previous commit, often used for resolving issues or bugs.
* **git pull --rebase=<remote_branch>:** Performs a pull operation with the option to rebase the local branch onto a specific remote branch.
* **git revert --no-commit <commit>..<commit>:** Reverts a range of commits without immediately creating new commit objects, allowing for further modifications before committing.
* **git push --set-upstream origin <branch_name>:** Sets the upstream branch for the current local branch and pushes it to the remote repository.
* **git commit --no-verify:** Skips the pre-commit and commit-msg hooks, allowing you to bypass any custom validation or checks.
* **git submodule foreach --recursive git pull origin <branch>:** Updates all submodules, including nested submodules, to the latest version of a specific branch from the remote repository.
* **git log --merges:** Displays only merge commits in the commit history.
* **git push --force-with-lease:** Forces a push to the remote repository, but only if the remote branch's HEAD matches the expected value, protecting against inadvertently overwriting someone else's work.
* **git clean -fdx:** Removes untracked files and directories, including ignored files, forcefully and recursively.
* **git stash show --name-only <stash>:** Shows the file names of the changes stored in a specific stash.
* **git rebase --onto <new_base> <old_base> <branch>^:** Reapplies commits from a branch onto a new base, excluding the first commit in the range.
* **git merge --no-commit --no-ff <branch_name>:** Performs a non-fast-forward merge with a specified branch, creating a merge commit even if a fast-forward merge is possible, without automatically committing the merge.
* **git log --numstat:** Shows the commit history with added and deleted lines of code for each file.
* **git clean -i:** Interactively selects untracked files and directories to be removed from the working directory.
* **git cherry-pick --no-ff --edit <commit>:** Cherry-picks a commit, creating a merge commit and allowing you to modify the commit message before finalizing the cherry-pick.
* **git pull --rebase=preserve:** Performs a pull operation with the option to rebase, preserving the merge commits in the local branch history.
* **git config --global credential.helper cache:** Sets up Git to cache credentials for a period of time, reducing the need to re-enter credentials for remote operations.
* **git bisect visualize --oneline:** Opens a graphical interface to visualize the commit history during the git bisect process, showing each commit on a single line.
* **git rebase --skip:** Skips the current commit during an interactive rebase operation.
* **git stash show -u <stash>:** Shows the changes stored in a specific stash, including untracked files.
* **git commit --allow-empty:** Creates an empty commit with no changes, useful for triggering hooks or marking a point in the commit history.
* **git clean -e <pattern>:** Removes untracked files, excluding files matching the specified pattern.
* **git revert --mainline <parent_number> <commit>:** Reverts a merge commit, specifying the parent number to determine which branch's changes to keep.
* **git push --force-with-lease=<ref>:<ref>:** Forces a push to the remote repository, but only if the specified reference matches the expected value, providing an extra level of safety.
* **git log --grep="<pattern>" --author="<author>":** Displays the commit history filtered by both a search pattern and a specific author.
* **git commit --no-verify --amend:** Amends the previous commit without triggering pre-commit and commit-msg hooks, allowing you to make changes and update the commit message.
* **git stash save --include-untracked "<stash_message>":** Creates a stash that includes both tracked and untracked files.
* **git clean -e <pattern> -n:** Shows a list of untracked files and directories, excluding files matching the specified pattern, without actually removing them.
* **git checkout -- <file>:** Discards changes made to a specific file and restores it to the version in the last commit.
* **git push origin --all:** Pushes all local branches to the remote repository.
* **git diff <commit_A>..<commit_B> -- <file>:** Displays the differences between two specific commits for a particular file.
* **git stash branch <branch_name> <stash>:** Creates a new branch from a specific stash, applying the changes stored in the stash to the new branch.
* **git reflog expire --expire=<time>:** Expires reflog entries older than the specified time, helping to manage the size of the reflog.
* **git commit --no-verify --allow-empty-message:** Creates an empty commit without triggering pre-commit hooks and without a commit message.
* **git stash drop --all:** Removes all stashes from the stash list.
* **git push origin --mirror:** Pushes all local branches, tags, and deleted branches to the remote repository, effectively mirroring the local repository.
* **git branch --merged:** Lists branches that have been merged into the current branch.
* **git commit --no-verify --fixup=<commit>:** Creates a fixup commit that targets a specific commit, allowing for easy grouping of related changes.
* **git config --global --unset-all <key>:** Removes all configurations matching the specified key globally.
* **git worktree prune:** Prunes obsolete working trees, removing them from the repository.
* **git grep <search_pattern> -- <file_pattern>:** Searches for a specific pattern in the contents of files matching a specified pattern.
* **git remote show -n <remote_name>:** Displays information about a remote repository, including the tracked branches and remote references.
* **git clean -e <pattern> -xdf:** Removes untracked files and directories, excluding files matching the specified pattern, forcefully and recursively.
* **git stash drop --all:** Removes all stashes from the stash list, freeing up storage space.
* **git pull --rebase=interactive:** Performs a pull operation with interactive rebase, allowing you to modify and rearrange commits during the rebase process.
* **git cherry-pick --abort:** Aborts an ongoing cherry-pick operation and restores the repository to its state before the cherry-pick started.
* **git bisect run <script>:** Automates the process of finding a specific commit by running a script that determines whether each commit is good or bad.
* **git push --dry-run:** Simulates a push operation, showing which changes would be pushed to the remote repository without actually pushing them.
* **git blame --show-email <file>:** Displays commit and author information for each line in a file, including the author's email address.
* **git log --reverse:** Shows the commit history in reverse order, starting from the oldest commit.
* **git tag -n: Lists all tags in the repository along with their annotated tag messages.
* **git merge --no-verify <branch_name>:** Performs a merge operation, skipping pre-merge hooks and validations.
* **git rebase -i --root:** Initiates an interactive rebase that includes all commits in the repository, starting from the root commit.
* **git stash branch --track <branch_name> <stash>:** Creates a new branch from a specific stash and tracks the new branch.
* **git checkout --patch <file>:** Interactively selects and stages specific changes within a file.
* **git submodule foreach --recursive <command>:** Executes a command in each submodule and their nested submodules recursively.
* **git pull --rebase=merges:** Performs a pull operation with the option to rebase, preserving the merge commits in the local branch history.
* **git revert --no-commit --no-edit <commit>..<commit>:** Reverts a range of commits without creating new commits or opening the default commit message editor.
* **git clean -e <pattern> -xdfn:** Shows a list of untracked files and directories, excluding files matching the specified pattern, without actually removing them, in a dry-run mode.
* **git cherry-pick --ff:** Forces a fast-forward merge when cherry-picking commits.
* **git branch --sort=-committerdate:** Lists branches sorted by the committer date in descending order.
* **git show-branch:** Displays the commit history and branch topology in a compact format.
* **git log --no-merges:** Displays the commit history excluding merge commits.
* **git push --set-upstream origin <local_branch>:** Sets the upstream branch for the current local branch and pushes it to the remote repository.
* **git stash drop --all:** Removes all stashes from the stash list, including both saved and working stashes.
* **git commit --fix=<commit>:** Creates a commit that fixes a specific previous commit, often used for addressing issues or bugs.
* **git clean -e <pattern> -d:** Removes untracked directories, excluding files matching the specified pattern.
* **git submodule sync --recursive:** Updates the URL of submodules and their nested submodules to match the latest changes made in the .gitmodules file.
* **git push --follow-tags:** Pushes commits and tags to the remote repository, ensuring that annotated tags are also pushed.
* **git checkout --detach:** Checks out the repository in a detached HEAD state, allowing you to view previous commits without creating a branch.
* **git tag -l "<pattern>":** Lists tags matching the specified pattern.
* **git worktree add --detach <path> <commit>:** Creates a new detached worktree at the specified path and checks out a specific commit.

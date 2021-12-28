# Git commands that may be asked in your interview: 


- git init -> Initialize an existing directory as a Git repository
- git clone [url] -> Retrieve an entire repository from a hosted location via URL
- git status -> Show modified files in working directory, staged for your next commit
- git add [file] -> Add a file as it looks now to your next commit (stage)
- git reset [file] -> Unstage a file while retaining the changes in working directory
- git diff  -> Difference of what is changed but not staged.
- git diff --staged -> Diff of what is staged but not yet commited
- git commit -m “[descriptive message]” -> commit your staged content as a new commit snapshot.
- git branch -> list your branches. a * will appear next to the currently active branch.
- git branch [branch-name] -> create a new branch at the current commit
- git checkout [branch-name] -> switch to another branch and check it out into your working directory.
- git merge [branch] -> merge the specified branch’s history into the current one
- git log -> show all commits in the current branch’s history.
- git merge [alias]/[branch] -> merge a remote branch into your current branch to bring it up to date.
- git remote add [alias] [url] -> add a git URL as an alias.
- git fetch [alias] -> fetch down all the branches from that Git remote
- git push [alias] [branch] -> Transmit local branch commits to the remote repository branch
- git pull [alias] [branch] -> fetch and merge any commits from the tracking remote branch.

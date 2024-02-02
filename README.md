# Git Commands

`git init`: initialize current folder as a git repository
`git clone <url>`: brings the git repo from <url> to the current folder
`git status`: tess us what we need to know about our repository
`git add <FILE>`: adds <FILE> to the stagin area
`git commit`: open a text editor to write commit message
`git commit -m "MESSAGE"`: writes MESSAGE as a commit without a text editor
`git log`: shows the log (history) of our commits
`git log`: shows the shorter oneline log (history) of our commits
`git diff`: compare current uncommitted state with the last known git state
`git diff --staged`: runs git diff between the staging aread and the last known state
`git diff <HEAD~<NUMBER>`: compares HEAD with commit <NUMBER> ago (relative)
`git diff <HASH>`: compares HEAD with the commit in <HASH>
`git restore --source <HASH or HEAD~> <FILE>`: restore FILE to <HASH or HEAD~>
`git checkout <HASH or HEAD~> <FILE>`: restore FILE to <HASH or HEAD~>
`git checkout <HASH or HEAD~>`: if you forget file, you end up in detached HEAD state - `git checkout main`: go back to main - `git switch -`: go back to main

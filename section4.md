understanding Git Stash
to save uncommitted, unstaged changes.

some stashed changes.

git log --merge
to log out the 2 commits that are in conflict

git diff
to see current and incoming changes


Merge vs Rebase vs Cherry-Pick

Cherry-Pick
add specific commit to branch (HEAD)
it copies commit with new ID

tags: lightweight vs annotated tags.
lightweight (temporary) tag. is basically a pointer
annotated is a git object
Tags are useful for milestones

git tag tagname
to create a temporary tag

git tag -a tagname -m "this is update to Beta version"
to create a full object (annotated)


git tag -d tagname
to delete a tag

Section 4 Wrap up

git stash - temporary storage for unstaged and uncommitted changes
git reflog - a log of all project changes made including deleted commits
git merge - combine commits from different branches (recursive creates new merge commit) or (fast forward: moving the HEAD)
git rebase - change the base (i.e. parent commit) of commits in another branch
git cherry-pick - copy commit including the changes made only in this commit as HEAD to other branch

when creating a new branch, it is important which branch you copy from, as all commits of that branch will be copied over.

Merging branches: if you are on MASTER, and you want to merge "Branch-3" into MASTER, then simply "git merge Branch-3"

#### What is the "Head"?

by default, Head points to latest commit.

#### What is "detached HEAD"?

if you checkout to a non-Head commit, you will see this when you "git branch":

-   \*(HEAD detached at f264859f)
    master
    second-branch

Because you are no longer at the most recent (Head) commit.

`git switch`
`git switch -c fourth-branch`

#### How to delete data (or go back)

-   working directory files
-   undoing Unstaged changes
-   staged changes
-   deleting latest commit(s)
-   deleting branches

`git ls-files`

**\*** Git Notes from Fireship's video **\***

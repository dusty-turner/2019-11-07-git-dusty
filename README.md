# Git Workshop DCR 2019 (DCR 2019)

Git Workshop for DCR 2019 notes.

## Local

- `init`: initialize folder as git repo
- `status`: see what is going on in the repo
- `add`: put file(s) into staging area
- `commit`: commit files from staging area (snapshot)
- `diff`: looks for differences in commits
- `checkout`: move your head around to different commits
- `head`: where you are currently looking or located
- `log`: looking at all the previous messages or commands (typed)
	-`log --oneline`: get a one line message history
	
## Remotes

- `remote`: somewhere your git repo is stores (eg, GITHUB)
 - `origin`: the default you give your remote
- `pull`: receiving local changes to remote
- `push`: sending local changes to remote

## Branches

- `branch <branch_name>`: create a new branch
- `checkout <branch_name>`: move to that branch
- `checkout -b <branch_name>`: create and move at the same time
- `branch -a`: see what branches exist
- `log --oneline --graph --decorate --all`: shows what is going on
- `branch -d <name_of_branch>`: delets branch 
- `git fetch --prune`: gets rid of remote branch that's already gone
- `branch -D`: force dele a branch that was *not* merged

## Updating history 

- `rebase <branch_name>`: incorporate changes in <branch_name> eg, `master` into current branch, eg `project_template` 
  - You perform this cocmmand on the feature branch, not on `master`. 

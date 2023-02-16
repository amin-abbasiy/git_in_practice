# Git Remote 

	git remote show # query on remote and show data
	git remote prune #delete remote repo branches references from local which deleted by other users

## PUSH

	git push --set-upstream origin master #set remote master tranking(upstream) branch for your local master on remote
	git push --all #push all branches and tags
	git push --force #disable some checks in remote while pushing

## CLONE

	git clone URL --bare | --mirror | 
	--depth #nubmer of revisions
	--recurse-submodules #all the git submodules
## PULL

	git clone URL target_folder
	git pull
	git pull --rebase #rebase instead of merege after fetch

## FETCH

	git fetch #fetch data without merging it

## BRANCH

Branching allows two independent tracks through history to be created and committed to without either modifying the other.
In Git, a branch is no more than a pointer to a particular commit.

	git branch <branch-name> master #create branch base on master branch
	git checkout <branch-name> #check out content of current branch to this branch, files states will be change to what this branch points 

## TAG

Typically tags are used for annotating commits;


## CHECKOUT

check out to new branch and change state of HEAD pointer

	git checkout --force #this will overrite uncommited changes
	git stash #save changes temporarialy


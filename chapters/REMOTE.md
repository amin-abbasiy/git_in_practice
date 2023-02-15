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

# Git in Practice 

## Diff

	git diff master~1 master -- concept.md # only diff for this particular file or path
### Diff two formats

	git diff --stat master~1 master
	git diff --word-diff master~1 master

## Ref

Suffixing a ref with ~1 is the same as saying “one commit before that ref.”

~1 eq ^
~2 eq ^^

HEAD in pointer to on top of currently you checked out

These git diff invocations are all equivalent:

- master~1 master
- master~1..master
- master~1..
- master^ master
- master~1 HEAD
- 6576b68 6b437c7

git rev-parse master #expand to full 40 char SHA1


## Remote 

	git push  #send commits to remote
	git fetch #receive commits from remote
	git remote add origin $url #add reference to remove repo
	git remove --verbose #confirm reference added

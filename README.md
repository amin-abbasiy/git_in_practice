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

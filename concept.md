# Concept

## Local Git

Git repositories store all their data on your local machine. Making commits, view-
ing history, and requesting differences between commits are all local operations that
don’t require a network connection.

    $ find .

Event Hooks: shows event hook samples (scripts that run on defined events). For example, pre-
commit is run before every new commit is made.

git commit can be called with --author and --date flags to override the auto-set
metadata in the new commit.

Git objects we’re concerned with: commits, blobs,
and trees. There’s also a tag object, but don’t worry about tags until they’re introduced
in technique 36. Figure 1.2 showed an example of a commit object and how it stores
metadata and referenced file contents. The file-contents reference is actually a refer-
ence to a tree object. A tree object stores a reference to all the blob objects at a particular
point in time and other tree objects if there are any subdirectories. A blob object stores
the contents of a particular version of a particular single file in the Git repository.

Ideally, commits are small and well-described; follow these
two rules, and having a complete history becomes a very useful tool.

The commit message should describe what the commit does in as much detail as is useful, in the
present tense.

    $ git log [-p --stat ]

In Git you can request a diff between any two commits, branches, or tags.

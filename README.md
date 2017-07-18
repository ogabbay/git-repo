# repo

Repo is a tool built on top of Git.  Repo helps manage many Git repositories,
does the uploads to revision control systems, and automates parts of the
development workflow.  Repo is not meant to replace Git, only to make it
easier to work with Git.  The repo command is an executable Python script
that you can put anywhere in your path.

* Homepage: https://code.google.com/p/git-repo/
* Bug reports: https://code.google.com/p/git-repo/issues/
* Source: https://code.google.com/p/git-repo/
* Overview: https://source.android.com/source/developing.html
* Docs: https://source.android.com/source/using-repo.html
* [Submitting patches](./SUBMITTING_PATCHES.md)

# topic branches modification

The modification is that if you are working on a topic branch and you do "repo sync", you will get the following message:

"[repo name]: You are working on topic branch [branch name] while manifest points to [...], so skipping rebase"

To use this tool, do:

* curl https://raw.githubusercontent.com/gabbayo/git-repo/topic_branches/repo > /usr/bin/repo
* chmod a+x /usr/bin/repo

After that, you will need to do a clean "repo init" to use the new tool

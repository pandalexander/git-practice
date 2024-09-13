Explain what it means for branches to be pointers.

- Branches are simply pointers to the latest commit in that particular branch. the commit that it is pointing to is also a pointer to the commit before it, much like a linked list, it just continues back to the beginning of a branch. That is what it means for a branch to be a pointer. The branch isn't actually a collection of commits, it simply is a pointer to the latest commit in the stream of that branch.

How can you amend your last commit?

- You can use git commit --amend -m 'amended git message here'

What are some different ways to rewrite history?

- There are several ways to rewrite git history. The two that come to mind are git rebase and git reset. there are several differences between how rebase and reset work, and it's important that you confirm with your team before changing any git changes that other people are working from. Also, make sure that the commits aren't destructive to your working directory unless you are sure that is what you want to do. It's not always the best idea to completely erase your data, but it can be the right call in some situations.

vanilla-git-aliases
===================

> **Dead simple**, clean aliases for git commands.

Only defines an alias for the base of a command, so instead of:
```
alias gbr='git branch --remote'
```
it only has:
```
alias gb='git branch'
```

So to achieve the former user would have to do `gb --remote`.

This ensures both quicker memorization and simpler setup.

Only exceptions are: `git add --all`, `git commit --amend`, `git diff --cached` and `git
reset HEAD` as those are too frequently used to not have an alias for.


Full list of aliases
--------------------

See [vanilla-git-aliases.zsh](vanilla-git-aliases.zsh)


License
-------
MIT © [Justyna Rachowicz](https://github.com/mrowa44)

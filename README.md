# Git Scripts

Helper scripts for managing git workflow.

## Intstallation

Add `git-cosmetic-commit` to your `$PATH` e.g.

```sh
cd /usr/local/bin && curl -L https://raw.githubusercontent.com/mrloop/git_scripts/master/git-cosmetic-commit | sudo tee git-cosmetic-commit >/dev/null; sudo chmod 755 git-cosmetic-commit
```

## git-cosmetic-commit

Creates a new commit for cosmetic changes on current feature branch or creates a new fixup commit for cosmetic changes commit on current branch.

```sh
git cosmetic-commit
```

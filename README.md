# pokecollapse

A work-in-progress Pokemon Emerald ROM hack.

Based off RHH's `pokeemerald-expansion` https://github.com/rh-hideout/pokeemerald-expansion/.

## Setup

Follow the instructions in the [`INSTALL.md`](INSTALL.md) file.

## Sync with `pokeemerald-expansion`

To sync with the latest changes from `pokeemerald-expansion`, run the following commands:

```bash
# Add the pokeemerald-expansion repo as a remote
git remote add upstream git@github.com:rh-hideout/pokeemerald-expansion.git

# Fetch the latest changes from the pokeemerald-expansion repo
git fetch upstream

# Rebase the changes from the pokeemerald-expansion repo into the current branch
git rebase upstream/master
```

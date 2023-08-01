# ml_for_monsters
SoT for ML/AI coursework for "ML for Monsters" at DeepMay 2023

Materials for the class.

## Workflow:

### On day 1
    1. make an auth token in github to do https
    2. https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens 
    3. FORK this repository in github, creating your own personal username/ml-for-monsters
    4. navigate to nb.deepmay.net
    5. launch a terminal
    6. `git clone git clone https://oauth-key-goes-here@github.com/username/DM23-ml-for-monsters.git`

Next we will set the original repo as the `remote` `upstream` source of truth:

```
git remote add upstream https://github.com/deepmay/DM23-ml-for-monsters
```

This will allow us to (so-to-speak) "sync" our forked version of the repo with the original

### In the morning

First we need to check for changes to the DeepMay version of the repo

```
git fetch upstream main
```

    1. `git fetch origin`
    2. `git merge --ff-only origin main`

### In the evening
    1. `git add *`
    2. `git status`
    3. `git commit -m "day 1 work"
    4. `git log`
    5. `git push origin HEAD`

your changes are saved!

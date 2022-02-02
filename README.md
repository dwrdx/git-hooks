# Git Hooks

A bunch of usefull git hooks for your convenience

# How to use

* Clone this project
* Use `git config --global core.hooksPath /path/to/my/hooks` to configure the global hooks path for your git

# Hooks

## pre-commit

Sometimes, you will need to use different emails for different projects, It's frustrating if you forget to configure local
user.name and user.email of git for different repos, even wrose, sometimes, you already push the commits to the remote.

This hook is here to help, It will ask you to check the user name and email before doing the actual commit action.
 


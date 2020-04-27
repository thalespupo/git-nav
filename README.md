# git-nav
Tool for git-branch navigation

# Usage
git-nav \<branch-index>


Run git-nav to have a simple indexed list of your last 5 branchs that you worked.

Run git-nav with index of your desired branch to checkout to it.

# Example
```
$ git-nav
[0] feature/firefighter_fix
[1] feature/awesome_tool
[2] dev
[3] master
[4] dev
```

```
$ git-nav 2
Switched to branch 'dev'
Your branch is up to date with 'dev'.
```

# Git & Github

- [Git & Github](#git--github)
- [Initialize git](#initialize-git)
- [Git status](#git-status)
- [Track untracked files](#track-untracked-files)
- [Git commit](#git-commit)
- [Check all commits](#check-all-commits)

# Initialize git

```sh
git init
```

Initialize git means all files and folders are trackable with git

# Git status

```sh
git status
```

Show the current status of git repo

# Track untracked files

| Command                  | Description               |
| ------------------------ | ------------------------- |
| **git add .**            | track all untracked files |
| **git add [ .. files ]** | track a specific file     |

# Git commit

| Command                 | Description                                                     |
| ----------------------- | --------------------------------------------------------------- |
| **git commit**          | it will open vim and inside vim we can write our commit message |
| **git commit -m "msg"** | commit message inside double quotes                             |

# Check all commits

| Command               | Description                         |
| --------------------- | ----------------------------------- |
| **git log**           | show all commits with author & date |
| **git log --oneline** | show all commits shortly            |

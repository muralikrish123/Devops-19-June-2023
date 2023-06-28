# Prerequsite before commit

- Create your project folder
- CD to create folder
- Run command `git init`
- Create some empty files or folders
- Set ownership (because git expects to give some basic information about the commit person)

  `git config --global user.name "vijay"`
  `git config --global user.email "mail.id"`


## commit 1

| Task                  | Command                         | Notes                                             |
| --------------------- | --------------------------------|---------------------------------------------------|
| Check untracked files | `git status`                    | To check untracked files in repo                  |
| Stage files           | `git add basic.sh`              | use `git status` again to check if file is staged |
| Commit files          | `git commit –m "First commit"`  | commit message can be user defined                |

## commit 2

* Let's try to modify the file again and do second commit

| Task                  | Command                         | Notes                                             |
| --------------------- | --------------------------------|---------------------------------------------------|
| Modify the source     |                                 |                                                   |
| Check untracked files | `git status`                    | To check untracked files in repo                  |
| Stage files           | `git add basic.sh`              | use `git status` again to check if file is staged |
| Commit files          | `git commit –m "Second commit"` | commit message can be user defined                |

### Key commands

| Task                  | Command                         | Notes                                             |
| --------------------- | --------------------------------|---------------------------------------------------|
| Check commit logs     | `git log`                       | view history of commits                           |
| Check commit logs     | `git log --oneline`             | view commit logs in oneline                       |

### Remove file from git (from all commits)
```bash
git filter-branch --index-filter 'git rm -rf --cached --ignore-unmatch path_to_file' HEAD
```


### Set user identity
#### Global
```bash
git config --global user.name "Petr Jandl"
git config --global user. email "you@example.com"
```
#### Only this project
```bash
git config user.email "petr.jandl@gmail.com"
```

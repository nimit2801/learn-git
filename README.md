# Learning Git with Nimit :)

## Basics
1. Initialize git

- Initialize locally
  ```sh
  git init
  ```
- Clone from a repo in cloud
  ```sh
  git clone <url>
  ```

2. Add files to staging
  
  - Add single file
  ```sh
  git add fileName.txt
  ```
  - Add folder to staging 
  ```sh
  git add /fileName
  ```
  - Add all files
  ```sh
  git add .
  ```

3. Commit the files from staging to create a version
- New Branch
  ```sh
  git commit -m "Important feauture"
  ```

4. Pull/Push to the repository
- Pull
  ```sh
  git pull
  ```
- Push
  ```sh
  git push
  ```

5. Checkout branch
- Create and checkout to new
  ```sh
  git checkout -b feature/working
  ```
- Old branch
  ```sh
  git checkout feature/old
  ```
   
6. Switch between branches
```sh
git switch
```

## Intermedieate concepts
1. Ingnore files from git ignore
```sh
vim .gitignore
```

2. View commit history
```sh
git log
```

- `git stash`: Temporarily save changes that are not ready to be committed
- `git stash pop`: Apply the most recently stashed changes
- `git fetch`: Download objects and refs from a remote repository

## Advanced
- `git submodule`: Manage git repositories within a git repository
- `git cherry-pick <commit>`: Apply the changes introduced by some existing commits
- `git rebase <branch>`: Reapply commits on top of another base tip

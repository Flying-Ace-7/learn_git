
## Basic commands on Git

### 1. Setting up a Repository:
- git init: Initializes a new Git repository in the current directory. 

``` git init ```


- git clone <repository-url>: Creates a local copy of an existing remote repository.

``` git clone https://github.com/user/repo.git ```

### 2. Staging and Committing Changes:
- git status: Displays the state of the working directory and the staging area, showing staged, unstaged, and untracked files.

``` git status```

- git add <file>: Adds a specific file to the staging area. 

``` git add index.html```

- git add .: Adds all new and changed files in the current directory to the staging area.

``` git add . ```

- git commit -m "Your commit message": Records the staged changes in the repository with a descriptive message.


``` git commit -m "Initial commit of project files" ```

## 3. Working with Branches:
- git branch: Lists all local branches in the repository. The asterisk indicates the current branch.

``` git branch```


- git branch <branch-name>: Creates a new branch.

``` git branch feature/new-feature```

- git checkout <branch-name>: Switches to a different branch.

```git checkout feature/new-feature```

- git merge <branch-name>: Merges changes from the specified branch into the current branch.

``` git merge feature/new-feature ```

## 4. Interacting with Remote Repositories:
-git pull: Fetches changes from a remote repository and merges them into the current local branch. 

``` git pull origin main ```

- git push: Uploads local commits to a remote repository.

``` git push origin main ```
## 5. Viewing History:

- git log: Shows the commit history for the current branch. 

``` git log ```

- git diff: Shows the differences between the working directory and the staging area, or between commits.

``` git diff ```

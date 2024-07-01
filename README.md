<style>
body {
    background-color: #15202B; /* Black background for the page */
    color: white; /* White text for better contrast */
    font-family: Arial, sans-serif; /* Example font */
    line-height: 1.6; /* Improved readability */
}

.code-highlight {
    background-color: #00C4A7; /* Light green background for commands */
    color: black; /* Black text for commands */
    padding: 2px 4px;
    border-radius: 4px;
}

.code-description {
    color: white; /* White text for descriptions */
}
</style>

### Configuring Git
- **<span class="code-highlight">`git config --global user.name "Your Name"`**</span>
  - <span class="code-description">Set the user's name for all repositories.</span>
- **<span class="code-highlight">`git config --global user.email "your.email@example.com"`**</span>
  - <span class="code-description">Set the user's email for all repositories.</span>

### Basic Operations
- **<span class="code-highlight">`git init`**</span>
  - <span class="code-description">Initialize a new Git repository.</span>
- **<span class="code-highlight">`git clone <repository-url>`**</span>
  - <span class="code-description">Clone an existing repository.</span>

### Working with Branches
- **<span class="code-highlight">`git branch`**</span>
  - <span class="code-description">List all branches.</span>
- **<span class="code-highlight">`git branch <new-branch-name>`**</span>
  - <span class="code-description">Create a new branch.</span>
- **<span class="code-highlight">`git checkout <branch-name>`**</span>
  - <span class="code-description">Switch to a branch.</span>
- **<span class="code-highlight">`git checkout -b <new-branch-name>`**</span>
  - <span class="code-description">Create and switch to a new branch.</span>

### Making Changes
- **<span class="code-highlight">`git status`**</span>
  - <span class="code-description">Check the status of the working directory.</span>
- **<span class="code-highlight">`git add <file-or-directory>`**</span>
  - <span class="code-description">Stage changes for commit.</span>
- **<span class="code-highlight">`git add .`**</span>
  - <span class="code-description">Stage all changes in the working directory for commit.</span>
- **<span class="code-highlight">`git commit -m "Your commit message"`**</span>
  - <span class="code-description">Commit staged changes.</span>

### Viewing History
- **<span class="code-highlight">`git log`**</span>
  - <span class="code-description">Show commit history.</span>
- **<span class="code-highlight">`git log --oneline`**</span>
  - <span class="code-description">Show commit history with one-line summaries.</span>

### Pushing and Pulling Changes
- **<span class="code-highlight">`git push origin <branch-name>`**</span>
  - <span class="code-description">Push changes to a remote repository.</span>
- **<span class="code-highlight">`git pull origin <branch-name>`**</span>
  - <span class="code-description">Pull changes from a remote repository.</span>

### Merging and Rebasing
- **<span class="code-highlight">`git merge <branch-name>`**</span>
  - <span class="code-description">Merge a branch into your current branch.</span>
- **<span class="code-highlight">`git rebase <branch-name>`**</span>
  - <span class="code-description">Rebase your current branch onto another branch.</span>

### Handling Conflicts
- **<span class="code-highlight">`git add <file-with-conflict>`**</span>
  - <span class="code-description">Mark conflicts as resolved.</span>
- **<span class="code-highlight">`git rebase --continue`**</span>
  - <span class="code-description">Continue rebase after resolving conflicts.</span>

### Stashing Changes
- **<span class="code-highlight">`git stash`**</span>
  - <span class="code-description">Stash uncommitted changes.</span>
- **<span class="code-highlight">`git stash apply`**</span>
  - <span class="code-description">Apply stashed changes.</span>

### Collaborating with Remote Repositories
- **<span class="code-highlight">`git remote add <remote-name> <repository-url>`**</span>
  - <span class="code-description">Add a remote repository.</span>
- **<span class="code-highlight">`git remote -v`**</span>
  - <span class="code-description">List remote repositories.</span>
- **<span class="code-highlight">`git fetch <remote-name>`**</span>
  - <span class="code-description">Fetch changes from a remote repository.</span>
- **<span class="code-highlight">`git push <remote-name> <branch-name>`**</span>
  - <span class="code-description">Push changes to a remote repository.</span>

### Viewing Differences
- **<span class="code-highlight">`git diff`**</span>
  - <span class="code-description">Show differences between working directory and the index.</span>
- **<span class="code-highlight">`git diff --cached`**</span>
  - <span class="code-description">Show differences between the index and the last commit.</span>

### Tags
- **<span class="code-highlight">`git tag <tag-name>`**</span>
  - <span class="code-description">Create a new tag.</span>
- **<span class="code-highlight">`git push origin --tags`**</span>
  - <span class="code-description">Push tags to the remote repository.</span>

# Proof of Work — DevOps Git Challenge

## 1. Git Commit History

PS D:\Semester 7\DevOps\Activities\53325_VersionControl_Activity\devops-git-challenge> git log --oneline --all --graph
*   b00c223 (HEAD -> main, origin/main) Merge pull request #1 from AbdulRafay300/development
|\  
| *   3f7fbac (origin/development, development) fix: resolved merge conflict
| |\  
| | * 30b808e (origin/staging, staging) fix: staging label
| |/  
|/|   
| * 178a71f updated script with staging environenmt
|/  
* 78e02b6 feat: initial commit with deploy script

## 2. Reflection Questions

### Q1. Difference between Git and GitHub

Git is a version control system that runs on my computer and tracks the changes in the files. It allow me to create commits, manage branches, and compare different versions of my work. GitHub is an online platform where I can store Git repositories and share them with others. It also provides features like Pull Requests and collaboration.

### Q2. Explain the Working Directory, Staging Area, and Local Repository

The Working Directory is where I create or edit files on my computer. The Staging Area contains the changes I select using `git add` before making a commit. The Local Repository stores committed versions of the project and its history. These three stages help me to control which changes become part of the commit.

### Q3. Difference between git stash pop and git stash apply

Both the commands restore changes saved using `git stash`. The `git stash pop` command restores the changes and normally removes the selected stash entry if the restoration succeeds. The `git stash apply` command restores the changes but keeps the stash entry. I use `pop` when I no longer need the saved entry and `apply` when I want to keep it for later.

### Q4. Difference between git fetch and git pull

The `git fetch` command download the new commits and other relevant updates from a remote repository without merging them into my current branch. The `git pull` command fetches remote updates and then integrates them into the current branch, this is done usually by merging depending on the configuration. Fetching is useful when I want to inspect remote changes before integrating or merging them. Pulling is useful when I am ready to update my local branch.
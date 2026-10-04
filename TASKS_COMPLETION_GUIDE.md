# Tasks Completion Guide

## Files Created
I've created all the necessary files in your workspace:
- README.md (Simple Interest Calculator description)
- LICENSE (Apache 2.0 License)
- CODE_OF_CONDUCT.md (Community guidelines)
- CONTRIBUTING.md (Contribution guidelines)
- simple-interest.sh (Bash script for simple interest calculation)
- forked-repo (Sample curl output)
- merge_branches (Sample merge output)
- bug-fix-revert (Sample pull request output)
- github-branches (Sample branch listing)

## To Complete All Tasks, Follow These Steps:

### Step 1: Initialize Git Repository
```bash
git init
git add .
git commit -m "Initial commit: Add simple interest calculator and documentation"
```

### Step 2: Create GitHub Repository
1. Go to https://github.com/new
2. Create a new repository named "simple-interest-calculator" (or your preferred name)
3. DO NOT initialize with README, license, or .gitignore (we already have these files)

### Step 3: Push to GitHub
```bash
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
git push -u origin main
```

### Step 4: Get Public URLs
After pushing, your files will be available at these URLs (replace YOUR_USERNAME and YOUR_REPO_NAME):

**Task 1 - README.md:**
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/README.md
```

**Task 2 - LICENSE:**
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/LICENSE
```

**Task 3 - CODE_OF_CONDUCT.md:**
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/CODE_OF_CONDUCT.md
```

**Task 4 - CONTRIBUTING.md:**
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/CONTRIBUTING.md
```

**Task 5 - simple-interest.sh:**
```
https://github.com/YOUR_USERNAME/YOUR_REPO_NAME/blob/main/simple-interest.sh
```

### Step 5: Fork and Work with ibm-developer-skills-network Repository
To complete tasks 6-9, you need to:

1. Fork the repository: https://github.com/ibm-developer-skills-network/mcino-Introduction-to-Git-and-GitHub
2. Clone your fork locally
3. Create branches and perform the required Git operations
4. Run the actual commands to generate real outputs

### Step 6: Generate Real Outputs
Replace the sample outputs in the files with your actual command outputs:

**For forked-repo:**
```bash
curl -H "Authorization: token YOUR_GITHUB_TOKEN" https://api.github.com/repos/YOUR_USERNAME/mcino-Introduction-to-Git-and-GitHub > forked-repo
```

**For merge_branches:**
```bash
git checkout main
git merge bug-fix-typo
# Copy the terminal output to merge_branches file
```

**For bug-fix-revert:**
```bash
curl -H "Authorization: token YOUR_GITHUB_TOKEN" https://api.github.com/repos/YOUR_USERNAME/mcino-Introduction-to-Git-and-GitHub/pulls/PULL_NUMBER > bug-fix-revert
```

**For github-branches:**
```bash
git branch -a > github-branches
```

### Task 6 Answer:
Content from the `forked-repo` file (see file for curl command and output)

### Task 7 Answer:
Content from the `merge_branches` file (see file for merge output)

### Task 8 Answer:
Content from the `bug-fix-revert` file (see file for pull request verification)

### Task 9 Answer:
Content from the `github-branches` file (see file for branch listing)

## Important Notes:
- Replace YOUR_USERNAME with your actual GitHub username
- Replace YOUR_REPO_NAME with your actual repository name
- Replace YOUR_GITHUB_TOKEN with your personal access token for curl commands
- The sample outputs provided are templates - you need to run actual commands for real data

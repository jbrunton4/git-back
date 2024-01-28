# jbrunton4/git-back

## Installation & Usage
Use cURL to clone the script into your user binaries:
```bash
curl -sSL https://raw.githubusercontent.com/jbrunton4/git-back/main/git-back.sh > /usr/bin/git-back
```

## Usage
Use the `git-back` command while in a git repository to create an instant backup of your working state on a new branch. 

Currently, this is limited to only work while on a branch head, and will pull all files out of your commit index. 
# Github CMD

```bash
# 1. Stage your files
git add .

# 2. Commit them (ALWAYS commit before tagging)
git commit -m "Initial commit: Shén Mó v1.0"

# 3. Push the commit to GitHub
git push origin main    # or 'master' if that's your branch name

# 4. Create a version tag
git tag v1.0

# 5. Push the tag
git push origin v1.0
```

```bash
# 1. Create a new branch
git checkout -b v1.0

# 2. Push branch to GitHub
git push origin v1.0

# 3. Switch between branches
git checkout main       # Switch to main
git checkout v1.0       # Switch back to v1.0

# 4. View branches
git branch              # Local branches
git branch -r           # Remote branches
git branch -a           # All branches (local + remote)

# 5. Merge v1.0 into main
git checkout main
git merge v1.0
```

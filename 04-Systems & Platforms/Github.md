# Create repo

## 1. Use website to create repo (leave empty)

## 2. On local machine

```powershell
# Initialize local repo if not already a git repo
git init

# Add remote
git remote add origin git@github.com:<user>/<repo>.git

# Push local main branch
git push -u origin main
```

# Workflow

```powershell
git add .
git commit -m "Initial commit"
git push -u origin main
```

# Generating an SSH Key (PowerShell)

```powershell
ssh-keygen -t ed25519 -C "your_email@example.com"

# Option 1: Using Get-Content
Get-Content ~/.ssh/id_ed25519.pub

# Option 2: Using 'cat' alias
cat ~/.ssh/id_ed25519.pub

# Test connection
ssh -T git@github.com
```

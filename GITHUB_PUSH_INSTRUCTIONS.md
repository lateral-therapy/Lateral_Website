# Instructions to Push LATERAL Website to GitHub

Follow these steps to create the repository and push the code:

## 1. Create Repository on GitHub

1. Go to https://github.com/new
2. Repository name: `LATERAL`
3. Description: "Lay Therapy Research Lab - Scaling mental health solutions through community-led innovation"
4. Set as Public or Private (your choice)
5. **DO NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

## 2. Push the Code

After creating the repository, GitHub will show you commands. Use these in your terminal:

```bash
# Navigate to the project directory
cd /Users/blai90/Documents/LATERAL_Website/lateral-site

# Add the remote repository (replace USERNAME with scottdougblain)
git remote add origin https://github.com/scottdougblain/LATERAL.git

# Push the code
git push -u origin main
```

If you get an authentication prompt, you may need to:
- Use your GitHub username and a Personal Access Token (not password)
- Or set up SSH keys

## 3. Alternative: Using GitHub Desktop

If you prefer a GUI approach:
1. Open GitHub Desktop
2. Add > Add Existing Repository
3. Browse to `/Users/blai90/Documents/LATERAL_Website/lateral-site`
4. Publish repository
5. Name it "LATERAL" and choose scottdougblain as the account

## 4. Enable GitHub Pages (Optional)

To host the website directly from GitHub:
1. Go to repository Settings
2. Scroll to "Pages" section
3. Source: Deploy from a branch
4. Branch: main, folder: / (root)
5. Save

The site will be available at: https://scottdougblain.github.io/LATERAL/

## Current Status

The repository is initialized locally with:
- All website files committed
- Branch named 'main'
- Ready to push

Just need to create the remote repository on GitHub and connect it!
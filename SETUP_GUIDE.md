# GitHub Repository Setup Guide

Step-by-step instructions to create and publish the AI Slides repository on GitHub.

## Prerequisites

- Git installed on your computer
- GitHub account
- Terminal/Command Line access

## Step 1: Initialize Git Repository

Open Terminal and navigate to the project directory:

```bash
cd /Users/nandan/Downloads/newskills/ai-slides
```

Initialize the Git repository:

```bash
git init
git add .
git commit -m "Initial commit: AI Slides - Next-generation slide generator"
```

## Step 2: Create GitHub Repository

### Option A: Using GitHub CLI (Recommended)

If you have GitHub CLI installed:

```bash
# Login to GitHub (if not already logged in)
gh auth login

# Create the repository
gh repo create ai-slides --public --source=. --remote=origin --push

# Set description
gh repo edit --description "AI-powered skill for creating stunning HTML presentations with intelligent content optimization, premium themes, and zero dependencies"

# Add topics
gh repo edit --add-topic ai --add-topic presentations --add-topic slides --add-topic html --add-topic claude-code --add-topic skill
```

### Option B: Using GitHub Website

1. Go to https://github.com/new
2. Fill in the details:
   - **Repository name**: `ai-slides`
   - **Description**: `AI-powered skill for creating stunning HTML presentations with intelligent content optimization, premium themes, and zero dependencies`
   - **Visibility**: Public
   - **DO NOT** initialize with README, .gitignore, or license (we already have these)
3. Click "Create repository"

4. Connect your local repository:

```bash
# Replace YOUR_USERNAME with your GitHub username
git remote add origin https://github.com/YOUR_USERNAME/ai-slides.git
git branch -M main
git push -u origin main
```

## Step 3: Configure Repository Settings

On GitHub, go to your repository settings:

### Topics (Tags)
Add these topics to help people discover your repo:
- `ai`
- `presentations`
- `slides`
- `html`
- `claude-code`
- `skill`
- `zero-dependencies`
- `presentation-generator`

### About Section
- Description: "AI-powered skill for creating stunning HTML presentations"
- Website: (optional - add if you have a demo site)
- Check "Releases" and "Packages"

### Social Preview
Upload a preview image (optional):
- Recommended size: 1280×640px
- Could be a screenshot of a sample presentation

## Step 4: Create Initial Release

```bash
# Create a tag for v1.0.0
git tag -a v1.0.0 -m "Release v1.0.0: Initial public release"
git push origin v1.0.0
```

Or use GitHub CLI:

```bash
gh release create v1.0.0 --title "v1.0.0 - Initial Release" --notes "
# AI Slides v1.0.0

First public release of AI Slides - an AI-powered presentation generator.

## Features
- 5 premium themes
- AI content optimization
- Zero dependencies
- Single HTML file output
- Full keyboard/touch navigation
- Accessible and responsive

## What's Included
- Complete skill documentation
- 5 theme presets
- AI prompt templates
- Real-world examples
- Sample presentations
"
```

## Step 5: Add Repository Badges (Optional)

Add these to the top of README.md:

```markdown
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub release](https://img.shields.io/github/release/YOUR_USERNAME/ai-slides.svg)](https://github.com/YOUR_USERNAME/ai-slides/releases)
[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/ai-slides.svg)](https://github.com/YOUR_USERNAME/ai-slides/stargazers)
```

## Step 6: Enable GitHub Pages (Optional)

To host sample presentations:

1. Go to Settings → Pages
2. Source: Deploy from a branch
3. Branch: `main` → `/templates/presets`
4. Save

Your samples will be available at:
`https://YOUR_USERNAME.github.io/ai-slides/sample-startup-pitch.html`

## Step 7: Set Up Issues and Discussions

### Enable Discussions
1. Go to Settings → General
2. Scroll to Features
3. Check "Discussions"

### Create Issue Templates
GitHub will auto-detect common templates, or create custom ones:

```bash
mkdir -p .github/ISSUE_TEMPLATE
```

## Verification Checklist

- [ ] Repository is public
- [ ] README displays correctly
- [ ] License file is present
- [ ] .gitignore is working
- [ ] All documentation files are included
- [ ] Sample HTML files are accessible
- [ ] Topics/tags are added
- [ ] Description is set
- [ ] Initial release is created

## Sharing Your Repository

Share your repo with:

```
https://github.com/YOUR_USERNAME/ai-slides
```

Or create a short link:
```
git.io/ai-slides (if available)
```

## Maintenance

### Updating the Repository

```bash
# Make changes
git add .
git commit -m "Description of changes"
git push origin main
```

### Creating New Releases

```bash
# Tag the release
git tag -a v1.1.0 -m "Release v1.1.0: New features"
git push origin v1.1.0

# Create release on GitHub
gh release create v1.1.0 --title "v1.1.0" --notes "Release notes here"
```

## Troubleshooting

**Push rejected?**
```bash
git pull origin main --rebase
git push origin main
```

**Large files?**
Ensure sample HTML files are under 100MB (they should be <150KB)

**Authentication issues?**
```bash
gh auth login
# or use SSH keys
```

## Next Steps

1. Star your own repo (to show it's active)
2. Share on social media
3. Submit to awesome lists
4. Write a blog post
5. Create demo videos
6. Engage with users who open issues

---

**Your repository is now live!** 🎉

Share it with the world and start accepting contributions.

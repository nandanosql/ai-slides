# Quick GitHub Setup Commands

Copy and paste these commands to set up your repository.

## 1. Initialize and Commit

```bash
cd /Users/nandan/Downloads/newskills/ai-slides
git init
git add .
git commit -m "Initial commit: AI Slides - Next-generation slide generator"
```

## 2. Create Repository on GitHub

### Option A: Using GitHub CLI (Easiest)

```bash
# Login (if needed)
gh auth login

# Create and push repository
gh repo create ai-slides \
  --public \
  --source=. \
  --remote=origin \
  --push \
  --description "AI-powered skill for creating stunning HTML presentations with intelligent content optimization, premium themes, and zero dependencies"

# Add topics
gh repo edit --add-topic ai
gh repo edit --add-topic presentations
gh repo edit --add-topic slides
gh repo edit --add-topic html
gh repo edit --add-topic claude-code
gh repo edit --add-topic skill
```

### Option B: Manual Setup

```bash
# Create repo on GitHub website first, then:
git remote add origin https://github.com/YOUR_USERNAME/ai-slides.git
git branch -M main
git push -u origin main
```

## 3. Create First Release

```bash
git tag -a v1.0.0 -m "Release v1.0.0: Initial public release"
git push origin v1.0.0

gh release create v1.0.0 \
  --title "v1.0.0 - Initial Release" \
  --notes "First public release of AI Slides with 5 premium themes, AI content optimization, and zero dependencies."
```

## 4. Verify

```bash
# Check remote
git remote -v

# Check status
git status

# View on GitHub
gh repo view --web
```

## Done! 🎉

Your repository is now live at:
`https://github.com/YOUR_USERNAME/ai-slides`

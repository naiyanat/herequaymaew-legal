# HereQuayMaew Channel - Legal Pages

Terms of Service and Privacy Policy pages for TikTok OAuth app registration.

## 📋 Information

- **App Name:** HereQuayMaew Channel
- **Developer:** ฮคม
- **Contact:** e.aoymam.app@gmail.com

## 🚀 Setup GitHub Pages

### Step 1: Create GitHub Repository

1. Go to https://github.com/new
2. Create a new repository:
   - **Name:** `herequaymaew-legal` (or any name you prefer)
   - **Visibility:** Public
   - **Initialize:** Don't add README, .gitignore, or license

### Step 2: Push Files to GitHub

```bash
cd ~/clawd/herequaymaew-legal

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial commit: Terms of Service and Privacy Policy"

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/herequaymaew-legal.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/ (root)`
5. Click **Save**

### Step 4: Wait for Deployment

- GitHub will deploy your site (usually takes 1-2 minutes)
- Your URLs will be:
  - **Homepage:** `https://YOUR_USERNAME.github.io/herequaymaew-legal/`
  - **Terms:** `https://YOUR_USERNAME.github.io/herequaymaew-legal/terms-of-service.html`
  - **Privacy:** `https://YOUR_USERNAME.github.io/herequaymaew-legal/privacy-policy.html`

### Step 5: Use URLs in TikTok OAuth Registration

Copy the URLs above and paste them into:
- **Terms of Service URL:** `https://YOUR_USERNAME.github.io/herequaymaew-legal/terms-of-service.html`
- **Privacy Policy URL:** `https://YOUR_USERNAME.github.io/herequaymaew-legal/privacy-policy.html`

## 📝 Files Included

- `index.html` - Homepage with links to legal pages
- `terms-of-service.html` - Terms of Service
- `privacy-policy.html` - Privacy Policy
- `README.md` - This file (setup instructions)

## 🎨 Design

- Clean, modern design
- Mobile-responsive
- Purple gradient theme
- Easy to read and navigate

## ✏️ Updating Content

To update any page:

1. Edit the HTML files locally
2. Commit and push changes:
   ```bash
   git add .
   git commit -m "Update content"
   git push
   ```
3. GitHub Pages will automatically redeploy (1-2 minutes)

---

**Developer:** ฮคม  
**Contact:** e.aoymam.app@gmail.com  
**Last Updated:** January 29, 2026

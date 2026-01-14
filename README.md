# Rewind Privacy Policy - GitHub Pages

This repository contains the Privacy Policy for the Rewind mobile app.

## 🚀 Deployment Instructions

### Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** button in the top right → **"New repository"**
3. Name it: `rewind-privacy-policy` (or any name you prefer)
4. Make it **Public** (required for GitHub Pages)
5. Don't add README, .gitignore, or license (we already have files)
6. Click **"Create repository"**

### Step 2: Push These Files to GitHub

Open Terminal and run these commands from this directory:

```bash
# Navigate to this directory
cd /Users/brennenstudenc/Desktop/Rewind/privacy-policy

# Initialize git repository
git init

# Add all files
git add .

# Commit the files
git commit -m "Add privacy policy for Rewind app"

# Add your GitHub repository as remote (replace with your actual URL)
git remote add origin https://github.com/YOUR_USERNAME/rewind-privacy-policy.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** tab
3. Scroll down to **"Pages"** in the left sidebar
4. Under "Source", select **"main"** branch
5. Keep folder as **"/ (root)"**
6. Click **"Save"**
7. Wait 2-3 minutes for deployment

### Step 4: Get Your Privacy Policy URL

Your privacy policy will be available at:
```
https://YOUR_USERNAME.github.io/rewind-privacy-policy/
```

For example:
```
https://bstudenc.github.io/rewind-privacy-policy/
```

### Step 5: Use This URL in Your App

Add this URL to:
- ✅ App Store Connect (Privacy Policy URL field)
- ✅ Your app's settings/about screen
- ✅ Your app's authentication screen
- ✅ Terms of Service document

---

## 📝 Alternative: Use a Custom Domain (Optional)

If you have a custom domain (like `rewindapp.com`):

1. In GitHub Pages settings, add your custom domain
2. Create a `CNAME` file with your domain
3. Update your DNS settings with GitHub's IPs
4. Your privacy policy will be at: `https://rewindapp.com/privacy`

---

## 🔄 Updating the Privacy Policy

To update the policy in the future:

```bash
# Navigate to directory
cd /Users/brennenstudenc/Desktop/Rewind/privacy-policy

# Edit index.html with your changes

# Commit and push
git add .
git commit -m "Update privacy policy - [describe changes]"
git push

# Changes will be live in 1-2 minutes
```

---

## ✅ Checklist

- [ ] Create GitHub repository
- [ ] Push files to GitHub
- [ ] Enable GitHub Pages
- [ ] Verify policy is live at your URL
- [ ] Add URL to App Store Connect
- [ ] Add link in app settings screen
- [ ] Add link on login/signup screen

---

## 📧 Contact

For questions about this privacy policy:
- Email: Bstudenc@gmail.com
- Company: Invictus Reserve

---

## 📄 Files in This Repository

- `index.html` - The privacy policy HTML page
- `style.css` - Styling for the policy page
- `README.md` - This file with deployment instructions

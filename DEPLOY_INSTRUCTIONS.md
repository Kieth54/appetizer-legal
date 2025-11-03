# 🚀 Deploy to GitHub Pages - Step by Step

## ✅ Files Ready
- privacy.html ✅
- support.html ✅
- terms.html ✅
- Email updated to: thabanichaka@gmail.com ✅

---

## 📋 Deployment Steps

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com)
2. Click **"New repository"** (green button)
3. Repository name: `appetizer-legal`
4. Description: `Legal pages for Appetizer app`
5. **Public** (must be public for GitHub Pages)
6. ✅ Check "Add a README file"
7. Click **"Create repository"**

---

### Step 2: Upload Files

**Option A: Via GitHub Website (Easiest)**

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop these 3 files:
   - `privacy.html`
   - `support.html`
   - `terms.html`
3. Commit message: "Add legal pages"
4. Click **"Commit changes"**

**Option B: Via Git Command Line**

```bash
cd c:\Users\thaba\backup\Appetizer\web

# Initialize git (if not already)
git init

# Add files
git add privacy.html support.html terms.html

# Commit
git commit -m "Add legal pages"

# Add remote (replace YOUR_USERNAME with your GitHub username)
git remote add origin https://github.com/YOUR_USERNAME/appetizer-legal.git

# Push
git branch -M main
git push -u origin main
```

---

### Step 3: Enable GitHub Pages

1. In your repository, click **"Settings"** (gear icon)
2. Scroll down to **"Pages"** in the left sidebar
3. Under **"Source"**:
   - Branch: **main**
   - Folder: **/ (root)**
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

---

### Step 4: Get Your URLs

After deployment, your pages will be available at:

```
https://YOUR_USERNAME.github.io/appetizer-legal/privacy.html
https://YOUR_USERNAME.github.io/appetizer-legal/support.html
https://YOUR_USERNAME.github.io/appetizer-legal/terms.html
```

**Replace `YOUR_USERNAME` with your actual GitHub username!**

---

### Step 5: Test Your Pages

1. Open each URL in your browser
2. Check on mobile (iPhone Safari)
3. Verify all links work
4. Verify email links open mail app

---

### Step 6: Add to App Store Connect

1. Go to [App Store Connect](https://appstoreconnect.apple.com)
2. **My Apps** → **Appetizer**
3. **App Information** section
4. Add URLs:
   - **Privacy Policy URL**: `https://YOUR_USERNAME.github.io/appetizer-legal/privacy.html`
   - **Support URL**: `https://YOUR_USERNAME.github.io/appetizer-legal/support.html`
5. Click **"Save"**

---

## 🎯 Quick Commands (If Using Git)

```bash
# Navigate to web folder
cd c:\Users\thaba\backup\Appetizer\web

# Initialize and push
git init
git add privacy.html support.html terms.html
git commit -m "Add legal pages"
git remote add origin https://github.com/YOUR_USERNAME/appetizer-legal.git
git branch -M main
git push -u origin main
```

---

## ✅ Verification Checklist

After deployment:

- [ ] Privacy page loads: `https://YOUR_USERNAME.github.io/appetizer-legal/privacy.html`
- [ ] Support page loads: `https://YOUR_USERNAME.github.io/appetizer-legal/support.html`
- [ ] Terms page loads: `https://YOUR_USERNAME.github.io/appetizer-legal/terms.html`
- [ ] Pages look good on mobile
- [ ] Email links work (open mail app)
- [ ] URLs added to App Store Connect
- [ ] URLs saved in App Store Connect

---

## 🔧 Troubleshooting

### "404 Not Found"
- Wait 2-3 minutes after enabling Pages
- Check that files are in the root of the repository
- Verify Pages is enabled in Settings

### "Page doesn't load"
- Check your GitHub username in the URL
- Make sure repository is public
- Clear browser cache

### "Need to update content"
- Edit files on GitHub directly
- Or push changes via git
- Pages update automatically in 1-2 minutes

---

## 📝 Example URLs

If your GitHub username is `thabani`:

```
https://thabani.github.io/appetizer-legal/privacy.html
https://thabani.github.io/appetizer-legal/support.html
https://thabani.github.io/appetizer-legal/terms.html
```

---

## 🎉 You're Done!

Once deployed and added to App Store Connect, you're ready to submit your app!

**Next steps**:
1. Deploy pages to GitHub ✅
2. Add URLs to App Store Connect ✅
3. Continue with TestFlight submission ✅

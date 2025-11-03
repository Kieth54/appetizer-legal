# Appetizer Legal Pages

This folder contains the required legal pages for App Store submission.

## 📄 Pages Included

1. **privacy.html** - Privacy Policy
2. **support.html** - Support Page
3. **terms.html** - Terms of Service

## 🚀 How to Host These Pages

### Option 1: GitHub Pages (Free & Easy)

1. **Create a GitHub repository**:
   ```bash
   git init
   git add web/
   git commit -m "Add legal pages"
   git remote add origin https://github.com/YOUR_USERNAME/appetizer-legal.git
   git push -u origin main
   ```

2. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Source: Deploy from branch
   - Branch: main
   - Folder: /web
   - Save

3. **Your URLs will be**:
   ```
   https://YOUR_USERNAME.github.io/appetizer-legal/privacy.html
   https://YOUR_USERNAME.github.io/appetizer-legal/support.html
   https://YOUR_USERNAME.github.io/appetizer-legal/terms.html
   ```

---

### Option 2: Netlify (Free & Fast)

1. **Install Netlify CLI**:
   ```bash
   npm install -g netlify-cli
   ```

2. **Deploy**:
   ```bash
   cd web
   netlify deploy
   ```

3. **Follow prompts**:
   - Create & configure a new site
   - Deploy directory: . (current directory)

4. **Your URLs will be**:
   ```
   https://YOUR_SITE.netlify.app/privacy.html
   https://YOUR_SITE.netlify.app/support.html
   https://YOUR_SITE.netlify.app/terms.html
   ```

---

### Option 3: Vercel (Free & Fast)

1. **Install Vercel CLI**:
   ```bash
   npm install -g vercel
   ```

2. **Deploy**:
   ```bash
   cd web
   vercel
   ```

3. **Your URLs will be**:
   ```
   https://YOUR_PROJECT.vercel.app/privacy.html
   https://YOUR_PROJECT.vercel.app/support.html
   https://YOUR_PROJECT.vercel.app/terms.html
   ```

---

### Option 4: Custom Domain

If you have a domain (e.g., appetizer-app.com):

1. **Use any hosting provider**:
   - GitHub Pages (with custom domain)
   - Netlify (with custom domain)
   - Vercel (with custom domain)
   - Traditional web hosting

2. **Upload files** to your hosting

3. **Your URLs will be**:
   ```
   https://appetizer-app.com/privacy.html
   https://appetizer-app.com/support.html
   https://appetizer-app.com/terms.html
   ```

---

## ✏️ Before Deploying - Update These

### In all files, update:

1. **Email addresses**:
   - `support@appetizer-app.com` → Your actual support email
   - `privacy@appetizer-app.com` → Your actual privacy email
   - `legal@appetizer-app.com` → Your actual legal email
   - `feedback@appetizer-app.com` → Your actual feedback email
   - `bugs@appetizer-app.com` → Your actual bugs email

2. **Website URL**:
   - `appetizer-app.com` → Your actual domain

3. **Mailing Address** (in privacy.html):
   - Add your actual physical address (required for App Store)

4. **Governing Law** (in terms.html):
   - Update `[Your State/Country]` to your jurisdiction

---

## 📱 Add URLs to App Store Connect

Once deployed, add these URLs to your App Store listing:

1. **App Store Connect** → **My Apps** → **Appetizer**

2. **App Information**:
   - Privacy Policy URL: `https://YOUR_DOMAIN/privacy.html`
   - Support URL: `https://YOUR_DOMAIN/support.html`

3. **App Review Information**:
   - Support URL: `https://YOUR_DOMAIN/support.html`

---

## ✅ Verification Checklist

Before submitting to App Store:

- [ ] All pages are accessible online
- [ ] URLs work on mobile devices
- [ ] Email addresses are correct
- [ ] Physical address is added (privacy.html)
- [ ] Governing law is specified (terms.html)
- [ ] Pages load quickly
- [ ] No broken links
- [ ] Responsive design works on iPhone

---

## 🎨 Customization

Feel free to customize:
- Colors (update CSS)
- Logo emoji (🍳)
- Contact information
- Additional FAQ items
- Company information

---

## 📝 Notes

- **Privacy Policy**: Required by Apple for App Store submission
- **Support Page**: Required by Apple for App Store submission
- **Terms of Service**: Recommended (protects you legally)

All pages are:
- ✅ Mobile-responsive
- ✅ Clean, professional design
- ✅ Easy to read
- ✅ Apple-style aesthetics
- ✅ No external dependencies (pure HTML/CSS)

---

## 🆘 Need Help?

If you need help deploying:
1. Choose GitHub Pages (easiest)
2. Follow the instructions above
3. Test URLs before submitting to App Store

---

## 📄 License

These pages are part of your Appetizer app. Customize as needed for your business.

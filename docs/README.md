# ParkPinner Support Page

This is the official support page for ParkPinner iOS app.

## 🚀 How to Publish to GitHub Pages

### Step 1: Push to GitHub

If you haven't already, initialize git and push to GitHub:

```bash
cd /Users/metinozkan/Desktop/Apexify/ParkSnap/parksnap

# Initialize git (if not already done)
git init

# Add all files
git add .

# Commit
git commit -m "Add support page"

# Create GitHub repository first, then:
git remote add origin https://github.com/YOUR-USERNAME/parkpinner.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your GitHub repository
2. Click **Settings** (top right)
3. Scroll down to **Pages** (left sidebar)
4. Under **Source**, select:
   - Branch: `main`
   - Folder: `/docs`
5. Click **Save**

### Step 3: Get Your URL

After a few minutes, your support page will be live at:

```
https://YOUR-USERNAME.github.io/parkpinner/
```

This is the URL you'll use for your App Store support link!

## 📝 Alternative: Quick Upload Method

If you don't want to use git:

1. Go to GitHub.com
2. Create a new repository called "parkpinner-support"
3. Upload the `index.html` file
4. Enable GitHub Pages in Settings → Pages
5. Your URL will be: `https://YOUR-USERNAME.github.io/parkpinner-support/`

## ✏️ Customization

To customize the support page:

1. Open `docs/index.html` in any text editor
2. Edit the content as needed
3. Save and push to GitHub
4. Changes will appear within a few minutes

## 🔗 Use in App Store Connect

Once published, use this URL in App Store Connect:

```
Support URL: https://YOUR-USERNAME.github.io/parkpinner/
```

---

**Contact:** apexifylabs@gmail.com

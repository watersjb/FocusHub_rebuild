# 🚀 GitHub + One-Click Deploy Instructions

## Step 1: Upload to GitHub (2 minutes)

### Option A: GitHub Web Interface (Easiest)

1. Go to https://github.com/new
2. Create a new repository:
   - Name: `focushub` (or whatever you want)
   - Description: "FocusHub productivity app"
   - Public or Private (your choice)
   - **Don't** initialize with README (we already have one)
3. Click "Create repository"
4. On the next page, look for "uploading an existing file"
5. Click that link
6. Drag ALL files from the `focushub-build` folder into the upload area
   - Make sure you drag everything (index.html, assets folder, all SVGs, etc.)
7. Scroll down and click "Commit changes"

**Done! Your repo is ready.**

### Option B: GitHub Desktop (If you prefer)

1. Download GitHub Desktop from https://desktop.github.com
2. Create new repository
3. Copy all files from `focushub-build` into the repo folder
4. Commit and push

---

## Step 2: One-Click Deploy (30 seconds)

Once your files are on GitHub, deployment is literally one click:

### Deploy to Netlify (Recommended)

1. Go to your GitHub repo page
2. Click the "Deploy to Netlify" button in the README
3. Netlify will ask you to authorize GitHub (click yes)
4. Click "Deploy site"
5. Wait 30 seconds
6. Get your live URL: `https://focushub-[random].netlify.app`

**That's it. Your app is live.**

### OR Deploy to Render

1. Click the "Deploy to Render" button
2. Connect your GitHub account
3. Select the repo
4. Click "Create Static Site"
5. Wait for build to complete
6. Get your live URL

---

## Step 3: Custom Domain (Optional)

### If you want `focushub.com` instead of `focushub-random.netlify.app`:

**On Netlify:**
1. Go to Site Settings → Domain Management
2. Click "Add custom domain"
3. Enter your domain (e.g., `focushub.com`)
4. Follow DNS instructions
5. Done

**On Render:**
1. Go to Settings → Custom Domains
2. Add your domain
3. Update DNS records as shown
4. Done

---

## What to Upload to GitHub

Make sure ALL of these files are uploaded:

```
✅ index.html
✅ assets/ (entire folder with both files inside)
✅ logo.svg
✅ favicon.svg
✅ FocusHub_horiinv.svg
✅ FocusHub_horinorm.svg
✅ FocusHub_vertinv.svg
✅ FocusHub_vertnorm.svg
✅ netlify.toml
✅ README.md
✅ .gitignore
✅ All other .md files (optional but recommended)
```

---

## Troubleshooting

**"Deploy to Netlify" button doesn't work:**
- Make sure you've uploaded ALL files to GitHub first
- The button won't work until files are on GitHub
- Alternative: Go to https://app.netlify.com, click "Add new site", select your repo

**Files won't upload:**
- Try uploading folders separately
- Or use GitHub Desktop
- Or drag files 5-10 at a time

**Deployment fails:**
- Check that `index.html` is in the root (not in a subfolder)
- Check that `assets/` folder uploaded correctly
- Check Netlify/Render build logs for errors

**App shows blank page after deploy:**
- Check browser console (F12)
- Verify all files uploaded
- Check that paths in index.html match your file structure

---

## After Deployment

Once your app is live:

1. **Test it:** Go through all features
2. **Bookmark it:** Save the URL
3. **Share it:** Send to colleagues/friends
4. **Use it:** Start your first sprint

---

## Video Tutorial (If Needed)

If you get stuck, search YouTube for:
- "How to upload files to GitHub"
- "Deploy static site to Netlify"

These are very common tasks with thousands of tutorials.

---

## Still Stuck?

If you can't get it working:

1. Upload files to GitHub (that's the hardest part)
2. Send me the GitHub repo URL
3. I'll check what's wrong

But honestly, it's just:
1. Upload files to GitHub
2. Click deploy button
3. Wait 30 seconds
4. Done

You've got this. 🚀

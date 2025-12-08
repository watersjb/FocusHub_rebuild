# ✅ GitHub Upload Checklist

Before you click "Deploy", make sure these files are on GitHub:

## Core Files
- [ ] `index.html` - Main app file
- [ ] `assets/index-[hash].js` - JavaScript bundle
- [ ] `assets/index-[hash].css` - Styles

## Branding Assets
- [ ] `logo.svg` - Header logo (white)
- [ ] `favicon.svg` - Browser icon
- [ ] `FocusHub_horiinv.svg` - White horizontal
- [ ] `FocusHub_horinorm.svg` - Black horizontal
- [ ] `FocusHub_vertinv.svg` - White vertical
- [ ] `FocusHub_vertnorm.svg` - Black vertical

## Configuration
- [ ] `netlify.toml` - Netlify settings
- [ ] `render.yaml` - Render settings
- [ ] `.gitignore` - Git ignore rules

## Documentation (Optional)
- [ ] `README.md` - Main readme with deploy buttons
- [ ] `DEPLOY.md` - Deployment guide
- [ ] `GITHUB-DEPLOY.md` - GitHub instructions
- [ ] `QUICKSTART.md` - Quick reference
- [ ] `BRANDING.md` - Logo info
- [ ] `TECHNICAL.md` - Technical docs
- [ ] `CHECKLIST.md` - Feature checklist

---

## How to Verify

After uploading, your GitHub repo should look like this:

```
your-username/focushub
├── index.html
├── assets/
│   ├── index-[hash].js
│   └── index-[hash].css
├── logo.svg
├── favicon.svg
├── FocusHub_horiinv.svg
├── FocusHub_horinorm.svg
├── FocusHub_vertinv.svg
├── FocusHub_vertnorm.svg
├── netlify.toml
├── render.yaml
├── .gitignore
└── [various .md files]
```

**Key check:** Can you see `index.html` in the root when you open your repo on GitHub?

If yes → You're ready to deploy!

---

## Common Mistakes to Avoid

❌ **Don't do this:**
- Upload files inside a subfolder
- Only upload some files
- Skip the `assets/` folder
- Rename files

✅ **Do this:**
- Upload ALL files to the root level
- Keep folder structure intact
- Keep original filenames
- Include the `assets/` folder with both files inside

---

## After Upload

1. Go to your repo URL: `github.com/your-username/focushub`
2. Click on `README.md` to view it
3. Scroll down to see the deploy buttons
4. Click "Deploy to Netlify"
5. Wait 30 seconds
6. Get your live URL

**That's it!**

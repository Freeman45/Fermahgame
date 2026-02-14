# 🚀 Quick Deployment Guide

## Deploy Your Fermah Game in 5 Minutes!

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `fermah-game` (or any name)
3. Keep it **Public** (required for free GitHub Pages)
4. ❌ **Don't** check "Add a README file"
5. Click "Create repository"

### Step 2: Upload Game Files
1. You'll see "Quick setup" page
2. Click **"uploading an existing file"**
3. Drag and drop **both files**:
   - `index.html` (the game)
   - `README.md` (documentation)
4. Add commit message: "Add Fermah ZK Proof Matchmaker game"
5. Click **"Commit changes"**

### Step 3: Enable GitHub Pages
1. Click **"Settings"** tab (top of page)
2. Scroll down left sidebar to **"Pages"**
3. Under "Source":
   - Branch: Select **main**
   - Folder: Select **/ (root)**
4. Click **"Save"**
5. Wait 1-2 minutes for deployment

### Step 4: Access Your Game! 🎮
Your game is now live at:
```
https://YOUR-USERNAME.github.io/fermah-game
```

**Example**: If your username is `john`, the URL will be:
```
https://john.github.io/fermah-game
```

---

## Alternative: Using Git Command Line

If you prefer using terminal/command line:

```bash
# Navigate to where you want the project
cd ~/projects

# Create new directory
mkdir fermah-game
cd fermah-game

# Initialize git
git init

# Copy your files here (index.html and README.md)
# Then:

git add .
git commit -m "Initial commit: Fermah ZK Proof Matchmaker"

# Add your GitHub repo as remote
git remote add origin https://github.com/YOUR-USERNAME/fermah-game.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then follow **Step 3** above to enable GitHub Pages.

---

## 🎯 Pro Tips

### Custom Domain (Optional)
Want your game at `game.yourdomain.com`?
1. Add CNAME file with your domain
2. Configure DNS at your domain provider
3. Update GitHub Pages settings

### Share Your Game
After deployment, share your game:
- Tweet it to [@fermah_xyz](https://twitter.com/fermah_xyz)
- Share on Discord/Telegram
- Post on Reddit (r/cryptography, r/ethereum)

### Make It Better
Fork and improve:
- Add more ZK proof types
- Create new levels
- Add sound effects
- Build a leaderboard

---

## 📱 Testing

Test on multiple devices:
- Desktop browsers (Chrome, Firefox, Safari, Edge)
- Mobile (iOS Safari, Chrome Mobile)
- Tablet (iPad, Android tablets)

The game is fully responsive and works on all screen sizes!

---

## ⚠️ Troubleshooting

**Game not loading?**
- Make sure file is named `index.html` (not `fermah-game.html`)
- Wait 2-3 minutes after enabling Pages
- Check Settings → Pages for deployment status
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

**404 Error?**
- Verify repository is Public
- Check that GitHub Pages is enabled
- Confirm branch is set to "main"

**Styling looks broken?**
- Check browser console for errors (F12)
- Ensure you uploaded the complete HTML file
- Try different browser

---

## 🎊 Success!

Your Fermah game is now live! 

Next steps:
1. Play and test the game
2. Share with friends
3. Contribute improvements
4. Learn more about Fermah at [fermah.xyz](https://fermah.xyz)

**Happy Proving!** 🌙⚡

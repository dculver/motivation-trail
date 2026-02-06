# GitHub Pages Setup Instructions

Follow these steps to host The Motivation Trail game on GitHub Pages (it's free and takes about 5 minutes!).

## Step 1: Create a GitHub Account (if you don't have one)

1. Go to https://github.com
2. Click "Sign up"
3. Follow the registration process

## Step 2: Create a New Repository

1. Once logged in, click the **"+"** icon in the top-right corner
2. Select **"New repository"**
3. Name your repository: `motivation-trail` (or any name you prefer)
4. **Important:** Make sure it's set to **Public**
5. Check the box **"Add a README file"** (this will be replaced)
6. Click **"Create repository"**

## Step 3: Upload Your Files

1. In your new repository, click **"Add file"** → **"Upload files"**
2. Drag and drop ALL THREE files from the `github-pages-files` folder:
   - `index.html` (the game)
   - `share.html` (QR code page)
   - `README.md` (description)
3. Scroll down and click **"Commit changes"**

## Step 4: Enable GitHub Pages

1. In your repository, click **"Settings"** (top menu)
2. In the left sidebar, click **"Pages"**
3. Under "Source", select **"Deploy from a branch"**
4. Under "Branch", select **"main"** and **"/ (root)"**
5. Click **"Save"**

## Step 5: Wait a Minute and Get Your URL

1. GitHub will take 1-2 minutes to build your site
2. Refresh the Settings → Pages page
3. You'll see a message: **"Your site is live at https://YOUR-USERNAME.github.io/motivation-trail/"**
4. Click that URL to see your game!

## Step 6: Create and Share Your QR Code

1. Go to your game URL and add `/share.html` to the end:
   - Example: `https://YOUR-USERNAME.github.io/motivation-trail/share.html`
2. This page will automatically generate a QR code for your game
3. You can:
   - Print it for handouts
   - Download it as PNG
   - Share the URL with students

## Your Final URLs

After setup, you'll have:

- **Game**: `https://YOUR-USERNAME.github.io/motivation-trail/`
- **QR Code Page**: `https://YOUR-USERNAME.github.io/motivation-trail/share.html`

## Updating the Game

If you want to update the game later:

1. Go to your repository
2. Click on `index.html`
3. Click the pencil icon (Edit)
4. Make your changes
5. Click "Commit changes"

The site will automatically update in 1-2 minutes!

## Troubleshooting

**"Page not found" error?**
- Wait a few minutes after enabling GitHub Pages
- Check that you selected "main" branch in Pages settings
- Make sure your repository is Public

**QR code not working?**
- Make sure you're using the full URL from share.html
- Test the URL in a browser first

**Want a custom domain?**
- In Settings → Pages, you can add a custom domain
- Follow GitHub's instructions for DNS setup

## Need Help?

- GitHub Pages Documentation: https://docs.github.com/en/pages
- GitHub Support: https://support.github.com

---

**That's it!** Your game is now live on the internet and anyone can play it by scanning your QR code or visiting your URL. 🎓✨

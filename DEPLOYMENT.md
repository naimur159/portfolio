# 🚀 GitHub Pages Deployment Guide

This guide will walk you through deploying your portfolio website to GitHub Pages for free hosting.

## Prerequisites

- A GitHub account
- Git installed on your computer
- Your portfolio files ready

## Step-by-Step Deployment

### 1. Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository: `portfolio` (or any name you prefer)
5. Make it **Public** (required for free GitHub Pages)
6. **Don't** initialize with README (since you already have files)
7. Click "Create repository"

### 2. Upload Your Files

#### Option A: Using Git (Recommended)

Open your terminal/command prompt and navigate to your portfolio folder:

```bash
# Navigate to your portfolio directory
cd path/to/your/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit your files
git commit -m "Initial portfolio commit"

# Add the remote repository (replace 'yourusername' with your GitHub username)
git remote add origin https://github.com/yourusername/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

#### Option B: Using GitHub Web Interface

1. Go to your new repository on GitHub
2. Click "uploading an existing file"
3. Drag and drop all your portfolio files (`index.html`, `styles.css`, `script.js`, `README.md`)
4. Click "Commit changes"

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main" and click "Save"
6. Wait a few minutes for your site to deploy

### 4. Access Your Live Site

Your portfolio will be available at:
```
https://yourusername.github.io/portfolio
```

Replace `yourusername` with your actual GitHub username and `portfolio` with your repository name.

## Custom Domain (Optional)

If you want to use a custom domain:

1. In your repository settings → Pages
2. Under "Custom domain", enter your domain name
3. Click "Save"
4. Add a CNAME file to your repository with your domain name
5. Configure your domain's DNS settings

## Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after enabling GitHub Pages
- Check that your repository is public
- Ensure `index.html` is in the root directory

### Styling Issues
- Check that all file paths are correct
- Ensure CSS and JS files are properly linked
- Clear your browser cache

### 404 Errors
- Make sure all file names match exactly (case-sensitive)
- Check that `index.html` is named correctly

## Updating Your Site

To update your portfolio:

```bash
# Make your changes to the files
# Then commit and push:
git add .
git commit -m "Update portfolio content"
git push
```

Your site will automatically update within a few minutes.

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minify Code**: Use minified versions of CSS/JS for production
3. **Use CDN**: External libraries are already loaded from CDN
4. **Check Mobile**: Test your site on mobile devices

## Analytics (Optional)

To add Google Analytics:

1. Go to [Google Analytics](https://analytics.google.com)
2. Create a new property
3. Get your tracking ID
4. Add this code to your `index.html` before the closing `</head>` tag:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_TRACKING_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_TRACKING_ID');
</script>
```

Replace `GA_TRACKING_ID` with your actual tracking ID.

## Security Considerations

- Keep your repository public (required for GitHub Pages)
- Don't include sensitive information in your code
- Use environment variables for any API keys (if needed)

## Support

If you encounter issues:

1. Check GitHub's [Pages documentation](https://pages.github.com/)
2. Verify your repository settings
3. Check the repository's "Actions" tab for deployment status
4. Look for error messages in the browser console

---

**🎉 Congratulations!** Your portfolio is now live and accessible to the world! 
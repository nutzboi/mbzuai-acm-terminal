# GitHub Pages Deployment Guide

## Quick Deployment Steps

### 1. Create GitHub Repository
1. Go to [GitHub](https://github.com) and create a new repository
2. Name it `mbzuai-acm-terminal` (or your preferred name)
3. Make it public for free GitHub Pages hosting

### 2. Upload Files
1. Upload all files from this directory to your GitHub repository:
   - `index.html`
   - `react.development.js`
   - `react-dom.development.js`
   - `README.md`
   - `LICENSE`
   - `.nojekyll`
   - `_config.yml`

### 3. Enable GitHub Pages
1. Go to your repository on GitHub
2. Click on **Settings** tab
3. Scroll down to **Pages** section
4. Under **Source**, select **Deploy from a branch**
5. Choose **main** branch and **/ (root)** folder
6. Click **Save**

### 4. Access Your Site
- Your site will be available at: `https://yourusername.github.io/mbzuai-acm-terminal`
- It may take a few minutes to deploy initially

## File Structure for GitHub Pages

```
mbzuai-acm-terminal/
├── index.html              # Main application
├── react.development.js    # React library
├── react-dom.development.js # React DOM library
├── README.md              # Project documentation
├── LICENSE                # License file
├── .nojekyll             # Disable Jekyll processing
├── _config.yml           # Jekyll configuration
└── DEPLOYMENT.md         # This file
```

## Important Notes

- **`.nojekyll` file**: This tells GitHub Pages not to process files with Jekyll, which is important for our React app
- **All files are in root**: GitHub Pages will serve `index.html` as the main page
- **No build process needed**: The app works directly in the browser
- **HTTPS enabled**: GitHub Pages automatically provides HTTPS

## Custom Domain (Optional)

If you want to use a custom domain:
1. Add a `CNAME` file with your domain name
2. Configure DNS settings to point to GitHub Pages
3. Enable custom domain in repository settings

## Troubleshooting

- **404 Error**: Make sure `index.html` is in the root directory
- **Files not loading**: Check that all JavaScript files are uploaded
- **Styling issues**: Ensure TailwindCSS CDN is accessible
- **Build failed**: Check that `.nojekyll` file exists

## Support

For issues with deployment, check:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Pages Troubleshooting](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-github-pages)

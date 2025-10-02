# Deployment Guide

## Option 1: GitHub Pages (Free)

1. **Create a GitHub Repository**:
   - Go to GitHub.com and create a new repository
   - Name it `your-username.github.io` for personal site
   - Or any name for a project site

2. **Upload Files**:
   - Upload all files from your `my-site` folder
   - Commit and push to the main branch

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Save

4. **Access Your Site**:
   - Your site will be available at: `https://your-username.github.io/repository-name`

## Option 2: Netlify (Free)

1. **Sign up at Netlify.com**
2. **Drag and Drop**:
   - Simply drag your `my-site` folder to Netlify dashboard
   - Or connect your GitHub repository

3. **Your site is live!**
   - Netlify provides a random URL
   - You can customize the domain name

## Option 3: Vercel (Free)

1. **Sign up at Vercel.com**
2. **Import Project**:
   - Connect your GitHub account
   - Import your repository

3. **Deploy**:
   - Vercel automatically deploys your site
   - Provides a custom URL

## Option 4: Traditional Web Hosting

1. **Choose a hosting provider** (GoDaddy, Namecheap, etc.)
2. **Upload files via FTP**:
   - Use FileZilla or similar FTP client
   - Upload all files to the public_html folder

3. **Configure domain**:
   - Point your domain to the hosting server

## Before Deploying

✅ **Checklist**:
- [ ] Add your profile photo to `assets/profile.jpg`
- [ ] Add project images to assets folder
- [ ] Update contact information with real details
- [ ] Replace placeholder social media links
- [ ] Test the website locally by opening `index.html`
- [ ] Customize project descriptions with your actual projects
- [ ] Update email addresses and phone numbers

## Testing Locally

1. **Simple Method**:
   - Double-click `index.html` to open in browser

2. **With Local Server** (recommended):
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```
   Then visit `http://localhost:8000`

## Updating Your Site

- **GitHub Pages**: Push changes to your repository
- **Netlify**: Redeploy by uploading new files or pushing to connected repo
- **Vercel**: Push to connected repository for automatic deployment
- **Traditional hosting**: Upload changed files via FTP

---

Your beautiful portfolio website is ready to go live! 🚀
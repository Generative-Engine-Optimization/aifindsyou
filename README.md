# AI Finds You - Redirect Website

A simple, elegant website that automatically redirects visitors to [RankWit AI](https://www.rankwit.ai/).

## Features

- **Instant Redirect**: Uses meta refresh for immediate redirection
- **Fallback JavaScript**: Ensures redirection even if meta refresh is disabled
- **Beautiful UI**: Modern gradient design with loading animation
- **User-Friendly**: Manual redirect link in case automatic redirect fails
- **Countdown Timer**: Shows users how long until redirect

## How to Use

Simply open `index.html` in any web browser. The page will automatically redirect to https://www.rankwit.ai/ within seconds.

## GitHub Pages Deployment

1. **Push to GitHub**: Push this repository to your GitHub account
2. **Enable GitHub Pages**: 
   - Go to Settings > Pages
   - Source: Deploy from a branch
   - Branch: `gh-pages` (will be created automatically)
   - Folder: `/ (root)`
3. **Automatic Deployment**: The GitHub Action will automatically deploy on every push to `main`

## Technical Details

- Pure HTML, CSS, and JavaScript
- No external dependencies
- Responsive design
- Works on all modern browsers
- Automatic deployment via GitHub Actions
- SEO optimized with sitemap and robots.txt

# BlueCap Landing Page

This is the landing page for BlueCap, hosted on GitHub Pages.

## Deployment Instructions

1. Push your changes to the main branch of your GitHub repository
2. Go to your repository's Settings
3. Scroll down to the "GitHub Pages" section
4. Under "Source", select "main" branch
5. Click "Save"

Your site will be published at `https://[your-username].github.io/[repository-name]`

## Custom Domain Setup

To set up your custom domain (www.bluecap.co):

1. Add a CNAME file to your repository:
   ```
   www.bluecap.co
   ```

2. Configure your domain's DNS settings:
   - Add an A record pointing to GitHub Pages IP addresses:
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```
   - Add a CNAME record pointing to `[your-username].github.io`

3. Wait for DNS propagation (can take up to 24 hours)

## Local Development

To run the site locally:
1. Clone the repository
2. Open `index.html` in your browser
3. Make changes and refresh to see updates

## Technologies Used

- HTML5
- CSS3
- Google Fonts (Inter) 
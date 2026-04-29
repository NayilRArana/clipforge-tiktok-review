# Publishing Notes

TikTok requires public URLs for:

- Web/Desktop URL
- Terms of Service URL
- Privacy Policy URL

The easiest cheap path is to publish the `submission/tiktok_review` folder as a static site.

## Low-friction options

### GitHub Pages

1. Push this repo or just this folder to GitHub.
2. Enable GitHub Pages.
3. Use:
   - homepage: `/index.html`
   - terms: `/terms.html`
   - privacy: `/privacy.html`

### Netlify Drop

1. Zip the folder.
2. Drag it onto Netlify Drop.
3. Use the generated URLs.

### Cloudflare Pages

1. Push to GitHub.
2. Connect the repo.
3. Publish the `submission/tiktok_review` directory.

## Important

The domain shown in your TikTok review demo should match the website URL you enter in the developer portal if you are demonstrating a web/desktop app.

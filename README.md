# CareerDNA OS prototype

This folder contains a deployment-ready static website for the CareerDNA OS prototype.

## Publish to GitHub Pages

1. Create a GitHub repository and upload these files.
2. In the repository settings, enable Pages.
3. Choose the GitHub Actions deployment method.
4. Set the custom domain to `careerdnaos.com`.
5. Add the DNS record for the domain provider:
   - Type: CNAME
   - Name: `www` (or root if supported)
   - Value: `<your-github-username>.github.io`

The included `CNAME` file will preserve the custom domain once the Pages site is configured.

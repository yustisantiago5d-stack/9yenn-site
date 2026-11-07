# 9yenn.com

Static site prepared for GitHub Pages. The `CNAME` file configures the custom
domain, and `.github/workflows/pages.yml` publishes the site whenever changes
are pushed to the `main` branch.

## Publish

1. Create a **public** GitHub repository and upload the contents of this folder
   to its `main` branch.
2. In the repository, open **Settings → Pages** and select **GitHub Actions**
   as the build and deployment source.
3. Configure the domain's DNS:
   - Add A records for `9yenn.com` pointing to
     `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, and
     `185.199.111.153`.
   - Optionally add a CNAME record for `www` pointing to
     `<github-username>.github.io`.
4. Wait for DNS to propagate, then enable **Enforce HTTPS** in the Pages
   settings when GitHub makes it available.

Do not post GitHub passwords or access tokens in chat. Sign in to GitHub in
your browser or GitHub Desktop to create and publish the repository.

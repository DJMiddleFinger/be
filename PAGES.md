# GitHub Pages Site Settings

## Configure Pages Deployment

1. Go to: https://github.com/DJMiddleFinger/be-pages/settings/pages
2. Under "Source", select **GitHub Actions**
3. The workflow file `.github/workflows/deploy-pages.yml` is already configured

## Next Steps

After deploying:
- GitHub will automatically deploy your site within 1-2 minutes
- Your live URL will be published at: https://DJMiddleFinger.github.io/be-pages/
- You can add a custom domain in the Pages settings if desired (e.g., bebrooklynequine.com)

## Deployment Flow

```
Main Repo (be) ──┐
                 ├── Push to main branch ───> Deploy workflow triggers
                /                              |
    Images + Content     ────────> Mirror to (be-pages)
```
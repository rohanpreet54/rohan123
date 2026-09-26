# NSRH HUB

GitHub Pages-ready deployment.

## Deploy
1. Create a GitHub repository.
2. Upload all files from this folder.
3. Go to **Settings → Pages** and select **GitHub Actions**.
4. Push to `main`. The included workflow deploys the site automatically.

This GitHub Pages build is fully client-side. Uploaded files are stored in the browser with IndexedDB, so each browser/device has its own data. The Python backend is not needed for this deployment.

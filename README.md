# Beeiman Honey — GitHub Pages

This is a ready-to-deploy static site for **bee.mohannagarden.ir**.

## How to deploy
1. Create a public repository on GitHub (e.g., `Beeiman-honey`).
2. Upload all files from this package to the **root** of the repository.
3. Go to **Settings → Pages** and set:
   - Source: `Deploy from a branch`
   - Branch: `main`, Folder: `/ (root)`
4. In **Settings → Pages → Custom domain**, set `bee.mohannagarden.ir`.
5. In your domain DNS, add a CNAME:
   - Host/Name: `bee`
   - Value: `<YOUR_GITHUB_USERNAME>.github.io`
6. Enable **Enforce HTTPS** after the certificate is issued.

## Replace placeholders
- `assets/logo.png` → your real logo
- `assets/product.jpg` → your product photo
- `assets/qr-bee.png` → optional QR image (currently a placeholder)

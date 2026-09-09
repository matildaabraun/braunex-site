# Braunex Website

Exported static site, ready for GitHub Pages.

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g. `braunex-site`)
2. Upload all files in this folder to the repository (keep the folder structure: images/, js/, services/, blog/ etc. at the root)
3. Go to repo Settings → Pages
4. Under "Source", select the `main` branch and `/ (root)` folder
5. Save — GitHub will give you a URL like `https://yourusername.github.io/braunex-site/`

## Custom domain (braunex.com)

1. In the same Settings → Pages screen, enter `braunex.com` under "Custom domain"
2. In GoDaddy DNS settings, add:
   - An A record pointing @ to GitHub's IP addresses (185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153)
   - A CNAME record pointing www to yourusername.github.io
3. Wait for DNS to propagate (can take up to 24-48 hours)

## Notes

- This is the real exported Framer output — colors, fonts, and animations are preserved as-is.
- Contact form / Cal.com embed: verify these still load correctly once live, since embeds sometimes depend on the original domain being whitelisted in Cal.com settings.

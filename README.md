
# PsyGuardianX Static Site

A dark, fast static site ready for GitHub Pages with a **Psynote** section and a **Windows installer** button.

## Deploy (GitHub Pages)
1. Create a public repo, e.g. `psyguardianx`.
2. Upload all files from this folder to the repo root.
3. In **Settings → Pages**, set Source = `main` / `(root)`.
4. In **Custom domain**, set `psyguardianx.co.za`. Keep the generated `CNAME` file.

## Windows Installer Button
- Put your installer at: `downloads/Psynote-Setup.exe`.
- The button links to `./downloads/Psynote-Setup.exe`.

## Customise
- Replace images in `./assets/` and edit copy in `index.html`.
- Colors are in `style.css`.

## DNS (GoDaddy → GitHub Pages)
Create/keep A records to these IPs:
- 185.199.108.153
- 185.199.109.153
- 185.199.110.153
- 185.199.111.153

Add a CNAME for `www` → `yourusername.github.io`.
Then in GitHub Pages, tick **Enforce HTTPS** once available.

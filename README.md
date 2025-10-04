# SkillCert — Static Cert Website

Issue certificates, verify them with QR, and let recruiters check.

## How it works

1. Use `index.html` to generate a certificate. After passing & payment, you’ll get a JSON file (e.g. `ABC12345.json`).
2. Upload that file to `/data/ABC12345.json` in your GitHub repo.
3. The link `verify.html?uid=ABC12345` will then show “Valid” with certificate details.

## Files to include

- index.html  
- verify.html  
- admin.html  
- sitemap.xml  
- README.md  
- `assets/` folder (logo.svg)  
- `data/` folder (initially empty)

## Deploy on GitHub Pages

- Push these files to your repo root.
- Go to Settings → Pages → Source: `main` branch, folder `/`.
- Visit `https://rahul-satav.github.io/SkillCert/`

## After issuing

- Upload the generated JSON file to `data/` folder.
- Shared QR / verify link becomes permanent.
- Optionally share on LinkedIn via button.

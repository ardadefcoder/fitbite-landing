# FitBite Landing Site

Static website for `fitbite.dev`, including:

- Landing page: `index.html`
- Privacy policy: `privacy.html`
- Support page: `support.html`
- Terms of Service: `terms.html`
- GitHub Pages custom domain file: `CNAME`

## Publish on GitHub Pages

1. Push these files to the `fitbite-landing` repository.
2. In GitHub, open the repository.
3. Go to **Settings > Pages**.
4. Under **Build and deployment**, choose:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
5. Under **Custom domain**, enter `fitbite.dev`.
6. Save, then enable **Enforce HTTPS** when GitHub allows it.

## Namecheap DNS Records

In Namecheap, go to **Domain List > fitbite.dev > Manage > Advanced DNS**.

Add these `A` records for the root domain:

| Type | Host | Value |
| --- | --- | --- |
| A Record | @ | 185.199.108.153 |
| A Record | @ | 185.199.109.153 |
| A Record | @ | 185.199.110.153 |
| A Record | @ | 185.199.111.153 |

Add this `CNAME` record for `www`:

| Type | Host | Value |
| --- | --- | --- |
| CNAME Record | www | YOUR-GITHUB-USERNAME.github.io |

Replace `YOUR-GITHUB-USERNAME` with your GitHub username.

DNS can take a few minutes to 24 hours. After GitHub verifies the domain, `https://fitbite.dev` should serve this site.

## App Store Connect URLs

Use these URLs in App Store Connect:

- Marketing URL: `https://fitbite.dev/`
- Privacy Policy URL: `https://fitbite.dev/privacy.html`
- Support URL: `https://fitbite.dev/support.html`
- Terms URL: `https://fitbite.dev/terms.html`

Before App Store review, update the privacy policy so it exactly matches what FitBite collects and which services it uses.
"# fitbite-landing" 

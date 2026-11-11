# Synexis Technologies — Official Website

**Brand line:** Engineered for Excellence.  
**Domain:** https://synexistech.co.zw/  
**Repository:** https://github.com/tarieciphertech/synexistech.co.zw-

## Hosting and deployment

This is a static, multi-page website hosted entirely on GitHub Pages. GitHub Actions deploys the repository root on pushes to `main`.

- No VPS or separate web-hosting server is required.
- Pages: Home, About, Services, Our Work, Contact and a custom 404.
- Shared styles and browser interactions: `assets/css/site.css` and `assets/js/site.js`.
- The company brand image is stored in the repository root.
- `CNAME` sets the custom domain.
- `robots.txt` and `sitemap.xml` provide search-engine discovery.

## GitHub configuration

1. Open **Settings → Pages**.
2. Set **Build and deployment → Source** to **GitHub Actions**.
3. Keep the custom domain as `synexistech.co.zw`.
4. Confirm the latest workflow under **Actions** completes successfully.
5. Once GitHub has issued the certificate, enable **Enforce HTTPS**.

## DNS

At the domain DNS provider, point the apex domain to GitHub Pages using these A records:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optional `www` CNAME: `tarieciphertech.github.io`.

Preserve email MX/TXT records and any records used by other active services. Do not replace existing records until their purpose is confirmed.

## Contact form limitation

The contact page currently prepares and copies an enquiry in the visitor's browser. It does **not** transmit or store form submissions. GitHub Pages only hosts static files; it does not run a server-side form handler or database. To receive enquiries automatically, the company must later choose an approved email/form provider or a separate backend. No company email address or telephone number has been invented in this site.

## Before public launch

- Confirm the final approved service descriptions and geographic/company registration wording.
- Add official company email, telephone/WhatsApp and social channels when supplied.
- Replace representative capability descriptions with approved project case studies and authorised client references.
- Test all pages on mobile and desktop.
- Verify DNS, Pages deployment and HTTPS.
- Submit the sitemap in Google Search Console after the custom domain is live.

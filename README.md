# Synexis Technologies website

Official company website for **Synexis Technologies** — *Engineered for Excellence.*

## Website

- Domain: https://synexistech.co.zw/
- Hosting target: GitHub Pages
- Source: static HTML, CSS and JavaScript
- Deployment: GitHub Actions workflow at `.github/workflows/pages.yml`

## Deploy

The workflow publishes the repository root whenever a commit is pushed to `main`, and can also be run manually from the Actions tab.

In **Settings → Pages**, select **GitHub Actions** as the build and deployment source. Keep the custom domain set to `synexistech.co.zw`.

## DNS

For the apex domain to resolve to GitHub Pages, configure the four GitHub Pages A records at the DNS provider:

- `185.199.108.153`
- `185.199.109.153`
- `185.199.110.153`
- `185.199.111.153`

Optionally point `www` to `tarieciphertech.github.io` with a CNAME record. Preserve existing MX and TXT records used by email and domain verification. Do not change records for other active services without checking their purpose.

## Before public launch

- Confirm the final company service list and wording.
- Add the official business email, telephone/WhatsApp and social links.
- Connect the enquiry form to an approved company inbox or form service. The current form formats and copies an enquiry; it does not transmit submissions.
- Add approved team, project and client material only where publication is authorised.
- Verify DNS and enable **Enforce HTTPS** once GitHub Pages has issued the certificate.

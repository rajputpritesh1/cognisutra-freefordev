# ⊕ CogniSutra — Free Tiers for Developers

> A curated database of **500+ free tier** SaaS, PaaS, and IaaS services for developers. No credit card. No nonsense.

🌐 **Live Site:** [cognisutra.in](https://www.cognisutra.in)
<img width="1919" height="912" alt="image" src="https://github.com/user-attachments/assets/12901e1c-b5dd-4cb7-8106-d2e110aee8f6" />

---

## What Is This?

CogniSutra Free Tiers is a single-page developer resource that helps you find the best free plans across cloud platforms, hosting, databases, CI/CD pipelines, AI/ML APIs, and more — all in one place.

Built for developers who want to ship without spending.

---

## Features

- 🔍 **Live search** across all 500+ services
- 🏷️ **Category filters** — Cloud, Hosting, Database, CI/CD, Auth, AI/ML, and more
- 🌙 **Dark / Light mode toggle** with localStorage persistence
- ⚡ **Zero dependencies** — pure HTML, CSS, and vanilla JS
- 📱 **Fully responsive** — works on mobile, tablet, and desktop
- 🔗 **URL search param support** — shareable filtered links via `?q=redis`

---

## Categories Covered

| Category | Services |
|---|---|
| ☁ Major Cloud Providers | AWS, GCP, Azure, Oracle, IBM, Cloudflare |
| ⌥ Source Code Repos | GitHub, GitLab, Bitbucket, Codeberg + more |
| ⟳ CI/CD Pipelines | GitHub Actions, CircleCI, Travis CI + more |
| ⬡ Web Hosting | Vercel, Netlify, Cloudflare Pages + more |
| 🗄 Databases | Supabase, PlanetScale, MongoDB Atlas + more |
| 🔐 Auth & Identity | Auth0, Firebase Auth, Clerk + more |
| 📊 Monitoring | Sentry, Datadog, UptimeRobot + more |
| 📧 Email Services | Resend, SendGrid, Mailgun + more |
| 🗃 Storage | Cloudflare R2, Backblaze B2 + more |
| 🤖 AI / ML APIs | OpenAI, Groq, Hugging Face + more |
| 🔒 Security | Snyk, OWASP, Dependabot + more |
| 🧪 Testing | Browserstack, Cypress, Postman + more |
| 📝 CMS | Sanity, Contentful, Strapi + more |
| ⊞ DNS & Domain | Cloudflare DNS, DuckDNS, Porkbun + more |
| ∞ Tools & Misc | Slack, Notion, Figma, Zapier + more |

---

## Tech Stack

- **HTML5** — semantic, SEO-optimised structure
- **CSS3** — custom properties, grid, animations, no frameworks
- **Vanilla JS** — search, filter, theme toggle, localStorage
- **Fonts** — Orbitron, Share Tech Mono, Exo 2 (Google Fonts)

No build step. No npm install. Just open `index.html`.

---

## Getting Started

```bash
# Clone the repo
git clone https://github.com/rajputpritesh1/cognisutra-freefordev.git

cd cognisutra-freefordev

# Open in browser — no server needed
open index.html
```

Or deploy instantly to any static host (Vercel, Netlify, GitHub Pages, Cloudflare Pages).

---

## Deploying

### GitHub Pages
1. Push to a GitHub repo
2. Go to **Settings → Pages → Deploy from branch → main / root**
3. Your site is live at `https://yourusername.github.io/repo-name`

### Vercel / Netlify
Just drag and drop the `index.html` into the deploy area — done in under 30 seconds.

### Cloudflare Pages
1. Connect your GitHub repo
2. Build command: *(leave blank)*
3. Output directory: `/`

---

## SEO Setup (Post-Deploy Checklist)

- [ ] Submit site to [Google Search Console](https://search.google.com/search-console)
- [ ] Upload `og-image.png` (1200×630px) to your domain root for social previews
- [ ] Create `robots.txt` at root with `Allow: /`
- [ ] Add Google Analytics — replace `G-XXXXXXXXXX` in the `<head>` script
- [ ] Add your AdSense Publisher ID — replace `ca-pub-XXXXXXXXXXXXXXXX` and uncomment the ad slots

---

## Monetisation

The site is pre-wired for ads. To activate:

**Google AdSense**
1. Apply at [adsense.google.com](https://adsense.google.com)
2. Replace `ca-pub-XXXXXXXXXXXXXXXX` in `<head>` with your Publisher ID
3. Replace `XXXXXXXXXX` in the ad slot `data-ad-slot` with your Ad Unit ID
4. Uncomment both blocks

**Affiliate Links**
Many listed services (DigitalOcean, Linode, Vultr, Hetzner) offer referral programs. You can swap the service links with your referral URLs for passive income.

---

## Contributing

Found a free tier that's missing? PRs are welcome.

1. Fork the repo
2. Add your service card inside the correct `<div class="section">` block
3. Follow the existing card format:

```html
<div class="service-card">
  <div class="service-name">
    <a href="https://example.com" target="_blank">Service Name</a>
    <span class="free-badge">FREE</span>
  </div>
  <div class="service-desc">What the free tier includes. Be specific about limits.</div>
</div>
```

4. Open a pull request with a short description

---

## Roadmap

- [ ] `manifest.json` + service worker for PWA / offline support
- [ ] "Bookmark" feature to save favourite services (localStorage)
- [ ] Shareable category links (`cognisutra.in/#hosting`)
- [ ] "Last verified" date on each card
- [ ] Submit-a-service form
- [ ] RSS feed for new additions

---

## Author

Built by **Pritesh Rajput** — Duty Manager by day, full-stack developer always.

- 🌐 [cognisutra.in](https://www.cognisutra.in)
- 📸 Instagram / YouTube: [@justpriteshrajput](https://www.instagram.com/justpriteshrajput)
- 💼 [Cognisutra](https://www.cognisutra.in) — Web development & tech services (Udyam Registered)

---

## License

MIT — free to use, fork, and modify. Attribution appreciated.

---

<p align="center">
  <strong>ALWAYS FREE. NO CREDIT CARD. NO NONSENSE.</strong>
</p>

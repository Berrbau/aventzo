# Aventzo — Landing Page

Simple one-page landing/waitlist site for [aventzo.com](https://aventzo.com), a digital protection company helping creators, influencers and online brands protect their content, privacy and digital identity through a coordinated network of trusted technology partners.

## Structure

```
.
├── index.html   # the entire site (HTML/CSS/JS, no build step required)
└── README.md
```

## Deploying with Cloudflare Pages

1. Push this repo to GitHub.
2. In the Cloudflare dashboard, go to **Workers & Pages → Create Application → Pages → Connect to Git**.
3. Select this repository.
4. Build settings:
   - **Build command:** (leave empty)
   - **Build output directory:** `/`
   - **Production branch:** `main`
5. Click **Save and Deploy**.
6. Once deployed, add your custom domain (`aventzo.com`) under **Custom Domains** in the project settings.

No build tools, frameworks, or dependencies are required — it's a single static HTML file.

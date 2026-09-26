# 🌐 Behnam Pourjanali — Personal Website

A minimal, elegant single-page portfolio built using pure **HTML/CSS/JS**.
The deployable site is the static `index.html`; the previous Cloudflare Worker source is retained under `Old_docs/` for reference. The site can be deployed on **GitHub Pages** or **Cloudflare Pages**.

---

## ✨ Features

- Responsive, adaptive card layout
- Balanced **light/dark** color system with toggle and persistent theme memory
- Subtle **blur and gradient** background aesthetics
- SEO and OpenGraph metadata
- Minimal SVG icon system (Sun/Moon, GitHub, LinkedIn)
- Built-in **modal for Sepidar SDKs**
- Fully deployable on **GitHub Pages** or **Cloudflare Pages**

## 🔎 SEO checks

Run the static checks for metadata, canonical URLs, JSON-LD, image alt text, external-link safety, `robots.txt`, and `sitemap.xml` with PowerShell:

```powershell
powershell -NoProfile -ExecutionPolicy Bypass -File .\tools\seo-check.ps1
```

These checks do not replace real-browser testing, Cloudflare/GitHub Pages response verification, Core Web Vitals measurement, or Google Search Console data.

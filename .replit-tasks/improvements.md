# Replit Agent Task: CPaintingServices

## Goal
Elevate the existing CPaintingServices multi-page HTML site (already well-structured with borough pages, gallery, and services) to production quality — adding real imagery placeholders, a working quote form, Google Maps embed, and polishing SEO so it ranks for NYC painting contractor searches across all five boroughs.

## Tasks
1. Audit all existing pages (index.html, about.html, gallery.html, contact.html, interior-painting.html, exterior-painting.html, commercial-painting.html, brooklyn.html, queens.html, manhattan.html) — note what's placeholder vs. real content and fix any broken links or missing styles
2. **Hero section (index.html)**: replace any stub content with a compelling headline ("NYC's Most Trusted Painters — Free Estimates, All 5 Boroughs"), a hero background image (use Unsplash painting crew placeholder), and two CTAs: "Get Free Quote" (scrolls to form) and "Call Now: (347) 469-8202"
3. **Services section**: add before/after image comparison cards for Interior, Exterior, and Commercial painting using a CSS slider (no JS library needed — use checkbox hack or simple JS toggle)
4. **Gallery page**: populate with 12 placeholder painting project images in a responsive masonry CSS grid; add filter buttons (Interior / Exterior / Commercial / Residential)
5. **Quote form (contact.html)**: name, phone, email, service type dropdown, property type, borough, message, preferred contact time; submit via Formspree; add Google reCAPTCHA v3 placeholder (just the script tag + data-sitekey stub)
6. **Google Maps embed**: on contact.html, embed a Google Maps iframe showing the NYC service area (use the embed API URL centered on Queens/NYC); add a "Service Area" section listing all five boroughs with borough-specific keywords
7. **Borough pages** (brooklyn.html, queens.html, manhattan.html): each should have unique hero copy, a "Why Choose Us in [Borough]" section, 3 local testimonials with first name + street/neighborhood, and a borough-specific FAQ (3–5 questions)
8. **SEO**: ensure each page has a unique <title>, meta description, canonical URL, and OG tags; add LocalBusiness schema JSON-LD to index.html (name, address, phone, areaServed, serviceType)
9. **Performance**: lazy-load all images (add loading="lazy"), minify inline CSS, ensure the existing Google Fonts load with `display=swap`
10. **CTA persistence**: add a sticky "Call Now" button on mobile (fixed bottom bar) visible on all pages

## Tech Stack
- Vanilla HTML5 / CSS3 / JavaScript (existing stack — do not convert to a framework)
- Formspree for contact form
- Google Maps embed (iframe)
- JSON-LD structured data
- Existing CSS file (css/main.css)

## Deploy Target
Cloudflare Pages (static site, existing CNAME already set to cpaintingservices.nyctailblazers.com). Never Vercel.

## Done When
- [ ] All pages load without 404s or broken asset links
- [ ] Hero has real headline, CTA buttons, and hero image
- [ ] Gallery shows 12 images with working filter buttons
- [ ] Quote form on contact.html submits via Formspree
- [ ] Google Maps embed renders on contact.html
- [ ] Each borough page has unique hero copy + 3 testimonials + FAQ
- [ ] LocalBusiness JSON-LD present on index.html
- [ ] Mobile sticky "Call Now" bar visible on all pages
- [ ] Lighthouse performance score ≥ 80 on mobile

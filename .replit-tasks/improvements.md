# Replit Agent Task: CPaintingServices + CPaintingServicesBrooklyn (Consolidation)

## Goal
Consolidate CPaintingServices and CPaintingServicesBrooklyn into a single, clean professional painting contractor website that serves all NYC boroughs, with strong local SEO and a clear quote request flow.

## Tasks
1. Merge the best content from both repos into one unified site — CPaintingServices becomes the canonical repo; CPaintingServicesBrooklyn can redirect here
2. Build a hero section: clean white/navy professional aesthetic, headline "NYC's Trusted Painting Contractors", subline covering all boroughs, and a prominent "Get a Free Quote" CTA
3. Create a Services section: Interior Painting, Exterior Painting, Commercial Painting, Wallpaper Removal, Color Consultation — each as a card with icon, description, and price range
4. Build a Portfolio/Gallery section: before/after photo grid (use placeholder images) with project type labels (apartment, brownstone, office, etc.)
5. Add a Service Area section: list all NYC boroughs served (Manhattan, Brooklyn, Queens, Bronx, Staten Island) with a simple NYC borough map graphic or icon grid
6. Add Testimonials: 5 realistic reviews from NYC clients with names, boroughs, and star ratings
7. Build a Quote Request form: name, email, phone, address, service type, square footage, preferred start date — submit to Supabase `quote_requests` table
8. Add local SEO: borough-specific meta description, JSON-LD for LocalBusiness with serviceArea NYC, canonical URL
9. Add Open Graph tags and a professional logo/favicon
10. Ensure full mobile responsiveness
11. Deploy to Cloudflare Pages

## Tech Stack
- HTML/CSS/JS (or React if the existing codebase already uses it — match what's there)
- Supabase (quote request storage)
- Cloudflare Pages (static deploy)

## Deploy Target
Cloudflare Pages — connect `Kaoz625/CPaintingServices`. Never Vercel.

## Done When
- [ ] Services, Portfolio, Testimonials, and Quote sections all built
- [ ] Quote form submits to Supabase
- [ ] All 5 NYC boroughs listed in service area
- [ ] JSON-LD LocalBusiness schema with serviceArea present
- [ ] Mobile-responsive at 375px
- [ ] All changes pushed to `Kaoz625/CPaintingServices` main branch

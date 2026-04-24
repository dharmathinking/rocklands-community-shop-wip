# Rocklands Community Shop — Website Concepts

Two complete website designs for Rocklands Community Shop Ltd (Community Benefit Society, Reg. No. 30665R).

---

## Concept A — "The Harvest Board" (`rcs-concept-a/`)

**Trading name:** Rocklands Market  
**Tagline:** "What's in today"  
**Feel:** Dark green, blackboard aesthetic — like a high-quality deli or farmers' market. The homepage IS a daily market board. Updated weekly.

### Pages
- `index.html` — Homepage: live board showing what's fresh, hours, suppliers, CTAs
- `shop.html` — Shop services, full grocery list, Post Office services
- `cafe.html` — Dove's Café, menu, community events
- `suppliers.html` — Local suppliers directory, "be a supplier" CTA
- `volunteer.html` — Volunteer page, roles, rights, expression-of-interest form
- `about.html` — Mission, values, membership, governance docs, privacy policy, complaints
- `contact.html` — Address, hours, map placeholder, contact form

---

## Concept B — "The Living Map" (`rcs-concept-b/`)

**Trading name:** The Rocklands  
**Tagline:** "30 miles, rooted here"  
**Feel:** Warm earth tones, editorial/magazine aesthetic. The hero map shows the 30-mile supplier radius — it's the central brand idea. Strong funder appeal.

### Pages
- `index.html` — Homepage with SVG map hero, suppliers, stories, hours, CTAs
- `our-map.html` — The Living Map: full-screen SVG map with supplier sidebar + profiles
- `cafe.html` — Café: menu, events, atmosphere
- `shop.html` — Shop & Post Office: full service list
- `volunteer.html` — Volunteer page: roles, rights, expression-of-interest form
- `about.html` — Mission, values (HRQAE), membership, governance docs, privacy, complaints
- `contact.html` — Address, map placeholder, contact form

---

## What both sites include
- Full navigation with active page highlighting
- Cookie consent banner (GDPR-compliant, stored in localStorage)
- Mobile-responsive design with hamburger menu
- Today's opening hours auto-highlighted
- Volunteer expression-of-interest form (with JS feedback)
- Newsletter signup
- Contact form
- Governance document list (PDF links ready to fill in)
- Full privacy policy (UK GDPR)
- Two-stage complaints procedure
- Funding logos: Plunkett UK, Prince's Countryside Fund, National Lottery Community Fund
- Post Office services list
- All legal text: CBS registration, volunteer rights, IP clause
- Page fade-in animation
- Social media links (Facebook, Instagram — update URLs)

---

## Production checklist before going live

1. **Phone number** — replace `01953 XXX XXX` with the real number in `contact.html`
2. **Email address** — update to the real shop email in `contact.html` and `about.html`
3. **Google Maps embed** — replace the map placeholder iframe in `contact.html`
4. **Governance PDFs** — upload real PDFs and update the `href="#"` links in `about.html`
5. **Opening hours** — check and update if different from those shown
6. **Social media URLs** — update Facebook/Instagram links in the footer
7. **Photos** — add real café and shop photos to replace the emoji placeholders
8. **Domain** — Concept A suits `rocklandsmarket.co.uk`; Concept B suits `therocklands.co.uk`
9. **Google Analytics / tracking** — add a `<script>` tag in `<head>` if desired
10. **Trading name decision** — choose one name and update any remaining references

---

## Deploying to GitHub Pages

1. Create a new GitHub repository (e.g. `rocklands-market-website`)
2. Upload the contents of your chosen concept folder as the root of the repo (or upload both in separate folders)
3. Go to **Settings → Pages** and set the source branch to `main`, folder to `/`
4. Your site will be live at `https://yourusername.github.io/rocklands-market-website/`
5. Share that URL with Andy to review

---

*Built April 2025. All content © Rocklands Community Shop Ltd, Community Benefit Society Reg. No. 30665R.*

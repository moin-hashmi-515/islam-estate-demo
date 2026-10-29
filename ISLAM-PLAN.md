# Islam Estate — Demo + CMS Plan (2026-10-29)
## Pitch issue (verified live 2026-10-29, dharealestate.pk)
- Do NOT pitch as "no website" — they have a 13-year-old WordPress/Genesis blog with DHA articles and search traffic.
- Pitchable problems: (1) blog, not a listings portal — no phase/price/size filters, no property price cards; (2) Plot Wanted enquiry form does not render (raw shortcode shown instead) — the exact lead that should be captured is lost; (3) Contact page has no form, only phone/WhatsApp text; (4) no address or hours shown; (5) duplicate breadcrumb and keyword-stuffed footer.
- Offer mapping: WordPress listings portal (search by phase/type/purpose, price-on-enquiry until real prices added, working enquiry forms, Plot Wanted flow), keep existing DHA articles for SEO, plus Listings CMS (listings, enquiries, articles, settings).
- Tracker estimate: PKR 35,000–60,000 (estimate only) for listings + lead-gen site, SEO separate from PKR 10,000/month. No real property prices/addresses invented in the demo — sample listings are layouts with "price on enquiry".
## Demo architecture (same limit as previous demos)
- GitHub Pages is static only. Front-end demo CMS: data in browser localStorage under ie_* keys (separate from SkinLab sl_* and Bella bc_* on the same origin), no server, no real login, no real notifications. Production needs a backend/WordPress build.
- Files: index.html (public demo portal), admin.html (CMS: Dashboard, Listings, Enquiries, Articles, Settings), ISLAM-PLAN.md (this file).
- Brand: black header + orange plaque as seen (no verified hex — orange in code is a visual approximation, not a claimed brand hex). Logo is text ("DHA Real Estate.pk") as on the live site — no logo file was exposed.
- Contact (verified): phone/WhatsApp 0321 4000 646 (WhatsApp via web.whatsapp.com/send, no wa.me found), email farazdha@gmail.com, names Faraz / Faraz Ali / CEO Faraz Shoukat as shown on site (exact CEO form to confirm), no address/hours shown.
- Tests: JS syntax checked with node --check; filters and enquiry save logic are client-side and demo-only.
- Outstanding: enable GitHub Pages (main, root) for the new repo, verify live URLs, owner to confirm real listings/prices, address, hours, and CEO name form.

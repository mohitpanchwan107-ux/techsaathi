NIV OGET — PROJECT NOTES (UPDATED 19 OCTOBER 2026)

LIVE WEBSITE
https://mohitpanchwan107-ux.github.io/techsaathi/

REPOSITORY / SOURCE CODE
https://github.com/mohitpanchwan107-ux/techsaathi

PROJECT PURPOSE
An electronics, gadgets, accessories and home-appliances discovery website with product cards and practical buying guidance. It is an information/affiliate-ready project, not a live price-comparison API or hands-on review lab.

PAGES
- index.html — homepage, product explorer, search, filters and product details
- about.html — about Nivoget
- contact.html — feedback/contact information
- smartphone-buying-guide.html — smartphone guide with English/Hinglish toggle
- laptop-buying-guide.html — English laptop guide
- laptop-buying-guide-hinglish.html — Hinglish laptop guide
- tablet-buying-guide.html — English tablet guide
- tablet-buying-guide-hinglish.html — Hinglish tablet guide
- home-appliances-buying-guide.html — English TV, refrigerator, washing-machine, AC and kitchen-appliance guide
- home-appliances-buying-guide-hinglish.html — Hinglish version of the home-appliances guide
- privacy.html — privacy information
- affiliate-disclosure.html — affiliate disclosure
- editorial-policy.html — editorial policy
- 404.html — missing-page help
- robots.txt and sitemap.xml — search-engine discovery

CATALOGUE STATUS
- Homepage catalogue contains 75 product cards across 29 categories.
- Current source audit found image URLs on all 75 product cards; no cards remain without an image URL. The 47 previously illustrative previews have been replaced with product-specific or clearly identified model/range images. External image loading, exact model/variant match, and source permissions/terms have not all been live-verified and must be checked before launch.
- Latest source audit across both JavaScript object styles found 10 direct Amazon product URLs and 65 Amazon search-result URLs across the 75 cards. Direct links are for Google Pixel 10, OnePlus 13R, Samsung UE86AH TV, Logitech K380s, Logitech G502 HERO, Canon EOS R50, Brother DCP-T535DW, TP-Link Deco M4 2-pack, Echo Dot 5th Gen and PS5 Slim. 51 Amazon search links use the full product-card name as the search query, improving specificity; they remain search-result links, not verified exact listings. This is a source-code audit, not a live check that a listing is available or matches the exact model/variant; open each direct listing before launch.
- Some entries represent product families rather than a verified exact model.
- Some cards use third-party retailer images; verify source terms/permissions and exact model/variant before launch.
- Some retailer buttons open model-search results rather than a verified exact product listing.
- Prices, stock, variants and specifications can change; verify with the manufacturer and seller before purchase.
- Product cards are manually maintained; products do not automatically update from a retailer feed/API.
- Do not claim hands-on testing, exact current prices or guaranteed availability unless verified.

PHASE 1 FINAL CHECKLIST — ITEMS STILL REQUIRING MANUAL/EXTERNAL VERIFICATION
1. Test search, category filters, sorting and every product-details popup on desktop and mobile.
2. User visually checked the product images on the live site and reported they look okay. Still review all 75 image sources for exact-model/variant match and source terms/permissions; the source count does not prove reuse is permitted.
3. Re-open the 10 direct Amazon product URLs to confirm the current listing and exact variant; review the 65 search links and keep them clearly described as search results until an exact listing is verified.
4. Static source audit checked all 15 HTML files in the repository and found no missing local page links. GitHub Actions checks now pass for internal links, catalogue data and inline JavaScript syntax (latest successful check commit: `658f4bc67ae26717e29fe3d841063f987d363d2b`). This does not replace a live browser/mobile test; recheck the deployed pages, 404 page, robots.txt and sitemap.xml.
5. Phase 2 SEO cleanup: refined meta descriptions for privacy, editorial policy and affiliate disclosure pages. Verify GitHub Pages deployment status before assuming the live copy has updated.
6. Check GitHub Pages deployment status after each commit and retest the live site.
7. Google Search Console ownership verification and sitemap submission require access to the owner's Google account; this cannot be completed from repository code alone.
8. Smartphone guide includes English/Hinglish content; laptop, tablet and home-appliances guides are now available in English and Hinglish.
9. Confirm teacher's rubric/project instructions. A website being live does not prove it satisfies every classroom requirement.

PUBLISHING
GitHub Pages deploys changes from the configured branch, but publishing may take a short time. Check:
https://github.com/mohitpanchwan107-ux/techsaathi/actions

IMPORTANT
Do not describe Phase 1 as fully verified until the checklist above has actually been tested.
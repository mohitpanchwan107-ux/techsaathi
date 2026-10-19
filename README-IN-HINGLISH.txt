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
- diwali-shopping-guide.html — English Diwali electronics and home-appliance shopping checklist
- diwali-shopping-guide-hinglish.html — Hinglish Diwali shopping checklist
- privacy.html — privacy information
- affiliate-disclosure.html — affiliate disclosure
- editorial-policy.html — editorial policy
- 404.html — missing-page help
- robots.txt and sitemap.xml — search-engine discovery

CATALOGUE STATUS
- Homepage catalogue contains 75 product cards across 29 categories.
- Current source audit found image URLs on all 75 product cards; no cards remain without an image URL. The 47 previously illustrative previews have been replaced with product-specific or clearly identified model/range images. External image loading, exact model/variant match, and source permissions/terms have not all been live-verified and must be checked before launch.
- Latest source audit found 6 direct Amazon product URLs and 69 Amazon search-result URLs across the 75 cards. Direct links currently point to Samsung UE86AH TV, Logitech G502 HERO, Canon EOS R50, Brother DCP-T535DW, TP-Link Deco M4 2-pack and PS5 Slim. All 69 Amazon search links use the exact full product-card name as the search query; automated checks validate this match. Search links are search results, not verified exact listings. This is a source-code audit, not a live check that a listing is available or matches the exact model/variant; open each direct listing before launch.
- Some entries represent product families rather than a verified exact model.
- Some cards use third-party retailer images; verify source terms/permissions and exact model/variant before launch.
- Some retailer buttons open model-search results rather than a verified exact product listing.
- Prices, stock, variants and specifications can change; verify with the manufacturer and seller before purchase.
- Product cards are manually maintained; products do not automatically update from a retailer feed/API.
- Do not claim hands-on testing, exact current prices or guaranteed availability unless verified.

PHASE 1 / LIVE QA STATUS — UPDATED 19 OCTOBER 2026
PASS — User manually checked the live homepage, search, category filter, sorting, View details, buying guide and mobile layout.
PASS — GitHub Actions site checks: internal links/catalogue data, product image and retailer URL coverage, inline JavaScript syntax, SEO metadata and sitemap coverage. Latest run reports 75 product entries, 65 exact-name Amazon search URLs, 10 direct product URLs, and 13 canonical pages included in sitemap.
PASS — Latest verified GitHub Pages deployment completed successfully for commit 5986008f7fee7b3d75a16b41d02d945211e5854b (Add bilingual Diwali guides to sitemap). Site-check workflow also passed for that same commit. Any later commit needs its own deployment check.
PASS — Static source audit checked all 16 HTML files and found no missing local page references.
PASS — Two Diwali shopping guides are available in English and Hinglish, linked to each other and included in the 15-page canonical sitemap.
PASS — Catalogue has 75 product cards across 29 categories; each has an HTTPS image URL, manufacturer URL and retailer URL. Current automated audit reports 10 direct Amazon product URLs and 65 Amazon search-result URLs; the search terms match the corresponding product-card names.

REMAINING LAUNCH TASKS — EXTERNAL / OWNER-ONLY VERIFICATION
1. Verify the 75 image sources for exact model/variant match and source terms/permissions. User reports images look okay on the live page; visual loading does not establish reuse rights.
2. Re-open the 10 direct Amazon product URLs to confirm current availability and exact variants. The other 65 are clearly labelled search-result links, not verified exact product listings.
3. Google Search Console verification file exists in the repository. User reports ownership verification is complete. Submit the sitemap in Search Console if it has not already been submitted: https://mohitpanchwan107-ux.github.io/techsaathi/sitemap.xml. Check the Sitemaps and Pages/Indexing reports for processing and indexing status; verification alone does not mean all pages are indexed.
4. Confirm the teacher's rubric/project instructions. A working website does not automatically satisfy every classroom requirement.
5. Recheck the latest deployment after any future change. GitHub Actions workflow checks are source-code checks and do not prove every third-party link or image will stay live.

PUBLISHING
GitHub Pages deploys changes from the configured branch, but publishing may take a short time. Check:
https://github.com/mohitpanchwan107-ux/techsaathi/actions

IMPORTANT
Do not describe Phase 1 as fully verified until the checklist above has actually been tested.
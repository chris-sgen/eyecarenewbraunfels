# Provenance

> **Unofficial copy — not the website of Eye Care New Braunfels.** See `README.md`.

Where everything in this copy comes from, and what was changed to publish it. The same facts, as data, are in `PROVENANCE.json`.

## Words

Apart from the redesign's own words listed in the README, the pages' text comes from https://www.eyecarenewbraunfels.com/, read from a crawl of 23 addresses on the evening of October 27, 2026, Central Time (October 27, between 23:30 and 23:31 UTC).

## Pictures and video made for this redesign

1 still and 1 loop (one more still was made only as the first and last frame of the loop), made on the evening of October 27, 2026, Central Time (October 28, between 00:01 and 00:07 UTC). None shows a person, the practice's office, a clinical result, lettering, a label, a logo or a named product. Each candidate was looked at whole, on a sheet beside the other candidate of its still, and each still used was then opened in enlarged regions at its full size, looking for lettering, numbers, marks that read as a brand, a recognisable product, a person or a hand, a malformed object and a border; the loop was looked at as a sheet of five of its frames (at 0, 1.2, 2.5, 3.8 and 4.9 seconds). Each still was made in two candidates, and the better one used. In each still used, the model had drawn a pretend size print along the inside of one temple of the eyeglasses: it was taken off by refilling small rectangles from their own borders (still-registration: 10 rectangles, 856 pixels, 0.02% of the picture, along the left temple; still-appointment: 7 rectangles, 1,344 pixels, 0.03% of the picture, along the right temple), and nothing outside them was changed. The files here are re-encodings made by the private build (WebP through a browser canvas, H.264 without an audio track); each carries the AI label (README, Generated imagery) and was read for metadata before publishing (README, Verification). The manifest of the fal.ai originals says that an imperceptible SynthID watermark was applied (a watermark in the picture itself, not in its metadata); this copy did not test for it. The services' price lists put the three requests at about $1.16 in all (the sum of the estimates their records state). 2 remarks of the review of the pictures:

| Picture | Remark |
| --- | --- |
| still-appointment | The still itself is not shipped as a picture of its own: the appointment request page shows the loop made from it, with the loop's first frame as the poster. |
| loop-appointment | Five seconds, 24 frames a second, first and last frame the same picture (the retouched still): the light through the lenses drifts over the linen, from soft aqua to a pale blush and back, and returns; the eyeglasses, the cup and the dish do not move. Encoded silent at 1280 and 768 px by the private build, none of the service's tags carried over. |

| Name (under assets/generated/) | Kind | What it shows | Made with | Pages that show it |
| --- | --- | --- | --- | --- |
| loop-appointment | loop | deep teal eyeglasses folded on white linen over a light wood counter, beside a white cup on its saucer and a small terracotta dish, with the light cast through the lenses drifting slowly over the linen, from aqua to a pale blush and back (made from one still, used as its first and last frame); a pretend size print that the model drew along the inside of the right temple was taken off the still it was made from | Higgsfield: kling-video/o3/first-last-frame, from a still made for it (fal.ai: nano-banana-pro) | `/contact-us/appointment-request-form/` |
| still-registration-clean | still | a pale wooden clipboard of blank white paper with a plain deep teal pen across it, black metal eyeglasses folded beside it and a sprig of eucalyptus, on white linen over a light wood desk; a pretend size print that the model drew along the inside of the left temple was taken off | fal.ai: nano-banana-pro | `/contact-us/patient-registration-form/` |

## Pictures from the live site

181 file names of pictures published on the practice's site are used, each in one version: photographs of the pages' topics, the photograph that appears to show the practice's two doctors before its sign (in its own shape, not cut to the shape of the band, on `/our-optometric-team/`, as on the live site, and on the home page), the photograph of its reception desk and the photograph of a family on a picnic (both on the home page, as on the live home page), two photographs of the town (on `/contact-us/`, as there), the pictures of the contact lenses and the instruments its pages name, the logos of the eyewear brands and insurers its pages name, the picture of its not-found page, and the practice's logo. Each picture stands on the pages where the live site shows it; the one the redesign adds elsewhere is the photograph of the doctors, on the home page. Of the 212 picture addresses the live pages and their stylesheets name, the private build shows 181 on its pages; the 31 it does not show are the platform's placeholder for the doctors' portraits (4 addresses, 2 pictures by their bytes; the private build keeps one file of it, only for the link-preview tags of the doctors' own pages, which is not shipped here: Hardening 10), a second copy of a contact lens box, the same bytes as one it shows, the photograph of eyeglasses on a shelf that the live `/eyeglasses/` page lays behind its band of brand logos (a stock library's picture, by its file name), the live site's tab icon (a small picture of the practice's mark), and 24 pictures of the old platform: its small icons and its form plugin's spinner (5), its credit logo (1) and the decorations its theme and plugin stylesheets name (18, one of which could not be downloaded: C07). The placeholder is not a photograph of either doctor: the private build, and this copy, draw each doctor's initials in its place (README, Hardening 6). No picture the private build shows on its pages is left out of this copy.

## Typefaces

Work Sans, the live site's own typeface, under the SIL Open Font License 1.1, served from this site; the licence text is beside the font files, and its copyright line is the one the font files carry (Version 2.012).

## Changes made for publishing

| Change | Count |
| --- | --- |
| Pages given the robots tag `noindex, nofollow, noarchive, nosnippet, noimageindex` and a `no-referrer` tag | 22 |
| JSON-LD blocks removed | 204 |
| Link-preview picture tags removed | 46 |
| Pages whose link-preview tags carry the disclosure | 22 |
| Link-card titles marked "Unofficial preview:" | 22 |
| Icon links removed | 66 |
| Page descriptions replaced by the disclosure | 2 |
| Forms of the practice switched off (inert three ways, with their notices) | 2 |
| Notices of a disabled form: in the head of the page, right above the form, under its button | 2, 2, 2 |
| Lines of the private build about its forms taken out (with the templates its script fills) | 4 (2) |
| Parts of the registration form that its rules show only after an answer, hidden before any answer (the script that hides them does not run in an inert form) | 26 of 26 |
| Notes "the words on this page are the live site's own" | 4 |
| Links that lost marks that say where the visit comes from | 1 |
| Map frames that carry `referrerpolicy="no-referrer"` | 21 (all carried it in the private build) |
| Canonical tags removed (pages the build makes itself) | 2 |
| Search-index entries reduced to their title, section and the short names they are filed under | 6 |
| Comments taken out (stylesheet, script) | 296, 111 |
| Generated files given the AI label | 9 |
| Files of the private build not shipped | `.htaccess`, `llms.txt`, `sitemap.xml`, `sitemaps/sitemap-blog-categories.xml`, `sitemaps/sitemap-locations.xml`, `sitemaps/sitemap-pages.xml`, `vercel.json`, `_headers`, `_redirects` |
| `robots.txt` | replaced by the preview's own (`Disallow: /`) |
| Files nothing in this copy names, not shipped | 4 |

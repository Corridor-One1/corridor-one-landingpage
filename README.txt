CORRIDOR ONE — WEBSITE (single page)
=====================================

Files
- index.html  The whole site: content (Thai + English), styles and scripts in one file. No build step.

Deploy
- Vercel / Netlify / Cloudflare Pages: upload this folder as a static site (no framework, no build command, output = this folder).

Settings to complete before public launch (search index.html for "CONFIG" and "TODO")
1. CONFIG.WEB3FORMS_KEY   Web3Forms access key. While empty, the form opens the visitor's email app instead.
2. CONFIG.CONTACT_EMAIL   Inquiry recipient (currently corridorone.hq@gmail.com). Confirm with the founder.
3. <link rel="canonical"> / og:url / og:image in <head> once the domain is final.
4. Privacy notice: replace the "[Privacy notice — pending review]" placeholder text (key "privacy" in the COPY object, both th and en) with a link to the approved notice.
5. Phone numbers and email in the Contact section: confirm with the founder.

Editing text
- All wording lives in the COPY object near the bottom of index.html (th and en). The Thai text is also written directly into the page markup so search engines can read it; if you change Thai wording, change it in both places (or ask for a rebuild).

Accessibility / motion
- No animations beyond smooth scrolling; respects "reduce motion".
- Language toggle remembers the visitor's choice in their browser.

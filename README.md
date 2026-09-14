# Satya Krithik — website

Single-file site. Routes are hash-based: #/ (home), #/work, #/about, #/work/<slug>.

## Files
- index.html — the whole site (HTML + CSS + JS + project data in the `projects` array)
- images/satya-bw.png — home page photo

## Editing
- Home copy: search for `class="home2"` in index.html.
- Projects: edit the `projects` array near the bottom of index.html.
- Fonts: Bricolage Grotesque (home name), Fraunces + Inter (rest), loaded from Google Fonts.
- Deploy: push to `main`; Vercel redeploys automatically.

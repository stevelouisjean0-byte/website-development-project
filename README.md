# American Partnership for Democracy and Opportunity (APDO) — Website

A 30-page static website for a U.S.–Haiti advocacy and public-affairs institution.
Built as plain HTML with inline styles (Public Sans + Source Serif 4 via Google Fonts)
and a `assets/` folder of photography. No build step required.

## Pages
- `index.html` — homepage (executive gateway)
- `about.html`, `leadership.html`, `compliance.html`
- `policy.html` + 18 individual `policy-*.html` priority pages
- `advocacy.html` (incl. Action Center), `research.html`
- `membership.html`, `donate.html`, `events.html`
- `media.html` (News & Press), `contact.html`

## Deploy (GitHub Pages)
1. Upload the entire contents of this folder to the repository root
   (Add file → Upload files → drag everything, including the `assets/` folder → Commit).
2. Settings → Pages → Build from branch → `main` / root.
3. The live site is served at the Pages URL; `index.html` is the entry point.

All internal links are relative flat paths (e.g. `about.html`), so the site works from
the repo root or any subpath without configuration.

## Notes
- Forms (newsletter, contact, donate, ZIP lookup) are front-end only; connect them to a
  CRM / email / payments provider at deployment.
- No tax-deductibility or endorsement claims are made; compliance disclaimers are included.
- Replace or add photography in `assets/` and update the matching `<img src>` references.

# American Partnership for Democracy and Opportunity (APDO) — Website

A 30-page static website for a U.S.–Haiti advocacy and public-affairs institution.
Plain HTML with inline styles (Public Sans + Source Serif 4 via Google Fonts) and an
`assets/` photo folder. No build step. Uses clean folder-per-page URLs (e.g. `/about/`,
`/policy/trade/`).

## Structure
- `index.html` — homepage
- `about/`, `leadership/`, `compliance/`
- `policy/` + 18 detail pages under `policy/<issue>/`
- `advocacy/` (incl. Action Center), `research/`
- `membership/`, `donate/`, `events/`
- `media/` (News & Press), `contact/`
- `assets/` — photography

## Deploy (GitHub Pages)
1. Upload the entire contents of this folder to the repository root
   (Add file → Upload files → drag everything, including `assets/` → Commit).
2. Settings → Pages → Build from branch → `main` / root.
3. Live at the Pages URL; `index.html` is the entry point and all links are relative.

## Notes
- Forms (newsletter, contact, donate, ZIP lookup) are front-end only; wire to a
  CRM / email / payments provider at deployment.
- No tax-deductibility or endorsement claims; compliance disclaimers included.
- To swap photos, replace files in `assets/` and keep the same filenames.

# maxime-pelissierh.github.io
# Personal academic website — Maxime Pélissier Hermitte

Single-page static site (HTML + CSS, no build step, no framework), hosted for free on GitHub Pages.

## Files
| File | Purpose |
|---|---|
| `index.html` | The whole website (content, design, small script) |
| `CV_Maxime_Pelissier_Hermitte.pdf` | Your CV, linked from the "Curriculum Vitae" button |
| `photo.jpg` | **You add this**: a square-ish portrait (min. 400x400 px). Until then a placeholder is shown |
| `photo-placeholder.svg` | Fallback avatar (delete once `photo.jpg` is added) |

## Deploy in 6 steps
1. **Create a GitHub account** at github.com (choose your username carefully: it appears in your URL).
2. **Create a repository** named exactly `YOUR-USERNAME.github.io` (public, no README).
3. **Upload the files**: on the empty repo page click *uploading an existing file*, drag in `index.html`, the CV PDF, `photo.jpg` and `photo-placeholder.svg`, then *Commit changes*.
4. **Enable Pages**: Settings → Pages → Source: *Deploy from a branch* → Branch: `main` / `(root)` → Save.
5. Wait 1–2 minutes: your site is live at `https://YOUR-USERNAME.github.io/`.
6. **Make it appear on Google**: go to search.google.com/search-console, add your URL as a "URL prefix" property, verify (HTML tag method: paste the given `<meta name="google-site-verification" ...>` tag inside `<head>` of `index.html`), then use *URL Inspection → Request indexing*. Also put the URL in your Google Scholar profile, ORCID, LinkedIn, and email signature to speed up indexing.

## What to customise in `index.html` (search for these strings)
- `YOUR_ID`, `YOUR-HANDLE`, `0000-0000-0000-0000`, `YOUR-USERNAME`: Scholar, LinkedIn, ORCID, GitHub links. **Delete any `<a>` icon you don't have.**
- `og:url` comment in `<head>`: uncomment and fill with your final URL.
- Contact block: the BSE street address is the school's public address; add your office number if you want.
- Add paper PDFs: put the file in the repo and add `<a class="paper-link" href="paper.pdf">paper</a>` after the paper title.
- Footer "Last updated": change the date when you edit.

## Content notes
- Text comes from your CV. I lightly corrected English typos in the abstracts (e.g. "knows", "exposition") and wrote the two intro paragraphs from your thesis title and papers: please read and adjust them.
- Nav: Home · Research · Presentations (#conferences) · Teaching · Service & Skills · Contact. A "References" section (as on the original) is omitted since your CV lists none; copy the `.referees` block from the original if you want one.
- Presentation months are derived from your CV dates (DD-MM-YYYY).

## Updating later
Edit `index.html` directly on GitHub (pencil icon) → Commit. The site refreshes in about a minute.

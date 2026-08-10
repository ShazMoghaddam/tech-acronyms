# Tech Acronyms, Decoded

A searchable field guide to 270+ tech abbreviations, grouped by field with a plain-English gloss on every one. One self-contained HTML page, no build step.

**Live:** https://shazmoghaddam.github.io/tech-acronyms/

## What it does
- Search every term, with the matching text highlighted in the results
- Filter by field, with shareable per-category links (for example `.../#security`)
- Keyboard: press `/` to jump to search, `Esc` to clear it
- Share button (uses the native share sheet, or copies the link) and Save as PDF
- Vibrant, colour-coded fields and a link-preview card for social posts

## Put it live on GitHub Pages
1. Create a new public repo named `tech-acronyms`.
2. Add `index.html` and `preview.png` to the root of the repo.
3. Go to Settings, then Pages. Under Source pick "Deploy from a branch", branch `main`, folder `/ (root)`, and Save.
4. Give it a minute, then open https://shazmoghaddam.github.io/tech-acronyms/

If you name the repo something else, update the three absolute URLs near the top of `index.html` (`canonical`, `og:url`, `og:image`) so the link-preview card resolves correctly.

## Files
- `index.html` — the page
- `preview.png` — the 1200x630 card shown when the link is shared

Made by Shaz Moghaddam.

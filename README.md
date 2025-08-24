# Our Bucket List Site (Form + Sheet)

This is a single-file website you can host on GitHub Pages. It lets both of you:
- Add new places via a **Google Form**
- See the live list via a **published Google Sheet**

## Quick Start
1) Create a Google Form with fields like *Place*, *Location*, *Why*, *Added by*.
2) Copy the form **Embed** URL (Send → <> Embed) and replace `YOUR_FORM_EMBED_URL` in `index.html`.
3) Open the form’s linked Google Sheet (Responses → View in Sheets).
4) In the Sheet: **File → Share → Publish to web** → Entire document → Publish.
5) Copy the published link (looks like `https://docs.google.com/spreadsheets/d/e/2PACX-.../pubhtml`) and replace `YOUR_SHEET_EMBED_URL` in `index.html`.
6) Commit to GitHub and enable **GitHub Pages** (Settings → Pages → Source: Deploy from branch).

## GitHub Pages URL
After enabling Pages, your site will be available at:
- `https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/`

## Notes
- If the sheet doesn’t render, ensure it's **Published to the web** (not just shared).
- For privacy, restrict edit access to just you two (via normal sharing), but publish a read-only view to the web for the embed.
- The site is fully static (no backend). The Google Form + Sheet handle collaboration.

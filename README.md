# Oxford Applied AI Society — Website

Static website for the Oxford Applied AI Society. No build step or dependencies — plain HTML and CSS.

## Structure

- `index.html` — home page: hero with "Become a Member" button, what we do, committee section, join section
- `termcard.html` — term card with the term's events
- `styles.css` — shared dark theme

## Local preview

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Customising

- **Committee members**: edit the `#committee` section in `index.html` (names, roles, avatar initials).
- **Membership link**: replace the `href="#"` on the "Become a Member" button in the `#join` section of `index.html` with your sign-up form or payment link.
- **Events**: edit the `.event` articles in `termcard.html`.
- **Colours**: tweak the CSS variables at the top of `styles.css`.

## Deploying

This site works as-is on GitHub Pages, Netlify, Vercel, or any static host — just upload the three files.

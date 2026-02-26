# E+B Arts & Crafts

Landing page for E+B Arts & Crafts — a 100% Yolŋu family-owned and operated art business from North-East Arnhem Land, Australia.

## About

E+B Arts is run by Elah Yunupingu and Barbara Wanambi. They create handcrafted sculptures, paintings, and weavings connected to Yolŋu moieties, kinships, and country. Completely independent from Balanda galleries and art centres.

## Project Structure

```
├── index.html              # Main landing page
├── assets/
│   ├── css/
│   │   └── styles.css      # Stylesheet
│   └── images/             # Artwork and portrait images
├── CNAME                   # Custom domain configuration
├── .gitignore
└── README.md
```

## Tech Stack

- Pure HTML/CSS/JS — no frameworks or build tools
- Google Fonts (Lilita One, Krona One, Barlow)
- Hosted on GitHub Pages

## Local Development

Open `index.html` directly in a browser, or use a local server:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`

## Deployment

This site is deployed via GitHub Pages. Any push to `main` will automatically deploy.

### Custom Domain Setup

1. In GitHub repo settings, go to Pages
2. Add your custom domain under "Custom domain"
3. Enable "Enforce HTTPS"
4. Configure DNS with your domain registrar:
   - For apex domain (e.g., `eandbarts.com`): Add `A` records pointing to GitHub's IPs
   - For subdomain (e.g., `www.eandbarts.com`): Add a `CNAME` record pointing to `<username>.github.io`

## License

All artwork and content copyright E+B Arts & Crafts.

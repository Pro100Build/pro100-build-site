# PRO100 BUILD — Website
Single-page React + Tailwind site ready for Netlify, Vercel, or GitHub Pages.

## Quick Start
```bash
npm i
npm run dev
npm run build
```

## Deploy
### Netlify
- New Site from Git
- Build command: `npm run build`
- Publish directory: `dist`

### GitHub Pages (Static Export)
- Push this folder to a new repo.
- Build locally: `npm run build`
- Serve `dist/` with GitHub Pages (enable Pages -> Deploy from `dist` on main via Actions or use a simple Pages workflow).

### Vercel
- Import the repo, set build command `npm run build`, output `dist`.

## Customise
- Edit `src/App.jsx` for content.
- Replace images in `public/` (logo.png, hero-image.jpg, og-image.jpg, favicon.ico).
- Update `index.html` meta tags (title/description/og).
- Set your Formspree endpoint in `src/App.jsx` (`action="https://formspree.io/f/your-id"`).

## Notes
- All works are marked as certified with warranty in Services.
- Contact details: phone, email, and address are prefilled for Royston SG8.

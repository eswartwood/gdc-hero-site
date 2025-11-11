# GDC Energy Core Site (Flare Edition)

This package includes transparent Energy Core V2 logos and Electric Horizon backgrounds (with strong flare), ready for GitHub → Vercel deployment.

## Structure
- `public/bg-desktop-flare.jpg`, `public/bg-mobile-flare.jpg` — strong flare backgrounds (default)
- `public/bg-desktop.jpg`, `public/bg-mobile.jpg` — non-flare alternates
- `public/gdc_energycore_v2_desktop.png`, `public/gdc_energycore_v2_mobile.png` — transparent logos
- `index.html` — minimal responsive poster (logo + tagline)

## Deploy
1. Create a new GitHub repo and upload all files.
2. In Vercel, **Import Git Repository** → Deploy.
3. Swap backgrounds by editing the CSS `background-image` in `index.html` if desired.

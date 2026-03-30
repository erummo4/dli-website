# NC Education Innovation Leadership Institute Website

This site is a static HTML/CSS/JS website. There is no build step.

## View locally

From this folder, run:

```bash
npm run preview
```

Then open:

[http://localhost:4173](http://localhost:4173)

If you want to preview it on another device on the same Wi-Fi network, run:

```bash
npm run preview:public
```

Then open:

`http://YOUR-COMPUTER-IP:4173`

## File structure

- `index.html`: landing page
- `pages/`: section pages
- `styles.css`: shared site styling
- `script.js`: mobile menu and active-nav behavior

## Share with others

Because this is a static site, the easiest sharing options are:

### Option 1: Netlify

1. Create a GitHub repo and push this folder.
2. In Netlify, choose "Add new site" -> "Import an existing project".
3. Select the repo.
4. Leave the build command blank.
5. Leave the publish directory as `/`.
6. Deploy.

### Option 2: Vercel

1. Create a GitHub repo and push this folder.
2. In Vercel, import the repo.
3. Framework preset: `Other`.
4. Build command: leave blank.
5. Output directory: leave blank.
6. Deploy.

### Option 3: GitHub Pages

1. Create a GitHub repo and push this folder to `main`.
2. In GitHub, open `Settings` -> `Pages`.
3. Under "Build and deployment", choose `Deploy from a branch`.
4. Select the `main` branch and the `/ (root)` folder.
5. Save.

GitHub will publish the site at a `github.io` URL after a short delay.

## Current status

The site includes:

- Home
- Convenings
- Learning Labs
- Fellowships
- Inspiration Visits
- Network
- Design Journeys

## Next likely improvements

- Add real application or inquiry forms
- Add logos, photography, or custom illustrations
- Connect CTAs to an email platform or CRM
- Add analytics and a custom domain

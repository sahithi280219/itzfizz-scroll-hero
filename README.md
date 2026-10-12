# ITZFIZZ — Scroll-Driven Hero

Responsive frontend assignment built with React, Tailwind CSS, GSAP, and ScrollTrigger.

## Run locally
1. Install Node.js if it is not installed.
2. In this folder, run:
   ```bash
   npm install
   npm run dev
   ```
3. Open the localhost URL shown in the terminal.

## Build and test
```bash
npm run build
npm run preview
```

## Deploy to GitHub Pages
1. Create a new **public** GitHub repository.
2. Upload the project contents to the repository's `main` branch.
3. Go to **Settings → Pages** and choose **GitHub Actions** as the source.
4. The included `.github/workflows/deploy.yml` builds and deploys the project after you push.
5. When the workflow is successful, open the repository's **Actions** tab to confirm deployment. The site URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`

## Interaction details
- GSAP timeline animates the intro headline on page load.
- ScrollTrigger pins the hero while the user scrolls the long hero track.
- Scroll progress drives the car translation and track-progress line.
- Statistic cards reveal at different scroll-progress points.
- Responsive styles support mobile and desktop; motion uses transform/opacity.

## Submission
Submit the actual deployed webpage URL, not the repository URL. Check it on both desktop and mobile first.

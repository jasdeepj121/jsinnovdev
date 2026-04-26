# JS Innovations Developer Site

Static developer website for JS Innovations and Water Sort Puzzle for Android.

## Files

- `index.html`: developer landing page and Water Sort Puzzle Google Play link.
- `privacy.html`: links to the current Water Sort Puzzle privacy policy.
- `support.html`: support contact page.
- `styles.css`: site styling.
- `app-ads.txt`: AdMob seller file.
- `assets/water-sort-puzzle-icon.png`: app icon copied from the Android launcher assets.
- `CNAME`: GitHub Pages custom domain (`jsinnovations.in`).

## Before Publishing

1. Confirm `app-ads.txt` matches your AdMob publisher ID (update if it ever changes):

   ```txt
   google.com, pub-8135378211247182, DIRECT, f08c47fec0942fa0
   ```

2. Confirm `CNAME` matches the hostname you configure in GitHub Pages and DNS:

   ```txt
   jsinnovations.in
   ```

## GitHub Pages Setup

1. Create a new GitHub repository for this folder, for example `jsinnovations-developer-site`.
2. Push these files to the repository's `main` branch.
3. In GitHub, open repository settings and go to **Pages**.
4. Set the source to `Deploy from a branch`.
5. Select branch `main` and folder `/ (root)`.
6. Add your custom domain in the GitHub Pages custom domain field.
7. Configure your domain DNS using GitHub Pages' recommended records.

After publishing, confirm these URLs load:

- `https://jsinnovations.in/`
- `https://jsinnovations.in/privacy.html`
- `https://jsinnovations.in/support.html`
- `https://jsinnovations.in/app-ads.txt`

Use the same domain in Google Play Console and AdMob app verification.

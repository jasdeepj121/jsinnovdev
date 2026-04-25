# JS Innovations Developer Site

Static developer website for JS Innovations and Water Sort Puzzle for Android.

## Files

- `index.html`: developer landing page and Water Sort Puzzle Google Play link.
- `privacy.html`: links to the current Water Sort Puzzle privacy policy.
- `support.html`: support contact page.
- `styles.css`: site styling.
- `app-ads.txt`: AdMob seller file.
- `assets/water-sort-puzzle-icon.png`: app icon copied from the Android launcher assets.

## Before Publishing

1. Replace the placeholder publisher ID in `app-ads.txt`:

   ```txt
   google.com, pub-0000000000000000, DIRECT, f08c47fec0942fa0
   ```

   Use your real AdMob publisher ID, for example `pub-1234567890123456`.

2. If you use a custom domain, add a file named `CNAME` in this folder with only your domain:

   ```txt
   example.com
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

- `https://your-domain.com/`
- `https://your-domain.com/privacy.html`
- `https://your-domain.com/support.html`
- `https://your-domain.com/app-ads.txt`

Use the same domain in Google Play Console and AdMob app verification.

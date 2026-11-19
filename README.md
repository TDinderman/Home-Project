# Our Home — iPhone-first design library

A static Progressive Web App intended for GitHub Pages and iPhone Safari.

## Publish with GitHub Pages

1. Sign in to GitHub and create a **new public repository** named `our-home-design`.
2. Upload the contents of this folder to the repository root (not the enclosing folder).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Choose branch `main`, folder `/ (root)`, then Save.
6. Wait for GitHub Pages to publish. Your app URL will look like:
   `https://YOUR-USERNAME.github.io/our-home-design/`

## Add it to iPhone Home Screen

1. Open the published URL in **Safari** (not the GitHub app or ChatGPT preview).
2. Tap Share.
3. Choose **Add to Home Screen**.
4. Name it **Our Home**, then tap Add.

## Photos and data

- Room details are stored in Safari local storage.
- Photos are resized and stored in IndexedDB on the device.
- This version does **not** sync across devices and does not upload photos to GitHub.
- Use **Backup** regularly. Save the downloaded `our-home-backup.json` in iCloud Drive or another safe location.
- Use **Restore** to load that backup on another device/browser.

## Privacy

The repository contains only the app code. Your room notes and photos remain in the browser on your device unless you export and share a backup.

## Notes

GitHub Pages provides free static hosting for public repositories. A custom domain is optional. For automatic cloud sync across multiple devices, add a separate backend such as Supabase in a later version; do not put private service keys in this repository.

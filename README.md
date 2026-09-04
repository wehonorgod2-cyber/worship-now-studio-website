# Worship Now Studio website

A static, responsive landing page based on the supplied Worship Now Studio design. It preserves the provided imagery, dark surfaces, and pink/purple accents. No framework, build step, analytics, or external fonts are required.

This website is separate from both Worship Now Xcode projects.

## Local preview

From this folder, run:

```sh
python3 -m http.server 4173 --bind 127.0.0.1
```

Open `http://127.0.0.1:4173`.

## Publish with GitHub Pages

1. Create a repository and upload this folder's contents. `index.html` must be at the repository root, alongside `assets/` and `.nojekyll`.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**, then choose **main** and **/ (root)**. Save.
4. Wait for the Pages deployment to finish and use the URL shown in Settings. A project website normally uses `https://ACCOUNT.github.io/REPOSITORY/`.

GitHub Pages publishes a public website. All paths are relative so the website works under a project-repository URL. See [GitHub's Pages instructions](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site).

## Content updates

- Edit copy in `index.html` and styling in `assets/styles.css`.
- The five JPEG images were extracted without recompression from the supplied HTML.
- App Store URLs were not supplied. The availability section says **Coming soon**; replace those informational labels with real download links when the apps are publicly available. Do not substitute a TestFlight invitation or an App Store Connect management URL.
- This landing page does not add a support form or privacy policy. Those require the owner's approved details/content separately.
- No app source or build numbers were changed.

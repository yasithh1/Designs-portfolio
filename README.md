# Yasith Pasindu — design & motion portfolio

A responsive portfolio built as a single static page. No build tools or dependencies are required.

## Make it yours

1. Open `index.html` to change your name, email address, social profile URLs, location, and project descriptions. The contact email and all four social links are already set to the details supplied for Yasith Pasindu.
2. Update the `projects` list near the bottom of the file to change titles, descriptions, or Drive file IDs. The supplied cards use Google Drive thumbnails and embedded previews. Keep each file shared so anyone with its link can view it; otherwise visitors may see an access request instead of the work.
3. Add your portrait as `assets/profile.jpg` to replace the initials in the About section.
4. Video and design cards use the Google Drive embedded preview. Each panel links to the original file as a fallback. The embedded video preview requires Google Drive to finish processing the uploaded video.

## Preview locally

Open `index.html` in a browser, or run `python -m http.server 8000` from this folder and visit `http://localhost:8000`.

## Publish with GitHub Pages

Push this project to a GitHub repository. In the repository, open **Settings → Pages** and select **GitHub Actions** as the build and deployment source. The included workflow publishes the site when changes are pushed to `main` or `master`; the deployed URL appears under the repository’s Pages settings. For a custom domain, configure it there after the first deployment.

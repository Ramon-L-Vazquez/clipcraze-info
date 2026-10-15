# ClipCraze information website

The public information website for ClipCraze, hosted using GitHub Pages.

- Website: https://ramon-l-vazquez.github.io/clipcraze-info/
- Terms: https://ramon-l-vazquez.github.io/clipcraze-info/terms/
- Privacy: https://ramon-l-vazquez.github.io/clipcraze-info/privacy/

This repository contains only static public HTML, CSS, and the ClipCraze logo. The app dashboard, media processing, account credentials, and private workspace remain local.

## Publishing

GitHub Pages publishes the root of the `main` branch. The `.nojekyll` file keeps the site buildless. No dependencies, build command, or runtime secrets are required. Internal asset and page URLs include the `/clipcraze-info/` project prefix.

For a local preview, serve the parent directory with `python -m http.server 5188 --bind 127.0.0.1` and open `http://127.0.0.1:5188/clipcraze-info/`.

Keep the TikTok Login Kit Desktop callback on `http://localhost:5000/auth/tiktok/callback`. The public website URLs and the local callback have different purposes.

Before updating policies or publishing, check that the wording matches the current app and that no private files or credentials have been added.

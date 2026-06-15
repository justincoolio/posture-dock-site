# Posture-Dock Website

A minimal static site for Posture-Dock. It provides an App Store download link,
privacy policy, and End User License Agreement.

The project uses only HTML and CSS. It has no framework, build process, package
manager, or runtime dependency.

## Project Structure

```text
.
├── index.html
├── privacy-policy.html
├── eula.html
├── styles.css
└── README.md
```

## Run Locally

You can open `index.html` directly in a browser, or serve the directory with a
simple local HTTP server:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Deploy with GitHub Pages

1. Push the repository to GitHub.
2. Open the repository’s **Settings**.
3. Select **Pages** under **Code and automation**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder.
6. Select **Save**.

GitHub Pages will publish the site without a build step. Replace the placeholder
App Store URL in `index.html` when the final product listing is available.

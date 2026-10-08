# Darya Zare — personal website

A minimal academic website, ready for GitHub Pages. It uses plain HTML and CSS, self-hosted Inter fonts, and no JavaScript or build tools.

## Preview

Open `index.html` in your browser. The portrait, fonts, and CV are included, so the site works offline.

## Publish on GitHub Pages

1. Create a public repository named **DaryaZareM.github.io** on the **DaryaZareM** account. If this repository already exists, preserve its contents and use a branch or pull request to review changes before replacing an existing site.
2. Upload the contents of this folder to the repository root. `index.html` must be at the top level, beside `style.css` and `assets/`.
3. Open **Settings → Pages**. Under **Build and deployment**, select **Deploy from a branch**. Choose **main** and **/ (root)**, then click **Save**.
4. The site will appear at **https://DaryaZareM.github.io/** after GitHub finishes deploying it. The repository name and URL assume the GitHub username in the supplied résumé is current.

No GitHub Actions workflow or dependency installation is needed. The `.nojekyll` file tells GitHub to serve the static site directly.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Edit the content

- **Bio, research, publications, experience, and projects:** edit `index.html`.
- **Typography, colors, spacing, and mobile layout:** edit `style.css`.
- **Portrait:** replace `assets/darya.png`.
- **CV:** replace `assets/Resume_DaryaZare.pdf`, preserving the filename, or update both CV links in `index.html`.

The current roles and dates follow the résumé supplied on 7 October 2026. Publication titles, authors, and publication years were checked against the publisher pages. The ASONAM paper appeared in the proceedings in January 2025 for the 2024 conference. LinkedIn is linked as supplied; it was not accessible for content verification.

## Files

```text
index.html
style.css
.nojekyll
assets/
  darya.png
  Resume_DaryaZare.pdf
  fonts/
    Inter-Regular.woff2
    Inter-Semibold.woff2
    OFL.txt
```

The Inter typeface is licensed under the SIL Open Font License 1.1; the font license is included. The website does not include analytics, tracking, or external font requests.

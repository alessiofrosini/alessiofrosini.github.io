# Alessio Frosini

Personal academic website covering research, teaching, talks, and contact information.

## Files

- `index.html` contains the website content, styles, and mobile navigation.
- `picture.png` is the portrait displayed beside the introduction.
- `.nojekyll` configures GitHub Pages to serve the static files directly.

The website needs no package installation or build step.

## Editing

Open `index.html` in a text editor to update the biography, ongoing research,
teaching, talks, or contact details. Save the file and open it in a browser to
preview changes.

To change the portrait, replace `picture.png` in the same directory as
`index.html`. The full portrait keeps its original proportions and moves below
the introduction on smaller screens.

Store any additional images or PDFs alongside the website or in an `assets`
directory, and link to them using relative paths.

## Publishing with GitHub Pages

For a personal website, use a repository named `USERNAME.github.io`, replacing
`USERNAME` with the account's GitHub username in lowercase. If that repository
already exists, review its contents before uploading files.

1. Put `index.html`, `picture.png`, `.nojekyll`, and this `README.md` in the repository root on the `main` branch.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select **main** and **/(root)**, then save.

The website address will be `https://USERNAME.github.io/`. Changes committed to
the publishing branch update the website. Public repositories support GitHub
Pages on GitHub Free.

[GitHub Pages documentation](https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site)

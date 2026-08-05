# Economics Job Market Website

This is a lightweight GitHub Pages website for an economics PhD candidate on the academic and nonacademic job market. It uses plain HTML and CSS, so there is no build step.

## Local Preview

Open `index.html` in your browser. The site is static, so it does not need a local development server.

## What To Personalize

1. Replace `Pablo [Last Name]` in `index.html` with your full name.
2. Update your university, city, fields, email, GitHub, LinkedIn, and Google Scholar links.
3. Replace the research placeholders with your job market paper, working papers, abstracts, slides, and manuscripts.
4. Add your CV as `assets/cv.pdf`.
5. Change the CV button in `index.html` from:

```html
<a class="button button-primary" href="#contact">Request CV</a>
```

to:

```html
<a class="button button-primary" href="assets/cv.pdf">Download CV</a>
```

## Publish With GitHub Pages

For a personal GitHub Pages site, create a public repository named exactly:

```text
your-github-username.github.io
```

Then put these files at the top level of that repository:

```text
index.html
styles.css
assets/
README.md
.nojekyll
```

Commit and push the files. GitHub Pages uses an `index.html`, `index.md`, or `README.md` file as the site entry point. For a user site, GitHub's docs say the repository name must be `<user>.github.io`, using lowercase if your username contains uppercase letters.

After pushing, open:

```text
https://your-github-username.github.io
```

If the site does not appear immediately, wait a few minutes and check the repository's **Settings > Pages** page.

GitHub's current Pages documentation is here:

- https://docs.github.com/en/pages/getting-started-with-github-pages/creating-a-github-pages-site

## Suggested Next Additions

- Add a professional headshot once you have one.
- Add a `papers/` folder for PDFs and a `slides/` folder for presentations.
- Add a custom domain later if you want a cleaner URL.
- Add analytics only if you are comfortable with the privacy tradeoffs.

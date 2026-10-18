# Ananya Singha Roy — Fall 2027 Academic Portfolio

Responsive academic portfolio for PhD applications in the United States, focused on scientific machine learning, inverse problems, and computational science.

Publication target: https://ananyasroy29.github.io/

## Source

- `index.html`: research, projects, education, and Fall 2027 doctoral interests.
- `styles.css`: responsive layout, keyboard focus, reduced motion, and print styles.
- `script.js`: accessible mobile navigation and footer year.
- `assets/`: original schematic flow illustration and site branding.
- `assets/ananya-singha-roy.jpg`: supplied profile photo, displayed beside the introduction.
- `.nojekyll`: supports serving this folder as a standalone GitHub Pages site.
- `sitemap.xml`: canonical page URL.

There is no dependency installation or framework build. All published paths are relative, so the website also works in a subdirectory.

## Publishing

The publication target is the root of the `main` branch of `Ananyasroy29/Ananyasroy29.github.io`.

1. Upload `index.html`, `styles.css`, `script.js`, `sitemap.xml`, `.nojekyll`, `README.md`, `LICENSE`, and the entire `assets/` directory into the repository root. Do not put them inside an extra parent folder.
2. Commit the files to `main`.
3. In repository **Settings → Pages**, choose **Deploy from a branch**, select **main** and **/(root)**, then save.
4. Wait for the Pages deployment to succeed, then open https://ananyasroy29.github.io/.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

`ananya-github-pages.zip` contains the upload files at its root. Extract it before using GitHub's upload page; uploading the ZIP alone will not publish the website. Local deployment records are excluded from the archive.

## Local preview

```bash
python3 -m http.server 8000
```

Visit http://localhost:8000. The site also opens directly from `index.html`.

## Content maintenance

Academic details come from the supplied website. The manuscript remains **in preparation**. Experimental percentages from the original draft are omitted because that draft identified them as needing verification. The flow graphic is labeled as a schematic and is not experimental data.

Ananya's GitHub profile is https://github.com/Ananyasroy29 and is linked on the website. No email address, LinkedIn profile, or CV was supplied; those links are omitted until the real details are available.

Site template code is MIT licensed. Personal and research content remains the property of its respective owners.

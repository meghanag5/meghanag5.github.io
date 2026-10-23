# Meghana Gotety — Portfolio

A static personal portfolio with applied AI case studies, professional experience, and a resume. No dependency installation or build command is needed.

## Publish through your own GitHub account

1. Extract this ZIP on your computer.
2. Sign into the GitHub account `meghanag5`.
3. Create a public repository named exactly `meghanag5.github.io`. If it already exists, review its current contents before replacing anything.
4. Initialize it with a README so the main branch exists.
5. In the repository, choose Add file → Upload files.
6. Upload the extracted files themselves, not the ZIP or its enclosing folder. `index.html` must be at the top level next to the other HTML files and resume PDF. This README can replace the initial README.
7. Commit the upload to main.
8. Open Settings → Pages. Under Build and deployment choose Deploy from a branch, main, and / (root), then Save.
9. Wait for GitHub's publication to finish. The intended address is https://meghanag5.github.io/ (it is not verified live by this package).
10. Test the homepage, project links, resume PDF, email, and social links before adding the URL to applications.

This package uses links beginning with `/`, so the username.github.io repository name matters. A repository named meghana-portfolio would publish under a subdirectory and require changing those links.

## Files

- index.html — homepage, experience, about, and contact
- editguard.html — CRISPR ML evaluation case study
- document-intelligence.html — Outamation document pipeline case study
- study-spotter.html — full-stack project case study
- product-automation.html — RWC automation case study
- meghana-gotety-resume.pdf — the resume supplied for the portfolio
- .nojekyll — optional marker to skip Jekyll processing; static HTML works if your browser uploader omits this hidden file

The resume PDF contains your phone number and email. Publishing this repository also publishes the included resume.

## Preview and edit locally

Open the extracted folder in VS Code. To preview root-relative links correctly, run:

    python3 -m http.server 8000

Then visit http://localhost:8000/. Double-clicking an HTML file can break root-relative navigation.

Edit the HTML files directly. CSS is embedded in each page's style element; update shared styles across pages when changing the overall design. Commit changes to the main branch to update the published website.

## Remaining evidence to add

The site links to your GitHub profile. Repository-specific project URLs, actual application screenshots, and live project demos still need to be connected. Planned features are labeled as planned; the case studies do not imply those features are already deployed.

## Ownership and portability

This is a portable export of the current site. It contains no Sites hosting configuration, account credentials, analytics, external JavaScript, or package dependencies. Future changes to your personal GitHub deployment and the original hosted Site are separate; they do not automatically synchronize.

## Official documentation

https://docs.github.com/en/pages/quickstart
https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

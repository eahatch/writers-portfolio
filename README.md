# Writer’s Portfolio

A responsive, accessible static portfolio prepared for GitHub Pages. No build tools, dependencies, or JavaScript required.

## Publish on GitHub Pages

1. Create a **public** GitHub repository named `writers-portfolio` (or another preferred name).
2. Upload **the contents of this folder** to the repository root. Include `.nojekyll` if using Git; it is optional for this plain HTML site. Do not upload the outer folder or the ZIP itself.
3. In the repository, open **Settings → Pages**. Under Build and deployment, select **Deploy from a branch**, choose **main** and **/(root)**, and save.
4. Wait for the Pages deployment to finish. GitHub provides the site URL in that settings page, normally `https://USERNAME.github.io/writers-portfolio/`.
5. Check every page at that URL before sharing it. If Pages is unavailable, check your account/organization policy and repository visibility.

Custom domain setup can follow later. No domain configuration is included because the domain was not supplied. GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Edit the portfolio

- `index.html`: homepage and introduction.
- `selected-work.html`: artifact index.
- `work/position-paper.html`, `work/status-report.html`, `work/outside-course.html`: artifact pages and reflection prompts.
- `writing-approach.html`: proposed thesis and outline; **not a completed 750–1,500-word statement**.
- `resume.html`: web résumé placeholder.
- `about.html`: biography and contact placeholders.
- `assets/style.css`: layout, colors, typography.
- `documents/`: add final PDFs here, then create links from the appropriate pages. Example from `work/position-paper.html`: `<a href="../documents/position-paper.pdf">Download the position paper (PDF)</a>`.

All navigation uses relative paths so the site works at a GitHub Pages project URL or a custom domain. Shared navigation/footer markup is repeated across the eight HTML files; update each when renaming the site or changing navigation.

## Before submitting

- Replace “Writer’s Portfolio” with your chosen public name in every HTML file.
- Add the real documents, their context, your role, and your reflections.
- Identify at least one artifact from this course and one from outside it. The extra outside-course page is reserved to ensure this requirement is addressed; adjust the collection once origins are confirmed.
- Complete the theory statement (750–1,500 words), integrating actual artifact evidence and course scholarship. Add references in the required style.
- Add your résumé and chosen public contact information.
- Remove placeholder notices only once the corresponding content is complete.
- Check document links, keyboard navigation, and mobile layout.

## Preview locally

From this folder, run `python3 -m http.server 8000`, then open http://localhost:8000. Stop the server with Ctrl+C.

## Future creative-writing iteration

Keep the domain and basic structure. Replace the homepage focus, introduce creative categories in Selected Work, and retain or archive the technical writing collection as desired. No platform migration is required.

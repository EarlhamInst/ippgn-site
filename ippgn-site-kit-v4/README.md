# International Plant Pangenome Network site kit

This starter kit is designed for a small, polished GitHub Pages site.

## Edit the text first
Before handing the repository to Codex, edit these files:
- `docs/copy/home.md`
- `docs/copy/how-we-work.md`
- `docs/copy/people.md`
- `docs/copy/contact.md`

These are the clean text drafts you can amend without touching the HTML.

## Website files
The actual site lives in `site/`.

## Logo placeholders
The header and homepage already reserve space for:
- a future network logo
- a future Earlham Institute logo

No logo files are included yet.

## Contact form
The contact page is set up as a static HTML form suitable for GitHub Pages.
To make it live, replace the placeholder `FORM_ENDPOINT_HERE` in `site/contact.html` with your form endpoint.

A simple route is to use a static-site form handler such as Formspree. If you prefer not to show a public email address, keep the form and leave the direct email hidden. If you later create a shared or role-based mailbox, you can add it to the page footer or contact panel.

## GitHub Pages
For a very simple setup, publish the contents of `site/` using GitHub Pages.

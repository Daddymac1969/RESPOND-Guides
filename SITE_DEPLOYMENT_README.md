# RESPOND Guide Library — GitHub + Netlify deployment

This is the standalone Netlify website, ready to place at the root of a dedicated GitHub repository. It is separate from your existing RESPOND Safeguarding website.

## Top-left icon layout

Every HTML page has its matching supplied favicon in a white, full-width masthead at the top-left, outside the coloured guide/library banner, matching the screenshot of Scenario 101. The icon links back to this Guide Library home page. The corresponding browser-tab icon is preserved. Styling is shared in `assets/page-icon-header.css`; the original `assets/library.css` and guide content are not modified.

## Publish via GitHub Desktop and Netlify

1. Create a dedicated GitHub repository (e.g. `respond-guide-library`) and clone it with GitHub Desktop.
2. Extract the ZIP and copy **its contents**, rather than the ZIP itself, into the repository root. `index.html` must appear at the root.
3. Commit and push the changes through GitHub Desktop; this avoids GitHub's browser limit of fewer than 100 files per upload.
4. In Netlify, choose **Add new project** and import the dedicated GitHub repository. Leave build command empty; publish directory is `.` (already set in `netlify.toml`).
5. Test the Netlify preview, confirm the URL and access permissions, and approve the outstanding safeguarding changes before public release.
6. Add a Guide Library link on your existing RESPOND Safeguarding website, pointing to the new Netlify domain.

**Safeguarding publication hold:** the content is preserved from the supplied archive. This layout-only rebuild does not approve or implement previously identified legal/safeguarding content amendments. If the site is public, staff guides and PDFs will also be public unless separate access controls are configured.

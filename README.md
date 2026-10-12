# NYU_OPA

A free, single-page personal website template for postdocs. No coding experience needed.
Sections included: About Me, Recent News, Publications, Presentations, and Resources.

The website itself lives in the [`docs/`](docs) folder. Design adapted from "Read Only" by [HTML5 UP](https://html5up.net) (CCA 3.0).

## Get your own copy

1. Sign in to GitHub and click **Fork** (top right of this page), or **Use this template** / download the repo as a ZIP.
2. Make the edits described below.

## Publish it with GitHub Pages

1. In your repository, go to **Settings → Pages**.
2. Under **Build and deployment**, set **Source** to "Deploy from a branch".
3. Choose your branch (usually `main`) and the **/docs** folder, then click **Save**.
4. After a minute or two, your site will be live at `https://<your-github-username>.github.io/<repository-name>/`.

## Customize the site

Preview changes by double-clicking `docs/index.html` to open it in your browser. Edit files with a plain text editor (Notepad, VS Code), not Word. You can also edit files directly on GitHub (click a file, then the pencil icon).

### Text and links: `docs/index.html`
- Search (Ctrl+F) for `>>> EDIT <<<`. Each one marks text to change.
- Type over the placeholder text. Leave anything inside `< >` alone.
- To change a link, edit the web address inside `href="..."`.
- To add a news item, publication, or presentation, copy an existing block, paste it next to the original, and edit it. To remove one, delete the block.
- To remove a section, delete its `<section>` block and its line in the menu near the top.
- To remove a social icon, delete its `<li>` line. To add one, copy a line and change the `fa-...` name to any free icon from [Font Awesome](https://fontawesome.com/v5/search?m=free) (use `brands` or `solid` as in the existing lines).

### Images: `docs/images/`
Replace the placeholder files with your own, keeping the same file names:

| File | Used for | Suggested size |
|------|----------|----------------|
| `avatar.jpg` | Small photo in the left menu | 400 x 400 |
| `profile.jpg` | Photo next to your intro | 400 x 500 |
| `banner.jpg` | Wide banner image on each section | 2000 x 600 |
| `thumbs/` | News item images | 400 x 300 |
| `poster.jpg` | Poster linked from Presentations | any |
| `favicon.png` | Browser tab icon | 64 x 64 |

### CV: `docs/docs/CV.pdf`
Replace this file with your own CV, keeping the name `CV.pdf`.

### Colors: `docs/assets/css/theme.css`
The colors are listed at the top of the file (page, content, menu, links, text, and sidebar). Change the `#xxxxxx` codes. A color picker is available at [htmlcolorcodes.com](https://htmlcolorcodes.com).


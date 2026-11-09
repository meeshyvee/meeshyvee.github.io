# Backpack design system prototype

A clickable prototype of the Backpack design system site, covering **Campus**, **Course Pro** and the shared **Library**.

The whole site is one file, `index.html`. All images are built into it, so there is nothing else to upload.

## Publish it with GitHub Pages

1. Create a new repository on GitHub (for example `backpack-prototype`).
2. Upload `index.html` and this `README.md` to the root of the repository and commit.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose the **main** branch and the **/ (root)** folder, then **Save**.
5. After a minute or two, the site is live at `https://<your-username>.github.io/<repository-name>/`.

Share that link with stakeholders. Each page also has its own link:

| Page | Link ending |
| --- | --- |
| Home (backpack) | `/` |
| Campus | `/#campus` |
| Course Pro | `/#course-pro` |
| Library | `/#assets` |

GitHub Pages is free for public repositories. A private repository needs a paid GitHub plan to use Pages.

## Good to know

- **Internet needed.** Fonts (Google Fonts), icons (Font Awesome Free) and the zip tool for "Download all" load from public CDNs.
- **Edits aren't saved.** Typing in the type samples or moving objects on the home page resets on reload.
- **Real vs. placeholder content.**
  - Real: Campus and Course Pro token values, all colors, the token CSS/JSON downloads, and the image downloads.
  - Placeholder: the Markdown guides (marked "Not published yet"), the Figma library link, and the Campus type scale (marked "Proposed").
- **Icons.** The icon preview uses the free Font Awesome set. Campus ships Font Awesome 7 Pro, so some Pro-only icons show as "Not found" here.

## Updating the site

Replace `index.html` in the repository with a new version and commit. GitHub Pages republishes automatically.

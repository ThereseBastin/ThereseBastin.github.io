# Thérèse Bastin — academic website

A lightweight academic website prepared for GitHub Pages.

## 1. Replace the portrait

Place your photograph in `assets/` and name it `profile.jpg`. Then replace this line in `index.html`:

```html
<img class="portrait" src="assets/profile-placeholder.svg" alt="Thérèse Bastin">
```

with:

```html
<img class="portrait" src="assets/profile.jpg" alt="Thérèse Bastin">
```

You can also remove the small sentence below the photograph.

## 2. Add the CV locally (optional)

Put the PDF in `assets/` as `Therese_Bastin_CV.pdf`, then replace the Google Drive URL in the “View my CV” button with:

```text
assets/Therese_Bastin_CV.pdf
```

## 3. Publish with GitHub Pages

### Recommended address: `https://YOUR-USERNAME.github.io/`

1. Create a public GitHub repository named exactly `YOUR-USERNAME.github.io`.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main`, folder `/ (root)`, and click **Save**.

### Alternative address: `https://YOUR-USERNAME.github.io/website/`

Create a repository named `website` instead and use the same Pages settings.

## 4. Edit the content

Most content is in `index.html`. Visual settings are in `style.css`.

Useful elements:

- `<section id="research">` — research projects
- `<section id="reports">` — reports and policy papers
- `<section id="presentations">` — conference list
- `<section id="contact">` — contact information

## Notes

- The site does not require a database, package manager, or build step.
- It is responsive and works on desktop and mobile.
- Abstracts use native HTML `<details>` elements, so no JavaScript library is required.

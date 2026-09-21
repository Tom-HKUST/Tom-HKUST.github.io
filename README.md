# Simple Academic Homepage

A minimal static academic homepage that can be hosted directly with GitHub Pages.

## Files

- `index.html` — homepage content
- `style.css` — page styling
- `.nojekyll` — tells GitHub Pages to serve the site as plain static files
- `cv.pdf` — add your own CV with this filename if you want the CV link to work

## 1. Edit your information

Open `index.html` and replace the placeholder text, especially:

- `YOUR NAME`
- `Department of XXX, University of XXX`
- `your.email@example.com`
- research interests
- publication titles, authors, venues, and links
- Google Scholar / GitHub / ORCID URLs

You can delete any section you do not need.

## 2. Add your CV

Put your CV PDF in the project root and name it:

`cv.pdf`

If you do not want to publish a CV, remove the CV link from `index.html`.

## 3. Optional profile photo

Put a photo in the project root as:

`photo.jpg`

Then find this line in `index.html`:

```html
<!-- <img class="profile-photo" src="photo.jpg" alt="Portrait of YOUR NAME" /> -->
```

Change it to:

```html
<img class="profile-photo" src="photo.jpg" alt="Portrait of YOUR NAME" />
```

## 4. Publish with GitHub Pages

### Simplest method

Create a GitHub repository named:

`YOUR_GITHUB_USERNAME.github.io`

For example, if your GitHub username is `zhangsan`, create:

`zhangsan.github.io`

Upload all files from this project to the repository root.

Your homepage should then be available at:

`https://YOUR_GITHUB_USERNAME.github.io`

It may take a short while for GitHub Pages to finish publishing after the first upload.

## 5. Using another repository name

You can also use a normal repository, for example:

`academic-homepage`

Then go to:

`Settings -> Pages`

Choose deployment from your main branch/root folder as appropriate for your GitHub Pages settings.

Your page URL will typically look like:

`https://YOUR_GITHUB_USERNAME.github.io/academic-homepage/`

## Updating the website

Edit `index.html`, upload/commit the new version, and GitHub Pages will publish the update.

No framework, package manager, server, or build step is required.

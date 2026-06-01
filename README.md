# Academic Website — Quarto + GitHub Pages

A minimal template for an academic personal website using [Quarto](https://quarto.org)
and hosted for free on [GitHub Pages](https://pages.github.com).

## What you get

- Home/about page with profile photo and social links
- Publications page
- Talks page
- Auto-deploys to GitHub Pages on every push

## The only files you need to edit

| File | What it controls |
|------|-----------------|
| `_quarto.yml` | Site title, navigation, theme colour |
| `index.qmd` | Your name, bio, photo, social links |
| `publications.qmd` | Your publications list |
| `talks.qmd` | Your talks and presentations |

## Setup (one time, ~15 minutes)

### 1. Fork or use this template on GitHub
Click **Use this template** → **Create a new repository**.
Name it whatever you like (e.g. `my-website`).

### 2. Enable GitHub Pages
In your new repo: **Settings → Pages → Source → GitHub Actions**

### 3. Edit your content
Open the files above and replace the placeholder content with your own.
Commit and push — the site builds automatically.

### 4. (Optional) Preview locally
If you have Quarto installed:
```bash
quarto preview
```

## Changing the theme
Edit `_quarto.yml` and change `theme: flatly` to any
[Bootswatch theme](https://bootswatch.com): `cosmo`, `litera`, `minty`,
`quartz`, `sandstone`, `yeti`, etc.

## Adding a profile photo
Drop a `profile.jpg` in the root folder and it will appear on the home page.

## Linking your CV
Put your CV PDF at `cv.pdf` in the root folder.
The navbar already has a CV link pointing there.

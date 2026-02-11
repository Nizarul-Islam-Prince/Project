# Project Repo Structure (Multi-Project Ready)

This repository is set up to host multiple static websites under one GitHub Pages project.

## Current Structure

- `index.html` (root): redirect entry point
- `abparlour/`: AB Parlour static site
- `.github/workflows/pages.yml`: GitHub Pages deployment workflow

Current live URL:
- `https://nizarul-islam-prince.github.io/Project/abparlour/`

## Add More Projects Later

When you add a new website, create a new folder at repo root, for example:

- `newproject/`
- `portfolio/`
- `shop/`

Then each project will be available like:
- `https://nizarul-islam-prince.github.io/Project/newproject/`
- `https://nizarul-islam-prince.github.io/Project/portfolio/`

## GitHub Pages Settings

1. Go to `Settings -> Pages`
2. Set `Source` to `GitHub Actions`
3. Keep using `main` branch with the existing workflow

## Notes

- AB Parlour is a WordPress mirror exported as static HTML.
- Contact form inside `abparlour/contact/index.html` points to WordPress backend and will not work as a fully static form unless replaced with a form service/API.

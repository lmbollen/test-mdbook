# mdBook + GitHub Pages Test Repository

This repository demonstrates how to use [mdBook](https://rust-lang.github.io/mdBook/) to create documentation and deploy it automatically to GitHub Pages.

## Features
- Basic mdBook setup
- Sample book content
- GitHub Actions workflow for deployment to GitHub Pages

## Quick Start

1. **Install mdBook**
   ```bash
   cargo install mdbook
   ```
2. **Build the book locally**
   ```bash
   mdbook build
   ```
3. **Serve the book locally**
   ```bash
   mdbook serve
   ```
   Then open [http://localhost:3000](http://localhost:3000) in your browser.

## Deployment
Deployment to GitHub Pages is automated via GitHub Actions. On every push to the `main` branch, the book will be built and published to the `gh-pages` branch.

## Directory Structure
- `book/` - The generated static site (ignored in git)
- `src/` - Markdown source files for the book
- `.github/workflows/` - GitHub Actions workflow files

## Customization
Edit the files in `src/` to change the content of your book.

---

Replace this README with your own project details as needed.

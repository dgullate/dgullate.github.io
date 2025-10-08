# David Gómez-Ullate Professional website

Public link: https://dgullate.github.io

Built from the Hugo Blox Pro template (academic-cv-pro).

## Develop locally

Follow the official Hugo install guide: https://docs.hugoblox.com/getting-started/install-hugo/

Preview the site locally (PowerShell):

```powershell
hugo server -D
```

Then open http://localhost:1313 in your browser.

## Content locations

The main author profile used on the front page is at `content/authors/admin/_index.md`.

Place `publications.bib` in the repository root. Updating this file triggers the import workflow `.github/workflows/import-publications.yml`, which converts the BibTeX file into `content/publication/` pages and opens a pull request.

## Large files and Git limits

GitHub rejects pushes that include individual files larger than 100 MB. If you accidentally committed a large file and want to undo your last local commit, you can run:

```powershell
# Option A: undo last commit but keep changes staged
git reset --soft HEAD~1

# Option B: undo last commit and discard local changes
git reset --hard HEAD~1
```

If you did more than one commit, you may need to run the command several times.

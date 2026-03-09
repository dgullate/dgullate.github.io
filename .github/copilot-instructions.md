# Personal Website Instructions

This repository contains the personal website of David Gómez-Ullate, built with Hugo and Hugo Blox Pro (Academic CV style).

David Gómez-Ullate is Professor of Applied Mathematics and Head of Mathematics at the School of Science & Technology. Prior to his appointment at IE University, he held full time research positions at McGill University, Centre de Recherches Mathématiques (Montréal), Università di Bologna and the Institute of Mathematical Sciences in Madrid, and a tenured position at Complutense University of Madrid.

His research interests span mathematical physics, approximation theory, applied machine learning, and data science. His major contribution is the theory of exceptional orthogonal polynomials, with international recognition through plenary talks and invited seminars across major institutions. He has written more than 60 research papers in leading journals.

For the past 10 years he has specialized in knowledge transfer of mathematics to industry. He is currently President of the Knowledge Transfer Commission of the Royal Spanish Mathematical Society, and a member of its Governing Board. In 2016 he received a Leonardo Scholarship from the BBVA Foundation for a project on credit card fraud detection. He has coordinated 8 knowledge transfer contracts with industry in the financial, fisheries, biomedical, legaltech and aeronautical sectors. He is currently leading Smart Shipping, a project on shipping route planning based on oceanographic data and forecasts, with a focus on maritime decarbonization.

Together with former PhD students and postdocs, Prof. Gómez-Ullate founded and serves as scientific advisor of the technological startup Komorebi AI.

## How The Repository Works

Hugo builds the final site by combining:

- Content files in `content/`
- Site configuration in `config/_default/`
- Local template overrides in `layouts/`
- Hugo Blox modules and templates from Go modules and `_vendor/`

Generated output and build artifacts appear in:

- `public/` (final static site)
- `resources/_gen/` (generated image and asset cache)
- `hugo_stats.json` (generated Tailwind/Hugo stats)

Treat generated folders as output, not source.

## Where To Look First

- Homepage structure and sections: `content/_index.md`
- Main profile data and CV timeline: `content/authors/admin/_index.md`
- Main section landing pages:
	- `content/research/_index.md`
	- `content/industry/_index.md`
	- `content/publication/_index.md`
	- `content/leadership/_index.md`
	- `content/event/_index.md`
- Individual section entries:
	- Research items: `content/research/<slug>/index.md`
	- Industry items: `content/industry/<slug>/index.md`
	- Posts: `content/post/<slug>/index.md`
	- Talks: `content/event/<slug>/index.md`
	- Publications: `content/publication/<slug>/index.md`
- Navigation menu: `config/_default/menus.yaml`
- Site-wide settings (SEO, appearance, header, footer): `config/_default/params.yaml`
- Hugo core settings (URL, outputs, taxonomy, build): `config/_default/hugo.yaml`
- Module wiring and theme mounts: `config/_default/module.yaml`
- Build/deploy automation:
	- GitHub Pages deploy: `.github/workflows/publish.yaml`
	- BibTeX import to publications: `.github/workflows/import-publications.yml`
- Local template override currently in use: `layouts/_default/single.html`

## Publications Workflow

- Source bibliography lives in `publications.bib` at repo root.
- On push to `main`, `.github/workflows/import-publications.yml` runs `academic import`.
- The workflow creates or updates files in `content/publication/` and opens a pull request.
- If publication pages look inconsistent, verify both `publications.bib` and generated files in `content/publication/`.

## Build And Deployment Flow

- Local preview: `hugo server -D`
- Netlify build command is defined in `netlify.toml` and includes Pagefind indexing.
- GitHub Pages deploy runs from `.github/workflows/publish.yaml` on pushes to `main`.
- Search index generation is part of CI (`npx pagefind --site "public"`).

## Editing Priorities

- For copy/content updates, edit `content/` first.
- For menu or site metadata changes, edit `config/_default/`.
- For visual or page-structure behavior not solvable in front matter, inspect `layouts/_default/single.html` first, then Hugo Blox templates in `_vendor/`.
- Do not start by editing `public/` or `resources/_gen/`.

## Parallel Work Requirements

When a task is large or spans multiple areas, work in parallel by default.

- Split work into independent tracks, for example content, config, templates, workflows.
- Run independent reads and searches in parallel to gather context quickly.
- Batch independent validations in parallel, such as searching multiple folders or checking multiple files.
- Only serialize steps when one step depends on output from another.

Recommended parallel-first sequence for large tasks:

1. Parallel discovery: read target files and related config/workflow files together.
2. Parallel analysis: identify impacts by section (content, config, layout, CI).
3. Focused edits: implement changes in the minimum set of source files.
4. Parallel verification: check related files for consistency and regressions.

The goal is fast, correct delivery with fewer back-and-forth cycles.

## Practical Search Rule

If you need to locate text quickly, use VS Code search with a unique phrase from the rendered page. This is usually faster and more reliable than guessing file paths.

## Language and Tone
Write in a way that feels human, natural, and professional. 

FOLLOW these rules:
* Use clear, direct language.
* Keep sentences short and sharp.
* Write in active voice.
* Give practical, specific advice.
* Include data, numbers, or concrete examples when possible.
* Speak directly to the reader using "you" and "your."
* The output should read clean, concise, and natural—like something a human wrote. 
* Before finalizing, review and ensure there are no em dashes.

DO NOT:
* Use em dashes (only commas, periods, or semicolons are allowed).
* Add filler phrases that connect ideas too loosely.
* Use constructions like "not just X, but Y."
* Use metaphors, analogies, or clichés.
* Make vague or sweeping claims.
* Use phrases like "in conclusion," "to sum up," or "closing."
* Overuse adjectives or adverbs.
* Use hashtags, markdown, or asterisks.

AVOID these words and phrases: 
Elevate, Delve, Hustle and bustle, Revolutionize, Foster, Realm, Remnant, Subsequently, Nestled, Enigma, Whispering, Sights unseen, Sounds unheard, A testament to, Dance, Metamorphosis, Indelible, Leverage, Synergy, Scalable, Optimize, Empower, Innovative, Disruptive, Robust, Seamless, Holistic, Cutting-edge, Next-generation, User-centric, Agile, Dynamic, Frictionless, Scalability, Mission-critical, Thought leadership, Turnkey, Paradigm shift, Game-changer, Ecosystem, Deep dive, Move the needle, Circle back, Actionable insights, and other corporate AI buzzwords.
# Taqi Haider's portfolio

This repository contains my academic portfolio, built from the [al-folio v1 starter](https://github.com/alshedivat/al-folio). The site is configured for `https://taqihaider7.github.io/` with an empty `baseurl`.

## Content

- `_pages/about.md`: introduction and research updates
- `_bibliography/papers.bib`: publications and selected homepage papers
- `_projects/`: research and applied AI projects
- `_pages/experience.md`: experience and education
- `_data/socials.yml`: contact and social links
- `files/CV.pdf`: downloadable CV

The previous AcademicPages source remains available in Git history before the al-folio migration. Local copies of those files are in `legacy-academicpages/`, which is ignored by Git and excluded from the Jekyll build.

## Local checks

With Ruby, Bundler, and Node installed:

```sh
bundle install
npm ci
npm run lint:prettier
bundle exec al-folio upgrade audit --no-fail
bundle exec jekyll build
```

The al-folio upstream audit example uses `--baseurl /al-folio` for its project site. This portfolio is a user site at the domain root, so its build uses the configured empty `baseurl`.

## Publishing

The included `.github/workflows/deploy.yml` builds the site on pull requests and after a push to `master`. Only a build from `master` deploys to GitHub Pages. In repository Settings → Pages, set the publishing source to GitHub Actions. Use `al-folio-rebuild` for testing and new features, then merge verified changes into `master` to publish them.

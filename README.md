# JamunaSMurthy.github.io

Source for [Jamuna S Murthy's academic website](https://jamunasmurthy.github.io), built with Jekyll on the
[AcademicPages](https://academicpages.github.io/) template (a fork of Minimal Mistakes).

## Editing

- Home page: `_pages/about.md`
- CV page: `_pages/cv.md` (PDF served from `files/JamunaSMurthy_CV.pdf`)
- Publications: one Markdown file per paper in `_publications/`; figures live in `images/papers/`, PDFs in `files/`
- Teaching: `_teaching/`
- Site settings, name, links, and sidebar profile: `_config.yml`

## Run locally

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open http://localhost:4000.

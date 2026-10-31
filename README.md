# Tin Sum Cheng: personal website

Source of [tscheng516.github.io](https://tscheng516.github.io), built with Jekyll on the [AcademicPages](https://github.com/academicpages/academicpages.github.io) template (a fork of Minimal Mistakes, MIT licensed, see `LICENSE`).

## Where things live

| What | Where |
|---|---|
| Site settings, sidebar bio, social links | `_config.yml` |
| Top navigation | `_data/navigation.yml` |
| Home page, CV | `_pages/about.md`, `_pages/cv.md` |
| Publications (one file each; `status: published` or `preprint`) | `_publications/` |
| Teaching | `_teaching/` |
| Notes (blog) | `_posts/` |
| CV PDF, papers | `files/` |

## Run locally

```bash
bundle install
bundle exec jekyll serve   # http://localhost:4000
```

The repository must be named `tscheng516.github.io` so that the site is served from the root (`baseurl: ""` in `_config.yml`).

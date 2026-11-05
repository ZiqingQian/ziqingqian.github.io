# Ziqing Qian's Academic Homepage

Personal academic homepage of **Ziqing Qian** (Ph.D. Candidate, Tongji University),
built with the [academic-homepage](https://github.com/luost26/academic-homepage) Jekyll template.

Live at: https://ziqingqian.github.io

## Sections

- **Profile / About**: brief bio, research interests (Complex Network, Data Science, Science of Science)
- **Publications**: 5 selected papers (ICCV 2025, AAAI 2026, Nature Human Behaviour, NeurIPS 2026, arXiv)
- **News**: recent updates

## Run locally

```bash
bundle install
bundle exec jekyll serve
```

Then open http://localhost:4000

## How to update

- `_data/profile.yml` – bio, email, social links, education
- `_publications/<year>/*.md` – add/edit papers (see existing files for the front-matter format)
- `_news/*.md` – add news items

## Deploy

Push to the `main` branch of `ZiqingQian/ziqingqian.github.io`;
GitHub Pages builds the Jekyll site automatically.

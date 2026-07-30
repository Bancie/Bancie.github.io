# Bancie.github.io

Personal portfolio site for **Nguyễn Chí Bằng**, hosted on GitHub Pages at [https://bancie.github.io](https://bancie.github.io).

Built with [Jekyll](https://jekyllrb.com/) and the [Minimal theme](https://github.com/pages-themes/minimal). Content is sourced from `CV/Recent_Grad_Resume_Template/cv_2.tex`.

## Local development

```bash
bundle install
bundle exec jekyll serve
```

Open [http://localhost:4000](http://localhost:4000).

## Replace profile photo

1. Add your photo to `assets/images/` (for example `avatar.jpg`).
2. Update `logo` in `_config.yml`:

```yaml
logo: /assets/images/avatar.jpg
```

## Structure

- `index.md` — About (intro, education, skills, research)
- `experience.md` / `competitions.md` / `volunteers.md` / `references.md` — About section pages
- `projects.md` — Projects
- `cv.md` — CV download
- `files/cv.pdf` — PDF resume

## Deployment

Push to `main` and enable GitHub Pages: **Settings → Pages → Deploy from branch `main` / root**.

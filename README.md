# jbarao04.github.io

Personal website of João Barão, live at <https://jbarao04.github.io>.

Built with [Jekyll](https://jekyllrb.com/) and the [al-folio](https://github.com/alshedivat/al-folio) starter (MIT License), hosted on GitHub Pages.

## Where things live

| What                        | File                                                                             |
| --------------------------- | -------------------------------------------------------------------------------- |
| Name, site URL, footer      | `_config.yml`                                                                    |
| Home page text and photo    | `_pages/about.md`, `assets/img/prof_pic.jpg`                                     |
| Publications                | `_bibliography/papers.bib` (add `selected = {true}` to show on the home page)    |
| Projects                    | `_projects/*.md`                                                                 |
| CV page                     | `_data/cv.yml`; PDF at `assets/pdf/JoaoBarao_CV.pdf`                             |
| Social links                | `_data/socials.yml`                                                              |
| News items (off by default) | add files to `_news/` and set `announcements.enabled: true` in `_pages/about.md` |

## Deploying

Every push to `main` runs `.github/workflows/deploy.yml`, which builds the site and publishes it to the `gh-pages` branch.
In the repository settings, **Pages → Build and deployment** must be set to _Deploy from a branch_, branch `gh-pages`, folder `/ (root)`.

The al-folio guides are in `docs/` (start with `docs/CUSTOMIZE.md`).

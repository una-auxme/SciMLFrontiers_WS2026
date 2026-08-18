# SciMLFrontiers_WS2026

Website for the workshop "SciML Frontiers: Progress, Evolution, and Future Directions",
held on 22–23 September 2026 at the University of Augsburg.

The workshop is organised by Prof. Lars Mikelsons, Prof. Michael Schlottke-Lakemper and
Andreas Hofmann, and hosted by the
[Centre for Advanced Analytics and Predictive Sciences](https://www.uni-augsburg.de/en/forschung/einrichtungen/institute/caaps/)
at the University of Augsburg.

## Building the site

The site is built with [Quarto](https://quarto.org). From the `website/` directory:

```bash
quarto preview   # local preview with live reload
quarto render    # build into website/_site
```

Pushing to `main` renders the site via GitHub Actions and publishes it to the `gh-pages`
branch.

## Licence

The **source code** in this repository — Quarto sources, `styles.css`, the GitHub Actions
workflow, and the topic illustrations `website/assets/topic_*.svg` — is licensed under the
MIT licence, see [LICENSE](LICENSE).

The following files are **not** covered by the MIT licence and may not be reused without
permission of the respective rights holders:

| File | Rights |
|------|--------|
| `website/assets/UNIA.png` | Logo and trademark of the University of Augsburg, taken from the university corporate design resources |
| `website/assets/building_w.jpg` | Photograph from the University of Augsburg corporate design resources |
| `website/assets/workshop_logo*.png` | Workshop logo, all rights reserved |
| `website/assets/prof_mikelsons.jpg` | Portrait photograph, all rights reserved |
| `website/assets/prof_schlottkelakemper.png` | Portrait photograph, all rights reserved |
| `website/assets/hofmann.jpg` | Portrait photograph, all rights reserved |

The files taken from the university corporate design resources have been renamed for use on
the web; their content is unchanged. They are not covered by the MIT
licence of this repository.

This website is based on [trudi-2026](https://github.com/trixi-framework/trudi-2026),
published under the MIT licence. See [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md) for
the full notice and [CONTRIBUTORS.md](CONTRIBUTORS.md) for authorship.

# UAOA Microcredential — course preview

Stakeholder landing page for **per-language HTML course exports**.

**Live site:** https://jhendri4.github.io/uaoa-course-preview/

## English preview (GitHub Pages)

Public Pages hosts **English only** so deploys stay under GitHub’s size/time limits (~63MB vs ~370MB for all six languages).

| Path | Language |
|------|----------|
| [`previews/en/`](previews/en/) | English |

`index.html` at the site root is a one-language landing page linking to `previews/en/`.

## Refresh English

1. Export HTML for **English** from ScormStack and unzip.
2. Replace `previews/en/` so `previews/en/index.html` opens the player.
3. Commit and push `main` — GitHub Pages rebuilds from `/`.

Other locales: use ScormStack preview or add a locale folder locally; do not commit extra full exports to `main` unless Pages limits are addressed (e.g. separate repos per language).

## Related

- Course source: [ND-DAC-DOME/uaoa-elearning](https://github.com/ND-DAC-DOME/uaoa-elearning)
- Widget gallery: [uaoa-interactive-review](https://jhendri4.github.io/uaoa-interactive-review/)
- Translation review: [uaoa-i18n-review](https://jhendri4.github.io/uaoa-i18n-review/)

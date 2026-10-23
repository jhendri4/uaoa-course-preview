# UAOA Microcredential — course preview

Stakeholder landing page for **per-language HTML course exports**.

**Live site:** https://jhendri4.github.io/uaoa-course-preview/

## Languages

| Path | Language |
|------|----------|
| [`previews/en/`](previews/en/) | English |
| [`previews/es/`](previews/es/) | Español |
| [`previews/fr/`](previews/fr/) | Français |
| [`previews/cs/`](previews/cs/) | Čeština |
| [`previews/sl/`](previews/sl/) | Slovenščina |
| [`previews/sv/`](previews/sv/) | Svenska |

Each folder is a ScormStack **HTML export** with `index.html` as the player entry point.

## Refresh an export

1. Export HTML for that language from ScormStack and unzip.
2. Replace `previews/<locale>/` contents so `previews/<locale>/index.html` opens the player.
3. Commit and push `main` — GitHub Pages rebuilds from `/`.

## Related

- Course source: [ND-DAC-DOME/uaoa-elearning](https://github.com/ND-DAC-DOME/uaoa-elearning)
- Widget gallery: [uaoa-interactive-review](https://jhendri4.github.io/uaoa-interactive-review/)
- Translation review: [uaoa-i18n-review](https://jhendri4.github.io/uaoa-i18n-review/)

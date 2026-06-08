![Metrics](/github-metrics.svg)

# magicsunday

Open-source PHP and JavaScript projects, with a focus on **genealogy
visualization for [webtrees](https://www.webtrees.net)** and reusable
metadata / mapping libraries.

## webtrees

Interactive D3.js chart modules and tooling for the webtrees genealogy application.

| Repository | What it is |
| --- | --- |
| [webtrees-fan-chart](https://github.com/magicsunday/webtrees-fan-chart) | SVG ancestor fan chart — zoom, export, up to 10 generations |
| [webtrees-pedigree-chart](https://github.com/magicsunday/webtrees-pedigree-chart) | SVG pedigree chart — multiple layouts, up to 25 generations |
| [webtrees-descendants-chart](https://github.com/magicsunday/webtrees-descendants-chart) | SVG descendants chart — spouse display, up to 25 generations |
| [webtrees-statistics](https://github.com/magicsunday/webtrees-statistics) | SVG-based statistics dashboard for a family tree |
| [webtrees-chart-lib](https://github.com/magicsunday/webtrees-chart-lib) | Shared D3 chart library powering the modules above |
| [webtrees-module-base](https://github.com/magicsunday/webtrees-module-base) | Shared PHP base classes (date, name, image, place processors) |
| [webtrees-module-installer-plugin](https://github.com/magicsunday/webtrees-module-installer-plugin) | Composer plugin that installs webtrees modules into `modules_v4/` |
| [webtrees-docker](https://github.com/magicsunday/webtrees-docker) | Self-host webtrees with one command — wizard-generated Docker stack |

## Libraries

| Repository | What it is |
| --- | --- |
| [imagemeta](https://github.com/magicsunday/imagemeta) | Read-only EXIF / XMP / IPTC / QuickTime / RIFF metadata extraction |
| [photo-renamer](https://github.com/magicsunday/photo-renamer) | Rename and deduplicate photos/videos via metadata and perceptual hashing |
| [gedcom-parser](https://github.com/magicsunday/gedcom-parser) | A GEDCOM 5.5.1 file parser |
| [jsonmapper](https://github.com/magicsunday/jsonmapper) | Map JSON to typed PHP objects |
| [xmlmapper](https://github.com/magicsunday/xmlmapper) | Map XML to typed PHP objects |
| [typo3-migration-analyzer](https://github.com/magicsunday/typo3-migration-analyzer) | Generate missing TYPO3 Extension Scanner matcher configs |

## About

The [`.github`](https://github.com/magicsunday/.github) repository holds the shared
community-health files and the reusable CI workflows used across these projects.

Contributions are welcome — see each repository's `CONTRIBUTING.md`, or the
account-wide [contributing guide](https://github.com/magicsunday/.github/blob/main/CONTRIBUTING.md).

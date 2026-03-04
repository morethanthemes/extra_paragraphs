# Extra Paragraphs

Reusable Paragraph types for content authors. This recipe provides ready‑to‑use
paragraph types such as **Highlight** and **Collapse** so editors can build
modular, media-rich pages quickly.

## What this recipe provides

- Paragraph type: Highlight (title, body, image, link)
- Paragraph type: Collapse (title + rich body for collapsible sections)
- Field and display configuration for editor and teaser presentations

## Requirements

- Drupal core **10.4+**
- Paragraphs module

## Installation

Install the recipe via Composer or apply it locally with Drush:

```bash
composer require drupal/extra_paragraphs
# or, from a local checkout:
# drush recipe ../recipes/extra_paragraphs
```

After installation, manage paragraph types under *Structure → Paragraphs types*.

## Customization

The exported configuration is in `config/` — edit and re-export if you make
changes you want to preserve in the recipe.

## License

GPL-2.0-or-later
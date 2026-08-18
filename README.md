# Naki // N4-K2 — Extended Jekyll Site

This is the expanded GitHub Pages / Jekyll version of the personal site.

## Major structure

```text
.
├── _config.yml
├── _data/
├── _includes/
├── _layouts/
├── _posts/
├── _projects/
├── _writing/
├── pages/
├── assets/
│   ├── css/
│   ├── js/
│   └── images/
├── Gemfile
├── README.md
└── index.html
```

## What Jekyll is doing

### Layouts

Reusable page structures live in `_layouts/`.

- `default.html` — global page shell
- `project.html` — individual project records
- `writing.html` — writing archive entries
- `post.html` — devlog posts

### Includes

Reusable pieces live in `_includes/`.

Examples:

- Header
- Footer
- Project cards
- Link cards
- Stat cards
- Page heroes

### Data

Editable YAML data lives in `_data/`.

This includes:

- Profile
- Navigation
- Skills
- Games
- Aesthetics
- FAQ
- Current activity
- Links
- Uses
- Statistics

### Collections

Projects live in `_projects/`.

Writing archive records live in `_writing/`.

Each Markdown file becomes its own generated page.

### Posts

Devlog entries live in `_posts/` and use normal Jekyll post filenames.

## Important URLs

- `/`
- `/about/`
- `/projects/`
- `/writing/`
- `/development/`
- `/gaming/`
- `/interests/`
- `/now/`
- `/uses/`
- `/faq/`
- `/devlog/`
- `/links/`
- `/directory/`

## Editing profile data

Edit:

```text
_data/profile.yml
```

## Adding a project

Create a Markdown file in:

```text
_projects/
```

Example:

```yaml
---
title: "Example Project"
type: "Minecraft Mod"
status: "In Development"
summary: "Short description."
tags:
  - "minecraft"
  - "java"
---

Long project description goes here in Markdown.
```

The project automatically receives the project layout and appears in the project collection.

## Adding a writing record

Create a Markdown file inside `_writing/`.

## Adding a devlog post

Create a file in `_posts/` with a date-prefixed filename:

```text
2026-08-17-example-post.md
```

## Command palette

Press:

```text
Ctrl + K
```

or:

```text
Command + K
```

to open the site command palette.

It searches generated pages and collections and also exposes a few site actions.

## Local Jekyll testing

Install Ruby and Bundler, then:

```bash
bundle install
bundle exec jekyll serve
```

Jekyll normally serves locally at:

```text
http://127.0.0.1:4000/
```

## GitHub Pages

For branch-based GitHub Pages publishing:

1. Upload the project files to the repository.
2. Open repository Settings.
3. Open Pages.
4. Choose Deploy from a branch.
5. Select the publishing branch.
6. Select `/(root)`.
7. Save.

This project intentionally does not contain `.nojekyll` because Jekyll processing is required.


# Wiki expansion

The site now includes these additional Jekyll collections:

```text
_characters/
_species/
_lore/
_docs/
_roadmaps/
_galleries/
_changelogs/
```

Generated wiki routes include:

```text
/wiki/
/wiki/characters/
/wiki/species/
/wiki/lore/
/docs/
/roadmaps/
/gallery/
/changelog/
/tags/
```

## Related records

Wiki records can include:

```yaml
record_id: "character-example"
related_ids:
  - "species-example"
  - "lore-example"
```

The wiki layout automatically renders matching connected records and backlinks.

## Tags

Tags are collected across the major collections and displayed on `/tags/`.

## Adding a character

Create a file in `_characters/`:

```yaml
---
title: "Example Character"
record_id: "character-example"
status: "Active Canon"
project: "Example Project"
role: "Core Character"
tags:
  - character
  - example
related_ids:
  - "species-example"
---

Character description in Markdown.
```

## Adding species or lore

Use the same pattern in `_species/` or `_lore/`.

## Documentation

Technical notes live in `_docs/` and receive their own generated documentation URLs.

## Gallery

Gallery records can contain normal Markdown, HTML, or image references. Put image files under `assets/images/`.

# Galascribe

Blog publishing software and Markdown publishing platform: write in an editor, keep every post as a Markdown file in your own GitHub repository, publish to GitHub Pages on your own domain.

This repository is the public home for Galascribe's documentation and issue links; the app is a hosted service at app.galascribe.com.

## What is Galascribe?

Galascribe is blog publishing software for a site you own. You write in a visual editor that has a Markdown view, preview on desktop and phone, and publish to your own domain. Every post is saved as Markdown with YAML front matter in a GitHub repository in your own account.

The site is hosted free on GitHub Pages. If you leave or close your account, the repository and the published site stay on GitHub. Leaving is a git clone.

## Features

| Feature | What it does |
|---|---|
| Scheduled posts | Publish on a date and time you choose, up to a year ahead |
| RSS and Atom feeds | Full-text feeds of your 50 newest posts |
| Built-in themes | Six themes, each with light and dark modes |
| Search | A search dialog on your published site |
| Markdown editor | Visual editor with a Markdown view; tables, code blocks, images, galleries |
| Your own GitHub repository | Posts are Markdown files you own |
| Custom domain | Your domain with HTTPS on GitHub Pages |
| Archive, tags and series | Archive by year, tag pages, series, author pages, an About page |
| Newsletter | Email your subscribers |
| Likes and comments | Reader interactions on your site |
| Listen | An audio version of every post (Basic and Pro) |
| Import | From Substack, WordPress, Medium or Ghost export files |

## What a Galascribe site looks like in your repository

```text
content/        one Markdown file per post or page
gala/           settings as JSON: publication, authors, navigation, appearance
assets/         your images
.github/workflows/
```

A post starts with front matter:

```markdown
---
schemaId: urn:gala:schema:content-frontmatter:2.0.0
schemaVersion: "2.0.0"
id: a stable id, do not change once published
kind: article
title: My new article
language: en-US
tags: []
status: published
slug: my-new-article
---

# My new article

Write your article here, in Markdown.
```

## Scheduled posts

Schedule a publish for a date and time you choose, up to a year ahead. One scheduled publish per site can wait at a time. You can also give a draft a release date: with staggered release switched on in Settings, Galascribe publishes it on that day in your time zone.

## RSS feeds

Every site has full-text RSS and Atom feeds of the 50 newest posts, at `/feed/rss.xml` and `/feed/atom.xml`. When Listen is on, there is also a podcast feed.

## Themes

Galascribe has six built-in themes: Default, Amaze, Flashy, Minimal, Zebra and Editorial. Each has light and dark modes. Pick one of six colour sets (Midnight, Oxblood, Forest, Plum, Ember, Graphite) or set custom colours.

## Search

Your published site has a search button in the header. It opens a search dialog over a static index of your posts and pages. Search needs JavaScript in the reader's browser.

## Is it a writer website builder?

Yes, for writing sites. Galascribe gives writers an independent writing site or author website with a home page, archive, tags, series, author pages and an About page, on your own domain. It is not a drag-and-drop page designer: the layout comes from the theme you choose.

## How it compares

- [Compare Galascribe](https://app.galascribe.com/compare)
- [Alternatives](https://app.galascribe.com/alternatives)
- [Choosing blog publishing software](https://app.galascribe.com/best-blog-publishing-software)

With Hugo, Jekyll, Eleventy or Astro you run the generator and write the configuration yourself. Galascribe gives you an editor, themes and publishing on top of files you still own.

## What it does not do

Galascribe does not charge your readers, run a store, or offer plugins. It is not a drag-and-drop page designer. You cannot run Galascribe on your own server, and there is no documented way yet to build your site without it.

## Pricing

Free is $0 for one site. Basic is $12 a month or $96 a year. Pro is $149 a month or $1,188 a year. Listen and the contact form are Basic and up. Details: https://app.galascribe.com/pricing

## Open source parts

The renderer, schemas and publish tooling are open source under Apache-2.0: [template](https://github.com/rathnasgala2/template), [schema](https://github.com/rathnasgala2/schema) and [publish](https://github.com/rathnasgala2/publish). The Galascribe app is a hosted service.

## Get help

Open an issue at https://github.com/galascribe/support/issues, or write to support@galascribe.com.

## Links

- https://galascribe.com
- https://app.galascribe.com/markdown-publishing-platform
- https://app.galascribe.com/writer-website-builder
- https://app.galascribe.com/features
- https://app.galascribe.com/pricing
- https://blog.galascribe.com/

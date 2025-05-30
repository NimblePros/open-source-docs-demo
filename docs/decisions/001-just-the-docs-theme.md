---
number: "001"
title: Just the Docs Theme
status: Active
---

## Context

We are setting up documentation for our open source project and need to choose a theme that is suitable for GitHub Pages. The theme must be:

- Easy to run locally
- Easy to deploy
- Clean and professional in appearance
- Searchable

We evaluated the [list of themes supported by GitHub Pages](https://pages.github.com/themes/) for our documentation. While these themes are straightforward to implement, none of them provided built-in support for document search, which we consider an essential feature.

## Decision

We will use the **Just the Docs** theme with GitHub Pages.

**Just the Docs** provides a clean layout and, most importantly, supports client-side search out of the box. It is also easy to integrate with GitHub Pages, allowing us to serve the documentation from the same repository as our code with minimal configuration.

## Consequences

- Our documentation site will be easy to maintain and deploy.
- Users will be able to search documentation without requiring an external service.
- We may need to manually ensure compatibility with GitHub Pages since Just the Docs is not in the officially supported theme list, though it works well with GitHub Pages via a custom remote theme.

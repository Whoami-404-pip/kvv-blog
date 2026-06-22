---
title: "Image Workflow"
subtitle: "A small helper for keeping image changes isolated"
date: 2026-06-08T09:00:00Z
tags: ["hugo", "images", "workflow"]
mood: "focused"
---

The `site-image` shortcode always points into `static/site-images/`, so content does not need hardcoded theme paths.

{{< site-image src="hero.png" alt="Workspace preview" caption="Replace the file in `static/site-images/` and every reference stays valid." >}}

## Usage

```md
{{< site-image src="hero.png" alt="Workspace preview" >}}
```

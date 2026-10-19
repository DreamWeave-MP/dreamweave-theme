+++
title = "DreamWeave Theme"
description = "Every template, stylesheet, font, image and script a DreamWeave site is presented with, as one Jess package."
date = 2026-10-19

[taxonomies]
tags = ["Jess", "Luau"]

[extra]
sections = ["overview", "releases", "credits"]
+++

Every template, stylesheet, font, image and script a DreamWeave site is presented with, as one Jess package.

<!-- more -->

A [Jess](https://github.com/DreamWeave-MP/jess) package, `org.dreamweave.theme`. Add it to a `jess.toml` and
`jess workspace sync` pins it from this site:

```toml
[dependencies]
"org.dreamweave.theme" = "0.2"
```

Every release below is the package's own archive, with its content digest beside the archive's
SHA-256; `jess.lock` pins the first and checks both.

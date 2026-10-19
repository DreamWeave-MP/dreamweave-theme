# DreamWeave theme

Every template, stylesheet, font, image and script a DreamWeave site is presented with, as one
Jess package: `org.dreamweave.theme`. A site depends on it and lets the generator read the files
through `@dreamweave/theme`, instead of copying `templates/`, `sass/` and `static/` from the Mod
Template and drifting. A file of the same path in the site itself wins over the theme's.

The files came from the DreamWeave Mod Template at `b25333b8` (branch `V5`); from here on this
package is where they live, and the template depends on it like every other site.

```sh
jess package test .      # the payload's contract, from the source and packed
jess package check .
```

Licensed MIT OR Apache-2.0, like the template. The fonts keep their own licenses in `licenses/`.

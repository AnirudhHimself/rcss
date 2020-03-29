# rcss
The CSS I use for my Rmd Notebooks


## Usage:
This css isn't used as part of a package, since it's only at about 80 lines for now. Seems easier to just include it as a CSS parameter in the YAML.

```
---
title: "Title"
subtitle: "Obviously Optional"
author: "pepperidge farm"
date: "`r Sys.Date()`"
output: 
  html_document:
    toc: true
    toc_float: true
      toc_collapsed: false
    theme: flatly
    css: **style.css**
---
```

Place the style.css folder in the same folder as the Rmd. Then, press knit.

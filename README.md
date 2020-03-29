# rcss
The CSS I use for my Rmd Notebooks


## Usage:
Have the below YAML at the top of your html_document.

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

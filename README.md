# rcss
The CSS I use for my Rmd Notebooks


Here's what it looks like:

![Image of Yaktocat](https://octodex.github.com/images/yaktocat.png)

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

If you're starting from a fresh rmarkdown file, you can just clone the R folder from this repo and clear out the Lorem Ipsum text.


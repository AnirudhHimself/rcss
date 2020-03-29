# rcss
You can customise the appearance of the html document that your r markdown file produces by adding CSS to match your tastes and needs. This repo contains the CSS I created to use for my Rmd Notebooks. It also contains the starter file with the YAML I typically include.


Here's what it looks like:

![Example Picture of Template](https://github.com/AnirudhHimself/rcss/blob/master/img/DemoImage.PNG)

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


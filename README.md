# Data All The Way

[![Netlify Status](https://api.netlify.com/api/v1/badges/7a35d80e-e047-4ba3-a70d-fc4d207d232b/deploy-status)](https://app.netlify.com/sites/dataalltheway/deploys)

This repository is for the Quarto website code for <https://dataalltheway.com/>, a tutorial website with concepts, methods, and example code on various data science, statistics, and machine learning topics.

## Example blog post YAML header

``` yaml
---
title: "How to download a shared file from Google Drive in R"
description: "A tutorial on how to download a shared file with 'anyone with the link' access rights from Google Drive in R."
author: 
  - name: "Rohit Farmer"
    orcid: "0000-0003-4197-3047"
    #affiliations:
    #  - name: "https://www.dataalltheway.com"
date: "2022-10-14"
categories: [How To, Etc]
format:
  html:
    code-fold: false
    code-tools:
      source: false
      toggle: false
citation: true
  #type: article
  #publisher: "Zenodo"
  #doi: "10.5281/zenodo.7232109"
  #url: "https://doi.org/10.5281/zenodo.7232109"
bibliography: "references.bib"
google-scholar: true
execute: 
  eval: true
draft: true
---
```

## To create a new post

In the posts folder, make a folder with the name that will go on the URL. The name of the folder need not be the same as the title of the post, as the title of a post can be way longer than what would look better on the URL. Prefix the name with the serial number 00N to make it easier to order as per the name of the posts. This serial number needs not correspond to the order in which the posts are updated. Most posts will likely get updated at a later date. Inside the folder, create an `index.qmd` file.

```         
00N-title-of-the-post
  index.qmd
```

## Helpful websites

-   [doi2bib](https://www.doi2bib.org/) - to convert a doi into BibTex.
-   Citation types - <https://docs.citationstyles.org/en/stable/specification.html#appendix-iii-types>

## Frequently used elements

### Callouts

```         
::: {.callout-note collapse="true"}
### Updates

2022-10-25
:::
```

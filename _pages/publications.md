---
layout: page
permalink: /publications/
title: publications
description: selected publications by lab members, in reverse chronological order.
nav: true
nav_order: 9
---

<!-- _pages/publications.md -->

<!-- Bibsearch Feature -->

Selected publications related to the lab's research. For complete lists, see the Google Scholar profiles of
[Dr. Zefeng Lyu](https://scholar.google.com/citations?user=-n8Ol7wAAAAJ) and [Dr. Yuqiu Ye](https://scholar.google.com/citations?user=azxMarcAAAAJ).

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

<style>
  .publications ol.bibliography li {
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    padding: 1rem 1.25rem;
    background-color: var(--global-card-bg-color);
  }
  .publications ol.bibliography li .row {
    margin: 0;
  }
  .publications ol.bibliography li .abbr:empty,
  .publications ol.bibliography li .abbr:not(:has(*)) {
    display: none;
  }
  .publications ol.bibliography li .col-sm-8 {
    flex: 1 1 auto;
    max-width: 100%;
    padding: 0;
  }
</style>

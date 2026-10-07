---
layout: page
permalink: /publications/
title: publications
description: selected publications by lab members, in reverse chronological order.
nav: true
nav_order: 9
---

<!-- _pages/publications.md -->
<!-- The navbar tab stays "publications" (page title); the heading below replaces the default page header. -->

<header class="post-header pub-header">
  <h1 class="post-title">selected publications</h1>
  <p class="post-description">publications related to the lab's research, in reverse chronological order.</p>
</header>

This is a selection of papers related to the lab's research, not a complete list of the co-directors' publications. For complete lists, see the
Google Scholar profiles of [Dr. Zefeng Lyu](https://scholar.google.com/citations?user=-n8Ol7wAAAAJ) and
[Dr. Yuqiu Ye](https://scholar.google.com/citations?user=azxMarcAAAAJ).

<!-- Bibsearch Feature -->

{% include bib_search.liquid %}

<div class="publications">

{% bibliography %}

</div>

<style>
  .post > .post-header:not(.pub-header) {
    display: none;
  }
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

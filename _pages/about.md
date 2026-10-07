---
layout: about
title: about
permalink: /
subtitle: Perception, Engineering & Navigation for Ground-UAV Intelligent Networks

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

The PENGUIN Lab (Perception, Engineering & Navigation for Ground-UAV Intelligent Networks) at Youngstown State University studies how aerial and
ground robots can sense, plan, and build together. Our current focus is **aerial additive manufacturing (AAM)**: using drones as flying 3D printers.

<div class="aam-gallery">
  <figure>
    <img src="{{ '/assets/img/aam/aerial-printing.webp' | relative_url }}" alt="A drone depositing material layer by layer to print a structure" loading="lazy">
    <figcaption>Aerial 3D printing: a drone deposits material layer by layer.</figcaption>
  </figure>
  <figure>
    <img src="{{ '/assets/img/aam/aerial-repair.webp' | relative_url }}" alt="A drone spraying repair material into a crack in a concrete wall" loading="lazy">
    <figcaption>Aerial repair: a drone applies material to a crack in a concrete wall.</figcaption>
  </figure>
</div>

Current research directions:

- **Flight control and stability**: keeping a UAV steady and precise enough to deposit material in flight.
- **Multi-UAV task allocation and path planning**: coordinating a team of drones to print a structure efficiently.
- **3D reconstruction**: using UAVs and ground robots to capture the 3D geometry of target objects.

Meet the team on the [people]({{ '/people/' | relative_url }}) page.

<style>
  .aam-gallery {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1rem;
    margin: 1.5rem 0;
  }
  .aam-gallery figure {
    margin: 0;
  }
  .aam-gallery img {
    width: 100%;
    aspect-ratio: 3 / 2;
    object-fit: cover;
    border-radius: 8px;
  }
  .aam-gallery figcaption {
    font-size: 0.85em;
    color: var(--global-text-color-light);
    margin-top: 0.4rem;
  }
  @media (max-width: 575px) {
    .aam-gallery {
      grid-template-columns: 1fr;
    }
  }
</style>

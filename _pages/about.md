---
layout: about
title: Home
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

<div class="hero">
  <div class="hero-text">
    <p>
      The PENGUIN Lab (Perception, Engineering &amp; Navigation for Ground-UAV Intelligent Networks) at Youngstown State University studies how
      aerial and ground robots can sense, plan, and build together.
    </p>
    <p>Our current focus is <strong>aerial additive manufacturing (AAM)</strong>: using drones as flying 3D printers.</p>
    <p class="hero-links">
      <a href="{{ '/people/' | relative_url }}">Meet the team →</a>
      <a href="{{ '/competitions/' | relative_url }}">Join a competition team →</a>
    </p>
  </div>
  <figure class="hero-figure">
    <img src="{{ '/assets/img/aam/aerial-printing.webp' | relative_url }}" alt="A drone depositing material layer by layer to print a structure" loading="lazy">
    <figcaption>Aerial 3D printing: a drone deposits material layer by layer.</figcaption>
  </figure>
</div>

## Research Directions

<div class="icon-cards">
  <div class="icon-card">
    <i class="fa-solid fa-gauge-high" aria-hidden="true"></i>
    <h3>Flight control and stability</h3>
    <p>Keeping a UAV steady and precise enough to deposit material in flight.</p>
  </div>
  <div class="icon-card">
    <i class="fa-solid fa-route" aria-hidden="true"></i>
    <h3>Multi-UAV task allocation and path planning</h3>
    <p>Coordinating a team of drones to print a structure efficiently.</p>
  </div>
  <div class="icon-card">
    <i class="fa-solid fa-cube" aria-hidden="true"></i>
    <h3>3D reconstruction</h3>
    <p>Using UAVs and ground robots to capture the 3D geometry of target objects.</p>
  </div>
</div>

<style>
  .icon-cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin: 1rem 0 1.5rem;
  }
  .icon-card {
    padding: 1.25rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
  }
  .icon-card i {
    font-size: 1.75rem;
    color: var(--global-theme-color);
    margin-bottom: 0.75rem;
  }
  .icon-card h3 {
    font-size: 1.1rem;
    margin: 0 0 0.5rem;
  }
  .icon-card p {
    margin: 0;
    font-size: 0.95em;
  }
  @media (max-width: 767px) {
    .icon-cards {
      grid-template-columns: 1fr;
    }
  }
  .hero {
    display: grid;
    grid-template-columns: 1fr 42%;
    gap: 2rem;
    align-items: center;
    margin-bottom: 1rem;
  }
  .hero-text p:last-child {
    margin-bottom: 0;
  }
  .hero-links a {
    display: inline-block;
    margin-right: 1.25rem;
    font-weight: 500;
  }
  .hero-figure {
    margin: 0;
  }
  .hero-figure img {
    width: 100%;
    aspect-ratio: 4 / 3;
    object-fit: cover;
    border-radius: 8px;
  }
  .hero-figure figcaption {
    font-size: 0.8em;
    color: var(--global-text-color-light);
    margin-top: 0.4rem;
  }
  @media (max-width: 767px) {
    .hero {
      grid-template-columns: 1fr;
      gap: 1rem;
    }
  }
</style>

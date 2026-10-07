---
layout: page
title: Projects
permalink: /projects/
description: Current and upcoming research projects
nav: false
sitemap: false
nav_order: 8
---

Our projects are organized around the three pillars in the lab's name.

<div class="icon-cards">
  <div class="icon-card">
    <i class="fa-solid fa-eye" aria-hidden="true"></i>
    <h3>Perception</h3>
    <p>Sensing and understanding the environment from the air and the ground.</p>
  </div>
  <div class="icon-card">
    <i class="fa-solid fa-gears" aria-hidden="true"></i>
    <h3>Engineering</h3>
    <p>Building aerial systems that can manufacture and repair structures.</p>
  </div>
  <div class="icon-card">
    <i class="fa-solid fa-route" aria-hidden="true"></i>
    <h3>Navigation</h3>
    <p>Planning and controlling how UAVs and ground robots move.</p>
  </div>
</div>

<div class="table-wrap">
<table class="project-table">
  <thead>
    <tr>
      <th>Project</th>
      <th>Pillar</th>
      <th>Status</th>
      <th>Lead</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>UAV-Based Pavement &amp; Infrastructure Crack Detection</td>
      <td class="pillar"><i class="fa-solid fa-eye" aria-hidden="true"></i> Perception</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu</td>
    </tr>
    <tr>
      <td>Aerial Additive Manufacturing (Aerial 3D Printing)</td>
      <td class="pillar"><i class="fa-solid fa-gears" aria-hidden="true"></i> Engineering</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu &amp; Ye</td>
    </tr>
    <tr>
      <td>UAV Delivery</td>
      <td class="pillar"><i class="fa-solid fa-route" aria-hidden="true"></i> Navigation</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu</td>
    </tr>
    <tr>
      <td>UAV-Based Water Pollution Monitoring</td>
      <td class="pillar"><i class="fa-solid fa-eye" aria-hidden="true"></i> Perception</td>
      <td><span class="status soon">Coming soon</span></td>
      <td>Ye</td>
    </tr>
    <tr>
      <td>UAV-Based Campus Traffic Safety Monitoring</td>
      <td class="pillar"><i class="fa-solid fa-eye" aria-hidden="true"></i> Perception</td>
      <td><span class="status soon">Coming soon</span></td>
      <td>Ye</td>
    </tr>
  </tbody>
</table>
</div>

<style>
  .icon-cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1rem;
    margin: 1rem 0 0.5rem;
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
  .pillar {
    white-space: nowrap;
  }
  .pillar i {
    color: var(--global-theme-color);
    width: 1.25em;
  }
  @media (max-width: 767px) {
    .icon-cards {
      grid-template-columns: 1fr;
    }
  }
  .table-wrap {
    overflow-x: auto;
    margin-top: 1.5rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
  }
  .project-table {
    width: 100%;
    border-collapse: collapse;
    margin: 0;
  }
  .project-table th,
  .project-table td {
    padding: 0.85rem 1rem;
    text-align: left;
    border-bottom: 1px solid var(--global-divider-color);
  }
  .project-table tbody tr:last-child td {
    border-bottom: none;
  }
  .project-table th {
    background-color: var(--global-card-bg-color);
    font-weight: 600;
  }
  .status {
    display: inline-block;
    padding: 0.15rem 0.6rem;
    border-radius: 4px;
    font-size: 0.9em;
    white-space: nowrap;
  }
  .status.active {
    color: var(--global-theme-color);
    border: 1px solid var(--global-theme-color);
  }
  .status.soon {
    color: var(--global-text-color-light);
    border: 1px solid var(--global-divider-color);
  }
</style>

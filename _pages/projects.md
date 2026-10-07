---
layout: page
title: projects
permalink: /projects/
description: current and upcoming research projects
nav: true
nav_order: 8
---

Our projects are organized around the three pillars in the lab's name: **Perception**, **Engineering**, and **Navigation**.

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
      <td>Perception</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu</td>
    </tr>
    <tr>
      <td>Aerial Additive Manufacturing (Aerial 3D Printing)</td>
      <td>Engineering</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu &amp; Ye</td>
    </tr>
    <tr>
      <td>UAV Delivery</td>
      <td>Navigation</td>
      <td><span class="status active">Active</span></td>
      <td>Lyu</td>
    </tr>
    <tr>
      <td>UAV-Based Water Pollution Monitoring</td>
      <td>Perception</td>
      <td><span class="status soon">Coming soon</span></td>
      <td>Ye</td>
    </tr>
    <tr>
      <td>UAV-Based Campus Traffic Safety Monitoring</td>
      <td>Perception</td>
      <td><span class="status soon">Coming soon</span></td>
      <td>Ye</td>
    </tr>
  </tbody>
</table>
</div>

<style>
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

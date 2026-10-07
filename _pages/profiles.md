---
layout: page
permalink: /people/
title: people
description: members of the PENGUIN Lab
nav: true
nav_order: 7
---

<!-- To add a real photo, put it in assets/img/people/ and change that person's img src below. -->

## Co-Directors

<div class="person">
  <img src="{{ '/assets/img/people/placeholder.svg' | relative_url }}" alt="Dr. Zefeng Lyu" class="z-depth-1 rounded">
  <div>
    <h3>Dr. Zefeng Lyu</h3>
    <p class="person-role">Assistant Professor, Youngstown State University</p>
    <p class="person-role"><a href="https://scholar.google.com/citations?user=-n8Ol7wAAAAJ" target="_blank" rel="noopener">Google Scholar</a></p>
    <p>
      Dr. Lyu received a Ph.D. in Industrial Engineering from the University of Tennessee, Knoxville (2023) and a B.S. in Industrial Engineering
      from Zhejiang University of Technology, and was a postdoctoral research associate at the University of Tennessee before joining YSU in 2024.
      Dr. Lyu's research combines operations research and machine learning, including vehicle routing, scheduling, and learning-based methods for
      combinatorial optimization, with UAV-based sensing, such as drone and deep learning pavement crack detection funded by the Tennessee
      Department of Transportation. This work has appeared in the European Journal of Operational Research, IEEE Transactions on Intelligent
      Transportation Systems, and Computers &amp; Industrial Engineering. At the PENGUIN Lab, Dr. Lyu leads research on multi-UAV planning for
      aerial additive manufacturing.
    </p>
  </div>
</div>

<div class="person">
  <img src="{{ '/assets/img/people/placeholder.svg' | relative_url }}" alt="Dr. Yuqiu Ye" class="z-depth-1 rounded">
  <div>
    <h3>Dr. Yuqiu Ye</h3>
    <p class="person-role">Assistant Professor, Department of Civil, Environmental, and Chemical Engineering, Youngstown State University</p>
    <p class="person-role"><a href="https://scholar.google.com/citations?user=azxMarcAAAAJ" target="_blank" rel="noopener">Google Scholar</a></p>
    <p>
      Dr. Ye received a Ph.D. (2024) and an M.Sc. in Civil Engineering from the University of Kansas, and an M.Sc. and a B.Sc. in Civil
      Engineering from Wuhan University of Technology, and was a research associate and lecturer at the University of Kansas before joining YSU in
      2025. Dr. Ye's research covers soil–structure interaction, ground improvement, computational geotechnics, remote sensors, and sustainable and
      resilient geomaterials, with publications in Géotechnique, the Journal of Geotechnical and Geoenvironmental Engineering, Geotextiles and
      Geomembranes, and Computers and Geotechnics. Honors include the YSU Research Professorship Award (2025) and a Best Paper Award Honorable
      Mention from Geotextiles and Geomembranes (2023). At YSU, Dr. Ye is developing aerial deposition materials for additive
      construction in civil engineering.
    </p>
  </div>
</div>

## Graduate Students

<div class="person">
  <img src="{{ '/assets/img/people/placeholder.svg' | relative_url }}" alt="Yuchen He" class="z-depth-1 rounded">
  <div>
    <h3>Yuchen He</h3>
    <p class="person-role">M.S. Student</p>
    <p>
      Yuchen develops task allocation and path planning algorithms for cooperative UAV swarms, including multi-objective optimization for
      multi-UAV aerial additive manufacturing operations.
    </p>
  </div>
</div>

<div class="person">
  <img src="{{ '/assets/img/people/placeholder.svg' | relative_url }}" alt="Muhammad Nouman Tahir" class="z-depth-1 rounded">
  <div>
    <h3>Muhammad Nouman Tahir</h3>
    <p class="person-role">M.S. Student</p>
    <p>
      Nouman works on UAV flight control and stability, keeping drones steady and precise enough for aerial 3D printing. Nouman holds a B.E. in
      Mechanical Engineering from the National University of Sciences and Technology (NUST), Pakistan (2025), and led autonomous UAV teams in
      international competitions, including reaching the finals of the TEKNOFEST 2024 International UAV Competition in Türkiye. Nouman's tools
      include PX4, ArduPilot, ROS 2, and Gazebo.
    </p>
  </div>
</div>

<div class="person">
  <img src="{{ '/assets/img/people/placeholder.svg' | relative_url }}" alt="Sumaia Islam" class="z-depth-1 rounded">
  <div>
    <h3>Sumaia Islam</h3>
    <p class="person-role">M.S. Student</p>
    <p>Sumaia works on 3D reconstruction of target objects using UAVs and ground robots.</p>
  </div>
</div>

<style>
  .person {
    display: flex;
    gap: 1.5rem;
    align-items: flex-start;
    margin: 1rem 0;
    padding: 1.25rem;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
  }
  .person img {
    width: 150px;
    height: 150px;
    object-fit: cover;
    flex-shrink: 0;
  }
  .person h3 {
    margin-top: 0;
    margin-bottom: 0.25rem;
  }
  .person-role {
    font-style: italic;
    margin-bottom: 0.5rem;
  }
  @media (max-width: 575px) {
    .person {
      flex-direction: column;
    }
  }
</style>

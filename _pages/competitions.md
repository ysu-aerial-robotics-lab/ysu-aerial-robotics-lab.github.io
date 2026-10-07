---
layout: page
permalink: /competitions/
title: competitions
description: student teams for uncrewed aircraft systems (UAS) competitions
nav: true
nav_order: 10
---

<div class="join-box">
  <h2><i class="fa-solid fa-user-plus" aria-hidden="true"></i> Join our competition teams</h2>
  <p>
    The PENGUIN Lab is recruiting students to form teams for uncrewed aircraft systems (UAS) competitions. Both undergraduate and graduate students
    are welcome. Team members work on autonomy software, flight control, computer vision, and building and testing aircraft.
  </p>
  <p>If you are interested in joining, email us:</p>
  <ul>
    <li>Dr. Zefeng Lyu: <a href="mailto:zlyu@ysu.edu">zlyu@ysu.edu</a></li>
    <li>Dr. Yuqiu Ye: <a href="mailto:yye01@ysu.edu">yye01@ysu.edu</a></li>
  </ul>
</div>

## Competitions we are targeting

<div class="comp-card">
  <div class="comp-logo"><img src="{{ '/assets/img/competitions/suas.png' | relative_url }}" alt="SUAS Competition logo"></div>
  <div class="comp-body">
  <h3><a href="https://suas-competition.org/" target="_blank" rel="noopener">SUAS: Student Unmanned Aerial Systems Competition</a></h3>
  <p class="comp-meta">Hosted by RoboNation · held every year</p>
  <p>
    Teams design, integrate, report on, and demonstrate a UAS capable of autonomous flight and navigation, remote sensing with onboard payload
    sensors, and a set of mission tasks such as object detection, payload delivery, and mapping. Each team presents a technical design and flight
    readiness review, then flies a simulated mission that is scored by the judges. The 2026 competition drew 85 registered teams, 64 of which,
    from 10 countries, qualified to fly at Skyway Range in Tulsa, Oklahoma.
  </p>
  </div>
</div>

<div class="comp-card">
  <div class="comp-logo"><img src="{{ '/assets/img/competitions/iarc.png' | relative_url }}" alt="IARC logo"></div>
  <div class="comp-body">
  <h3>
    <a href="http://www.aerialroboticscompetition.org/" target="_blank" rel="noopener">IARC: International Aerial Robotics Competition</a>
  </h3>
  <p class="comp-meta">Running since 1991 · the longest-running collegiate aerial robotics challenge</p>
  <p>
    Founded by Robert Michelson, who coined the term "aerial robotics", the IARC poses missions that require behaviors no flying robot has shown
    before. Each mission stays open until a team completes it. The current Mission 10 addresses anti-personnel landmines: teams must use aerial
    robots to help a person cross a 100-meter minefield in under 10 minutes.
  </p>
  </div>
</div>

<div class="comp-card">
  <div class="comp-logo"><img src="{{ '/assets/img/competitions/aigp.png' | relative_url }}" alt="AI Grand Prix logo"></div>
  <div class="comp-body">
  <h3><a href="https://theaigrandprix.com" target="_blank" rel="noopener">AI Grand Prix</a></h3>
  <p class="comp-meta">Launched by Anduril in 2026 · fully autonomous drone racing</p>
  <p>
    A global autonomous drone racing series in which software is the only difference between teams. Everyone races identical drones built by
    Neros Technologies, with no human pilots and no hardware modifications. Teams first submit Python-based autonomy software to race in
    simulation, then advance to physical qualifiers. The inaugural championship race is held in Columbus, Ohio, in November 2026, with a $500,000
    prize pool and a job opportunity at Anduril. University and independent teams can enter.
  </p>
  </div>
</div>

<style>
  .join-box {
    padding: 1.25rem 1.5rem;
    margin-bottom: 2rem;
    border: 2px solid var(--global-theme-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
  }
  .join-box h2 {
    margin-top: 0;
  }
  .join-box ul {
    margin-bottom: 0;
  }
  .comp-card {
    padding: 1.25rem 1.5rem;
    margin: 1rem 0;
    border: 1px solid var(--global-divider-color);
    border-radius: 8px;
    background-color: var(--global-card-bg-color);
  }
  .comp-card h3 {
    margin-top: 0;
    margin-bottom: 0.25rem;
  }
  .comp-meta {
    font-style: italic;
    margin-bottom: 0.5rem;
  }
  .comp-card p:last-child {
    margin-bottom: 0;
  }
  .comp-card {
    display: flex;
    gap: 1.25rem;
    align-items: flex-start;
  }
  .comp-logo {
    flex: 0 0 110px;
    height: 110px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 0.4rem;
    border-radius: 8px;
    background-color: var(--global-bg-color);
    border: 1px solid var(--global-divider-color);
    color: var(--global-theme-color);
  }
  .comp-logo i {
    font-size: 2.25rem;
  }
  .comp-logo span {
    font-weight: 600;
    letter-spacing: 0.05em;
  }
  .comp-logo img {
    max-width: 100%;
    max-height: 100%;
    object-fit: contain;
  }
  .comp-logo:has(img) {
    background-color: #fff;
    padding: 0.5rem;
  }
  .comp-body {
    flex: 1;
    min-width: 0;
  }
  @media (max-width: 575px) {
    .comp-card {
      flex-direction: column;
    }
  }
</style>

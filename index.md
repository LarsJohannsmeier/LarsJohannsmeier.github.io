---
layout: page
title: Home
permalink: /
---

<div class="home-layout">
  <aside class="home-sidebar">
    <h1 class="home-name">Lars Johannsmeier</h1>
    <p class="home-role">Research Scientist · NVIDIA</p>
    <p class="home-short">
      Robotics, AI, and machine learning for contact-intensive robot manipulation.
    </p>
    <ul class="home-links">
      <li><a href="{{ '/about/' | relative_url }}">About</a></li>
      <li><a href="{{ '/publications/' | relative_url }}">Publications</a></li>
      <li><a href="{{ '/talks/' | relative_url }}">Talks</a></li>
      <li><a href="https://www.linkedin.com/in/lars-johannsmeier-575940181/">LinkedIn</a></li>
      <li><a href="https://orcid.org/0000-0003-4599-7636">ORCID</a></li>
    </ul>
  </aside>

  <main class="home-main">
    <section>
      <h2>About</h2>
      <p>
        I am a Research Scientist at NVIDIA with more than 10 years of academic and industrial
        robotics research experience. My work focuses on tactile and contact-intensive
        manipulation, autonomous policy synthesis, and robust transfer from research prototypes
        to real-world systems.
      </p>
    </section>

    <section>
      <h2>Research Interests</h2>
      <h3>Research Themes</h3>
      <h4>1) Contact-Intensive Manipulation Learning</h4>
      <p>Learning architectures and models for tactile and contact-rich robotic skills.</p>

      <h4>2) Autonomous Policy Synthesis</h4>
      <p>Process-taxonomy-based planning and learning-driven policy generation for manipulation tasks.</p>

      <h4>3) Real-World Robotics Systems</h4>
      <p>From demonstrators to product transfer: robust implementation across control, planning, and software systems.</p>

      <h3>Current Direction</h3>
      <p>
        My current work at NVIDIA focuses on robotics, AI, and machine learning, with an emphasis on
        methods that scale from research prototypes to dependable real-world systems.
      </p>
    </section>

    <section>
      <h2>Selected Publications</h2>
      <div class="selected-publications">
        <article class="publication-card">
          <p class="publication-venue"><strong>Nature Machine Intelligence (2025)</strong></p>
          <h3 class="publication-title">
            <a href="https://www.nature.com/articles/s42256-025-01076-2">A process-centric manipulation taxonomy for the organisation, classification and synthesis of tactile robot skills.</a>
          </h3>
          <p class="publication-abstract">
            This paper introduces a process-centric taxonomy for tactile manipulation that structures robot skills by manipulation process instead of only by task labels. The taxonomy provides a principled basis for organizing prior knowledge and guiding skill synthesis.
          </p>
        </article>

        <article class="publication-card">
          <p class="publication-venue"><strong>ICRA (2019)</strong></p>
          <h3 class="publication-title">
            <a href="https://ieeexplore.ieee.org/document/8793529">A Framework for Robot Manipulation: Skill Formalism, Meta Learning and Adaptive Control.</a>
          </h3>
          <p class="publication-abstract">
            The work presents a manipulation framework that combines a structured skill formalism with meta-learning and adaptive control. The goal is to speed up skill acquisition while maintaining robust performance under changing task dynamics.
          </p>
        </article>

        <article class="publication-card">
          <p class="publication-venue"><strong>Proceedings of the IEEE (2019)</strong></p>
          <h3 class="publication-title">
            <a href="https://ieeexplore.ieee.org/document/8624466">Tactile Robots as a Central Embodiment of the Tactile Internet.</a>
          </h3>
          <p class="publication-abstract">
            This article discusses tactile robots as a key embodiment layer for the Tactile Internet, connecting sensing, communication, and control requirements. It outlines the technical foundations and system-level implications for reliable remote physical interaction.
          </p>
        </article>
      </div>
      <p><a href="{{ '/publications/' | relative_url }}">See full publication list →</a></p>
    </section>
  </main>
</div>

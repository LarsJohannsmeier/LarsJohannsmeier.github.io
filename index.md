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
            <a href="https://www.nature.com/articles/s42256-025-01045-3?utm_source=rct_congratemailt&utm_medium=email&utm_campaign=oa_20250623&utm_content=10.1038/s42256-025-01045-3">A process-centric manipulation taxonomy for the organisation, classification and synthesis of tactile robot skills.</a>
          </h3>
          <p class="publication-abstract">
            Despite decades of research in robotic manipulation, only a few autonomous manipulation skills are currently used. Traditional and machine-learning-based end-to-end solutions have shown substantial progress but still struggle to generate reliable manipulation skills for difficult processes like insertion or bending material. To facilitate the deployment and learning of tactile robot manipulation skills, we introduce here a taxonomy based on formal process specifications provided by experts, which assigns a suitable skill to a given process. We validated the inherent scalability of the taxonomy on 28 different skills from industrial application domains. The experimental results had success rates close to 100%, even under goal pose disturbances, with high performance attained by the skill models in terms of execution times and contact moments in partially known environments. The basic elements of the models are reusable and facilitate skill-learning to optimize control performance. Like established curricula for human trainees, this framework could provide a comprehensive platform that enables robots to acquire relevant manipulation skills and act as a catalyst to propel automation beyond its current capabilities.
          </p>
        </article>

        <article class="publication-card">
          <p class="publication-venue"><strong>IROS (2022)</strong></p>
          <h3 class="publication-title">
            <a href="https://ieeexplore.ieee.org/abstract/document/9982025">Can we reach human expert programming performance? A tactile manipulation case study in learning time and task performance.</a>
          </h3>
          <p class="publication-abstract">
            Reaching human-level performance in tactile manipulation is one of the grand challenges in nowadays robotics research. Over the past decade significant progress in both skill control and learning was made. However, the achievable execution speed still falls behind the human ability, without clearly understanding whether the specific shortcomings are mainly in the control, skill learning, or motion planning layer. For gaining a better understanding of this complex problem, we draw an experimental side-by-side comparative case study. First, given a task program for a challenging benchmarking task, the goal is to objectify the achievable task performance from a human expert programmer against autonomously learning these assembly behaviors with a state-of-the-art skill learning framework. Second, we compare the manually tuned and learned robot skills to the performance of an adult human solving the task manually. For the former, it could be shown that despite longer learning duration, the task execution speed of the machine learning-based solution is equivalent to the one programmed by the human expert. For the latter, the identified performance gap remained significantly larger, where only for some specific isolated skills the system was able to reach comparable or even faster than human execution speeds. The overall analysis gave also useful hints where in particular manipulation policies and arm-hand coordination still need significant improvements in the future.
          </p>
        </article>

        <article class="publication-card">
          <p class="publication-venue"><strong>Proceedings of the IEEE (2019)</strong></p>
          <h3 class="publication-title">
            <a href="https://ieeexplore.ieee.org/abstract/document/8556371">Tactile Robots as a Central Embodiment of the Tactile Internet.</a>
          </h3>
          <p class="publication-abstract">
            In this paper, we discuss and speculate about the concept of the Tactile Robot connected with human operators via smart wearables as an essential multimodal embodiment of the coming Tactile Internet. The Tactile Robot, succeeding the recently introduced kinesthetic soft robot, is the upcoming next step in the evolution of rapidly developing robotic platforms that are capable of sensitive physical interaction with their environment. From the combination of rich tactile feedback with state-of-the-art robotics, technology, and algorithms emerge the potential of a meaningful and immersive connection to human operators via the vastly progressing smart wearables and virtual reality/augmented reality devices, effectively creating real-world avatars. Moreover, the Tactile Internet is believed to make it possible to create avatar collectives spanning different application domains and, therefore, cover heterogeneous robotic platforms. We hypothesize that this development will enable us to seamlessly interact with heterogeneous systems such as industrial assembly lines, service robots, automated medical units, or even deep sea and space exploration units. This new paradigm of an immersive coexistence between humans and robots builds on numerous technological advances in robotics, multimodal teleoperation, wearable technology, distributed computing, or network technology, for example. However, such a vision obviously poses major challenges in multiple areas that are still to be overcome. In this paper, we discuss the potentials and enabling technologies together with foreseeable application domains in the framework of the Tactile Internet. Furthermore, we address major challenges and hypothesize about potential solutions.
          </p>
        </article>
      </div>
      <p><a href="{{ '/publications/' | relative_url }}">See full publication list →</a></p>
    </section>
  </main>
</div>

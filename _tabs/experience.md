---
title: Experience
icon: fas fa-briefcase
order: 5
---

<div class="experience-page">

  <section class="experience-section">
    <h2 class="section-title">Research Experience</h2>

    <div class="experience-list">

      <article class="experience-item">
        <div class="experience-header">
          <div>
            <h3>Young Research Fellow</h3>
            <p class="organization">Indian Institute of Technology Madras</p>
          </div>
          <span class="experience-date">Jul 2025 – Jul 2026</span>
        </div>

        <p class="research-context">
          Deep learning for computational geometry and shape analysis
        </p>

        <ul>
          <li>
            Benchmarked <strong>10+ skeletonization approaches</strong> while
            investigating learning-based methods for shape skeletonization.
          </li>
          <li>
            Modeled <strong>midcurves and midsurfaces using signed distance
            fields</strong> under Prof. Ramanathan Muthuganapathy.
          </li>
          <li>
            Created <strong>35+ publication-quality figures</strong> and
            contributed to research presented at SIGGRAPH Asia 2025 and
            an industry poster at IISc Bangalore.
          </li>
        </ul>
      </article>


      <article class="experience-item">
        <div class="experience-header">
          <div>
            <h3>Research Assistant</h3>
            <p class="organization">
              Advanced Geometric Computing Lab · IIT Madras
            </p>
          </div>
          <span class="experience-date">Jan 2025 – Jul 2025</span>
        </div>

        <p class="research-context">
          Geometric deep learning for midcurve reconstruction
        </p>

        <ul>
          <li>
            Built <strong>DGCNN, VGAE, and Graph Transformer</strong>
            pipelines to reconstruct midcurves from sparse shape profiles.
          </li>
          <li>
            Benchmarked <strong>10+ methods</strong> while studying implicit
            representations and medial-axis geometry and topology.
          </li>
          <li>
            Reviewed <strong>30+ papers</strong> spanning computational
            geometry, graph learning, and geometric deep learning.
          </li>
        </ul>
      </article>

    </div>
  </section>


  <section class="experience-section">
    <h2 class="section-title">Technical & Project Experience</h2>

    <article class="experience-item">
      <div class="experience-header">
        <div>
          <h3>Project Member · Team Suncast</h3>
          <p class="organization">
            AI Club × Horizon Club · IIT Madras
          </p>
        </div>
        <span class="experience-date">May 2024 – May 2025</span>
      </div>

      <p class="research-context">
        Graph-based solar flare prediction
      </p>

      <ul>
        <li>
          Combined <strong>GATs and LSTMs</strong> to model spatial-temporal
          dependencies in correlation-based solar-flare graphs.
        </li>
        <li>
          Improved classification accuracy by <strong>&gt;8%</strong> over
          non-graph baselines through joint spatial-temporal learning.
        </li>
        <li>
          Presented research results to <strong>5k+ attendees</strong> across
          CFI Research Conclave ’24 and CFI Open House ’25.
        </li>
      </ul>
    </article>
  </section>


  <section class="experience-section">
    <h2 class="section-title">Leadership</h2>

    <article class="experience-item leadership-item">
      <div class="experience-header">
        <div>
          <h3>Coordinator · AI Club</h3>
          <p class="organization">Indian Institute of Technology Madras</p>
        </div>
        <span class="experience-date">May 2024 – May 2025</span>
      </div>

      <ul>
        <li>
          Organized and ideated AI Club workshops and events and wrote
          technical questions as one of 10 coordinators.
        </li>
        <li>
          Co-organized a deep learning workshop reaching
          <strong>2k+ participants</strong> at CFI Summer School.
        </li>
        <li>
          Taught <strong>Gridworld Q-learning</strong> to 20+ peers.
        </li>
        <li>
          Introduced AI concepts to <strong>1k+ students</strong> at CFI
          Freshie Weekender.
        </li>
        <li>
          Published a Medium review of GameNGen covering reinforcement
          learning and diffusion-based simulation.
        </li>
      </ul>
    </article>
  </section>

</div>


<style>
  .experience-page {
    max-width: 900px;
  }

  .experience-section {
    margin-bottom: 3rem;
  }

  .section-title {
    font-size: 1.35rem;
    margin-bottom: 1.3rem;
    padding-bottom: 0.55rem;
    border-bottom: 1px solid rgba(120, 130, 150, 0.18);
  }

  .experience-list {
    display: grid;
    gap: 2.2rem;
  }

  .experience-item {
    position: relative;
    padding-left: 1.3rem;
    border-left: 2px solid rgba(120, 130, 150, 0.22);
  }

  .experience-header {
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1.5rem;
    margin-bottom: 0.35rem;
  }

  .experience-item h3 {
    margin: 0;
    font-size: 1.15rem;
    line-height: 1.4;
  }

  .organization {
    margin: 0.2rem 0 0;
    color: var(--text-muted-color, #6b7280);
    font-size: 0.95rem;
  }

  .experience-date {
    flex-shrink: 0;
    color: var(--text-muted-color, #6b7280);
    font-size: 0.88rem;
    white-space: nowrap;
  }

  .research-context {
    margin: 0.75rem 0 0.8rem;
    font-size: 0.9rem;
    font-style: italic;
    color: var(--text-muted-color, #6b7280);
  }

  .experience-item ul {
    margin: 0;
    padding-left: 1.15rem;
  }

  .experience-item li {
    margin-bottom: 0.65rem;
    line-height: 1.65;
  }

  .experience-item li:last-child {
    margin-bottom: 0;
  }

  .leadership-item {
    border-left-color: rgba(120, 130, 150, 0.18);
  }

  .dynamic-title,
  .page-header {
    display: none !important;
  }

  @media (max-width: 767px) {
    .experience-page {
      max-width: 100%;
    }

    .experience-header {
      flex-direction: column;
      gap: 0.3rem;
    }

    .experience-date {
      white-space: normal;
    }

    .experience-section {
      margin-bottom: 2.4rem;
    }
  }
</style>
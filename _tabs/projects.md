---
title: Projects
icon: fas fa-diagram-project
order: 4
---

<div class="projects-page">

  <div class="projects-intro">
    <div class="section-label">SELECTED WORK</div>
    <h1>Projects</h1>
    <p>
      Selected technical projects spanning 3D vision, computer vision,
      geometric reconstruction, strategic learning, and real-time perception.
    </p>
  </div>


  <!-- FEATURED PROJECT -->

  <section class="featured-project">

    <div class="project-kicker">
      FEATURED · 3D VISION
    </div>

    <div class="featured-header">
      <div>
        <h2>Multi-view Consistent<br>3D Reconstruction</h2>

        <p class="project-meta">
          EE5178 · Modern Computer Vision
          <span>·</span>
          Mar 2026 – Apr 2026
        </p>
      </div>
    </div>

    <div class="project-tags">
      <span>3D Gaussian Splatting</span>
      <span>Multi-view Geometry</span>
      <span>HLOC</span>
      <span>Super Resolution</span>
    </div>

    <p class="featured-description">
      Investigated multi-view 3D reconstruction from low-resolution inputs,
      combining camera localization, super-resolution, and Gaussian
      Splatting to improve reconstruction quality.
    </p>


    <div class="results">

      <div class="result">
        <strong>77.2%</strong>
        <span>benchmark accuracy</span>
      </div>

      <div class="result">
        <strong>0.59 → 0.77</strong>
        <span>benchmark score</span>
      </div>

      <div class="result">
        <strong>21 → 29</strong>
        <span>PSNR</span>
      </div>

      <div class="result">
        <strong>90%+</strong>
        <span>SSIM</span>
      </div>

    </div>


    <div class="project-details">

      <div>
        <h3>What I explored</h3>

        <ul>
          <li>
            Combined low-resolution multi-view inputs with
            <strong>super-resolution and 3D Gaussian Splatting</strong>
            for reconstruction.
          </li>

          <li>
            Replaced conventional COLMAP SfM with
            <strong>HLOC</strong> for camera localization,
            improving the benchmark score from 0.59 to 0.77.
          </li>

          <li>
            Ablated <strong>8+ reconstruction pipelines</strong>,
            including SRGS, DAT, HAT, ESRGAN, SwinIR and SplatSure.
          </li>

          <li>
            Evaluated reconstruction quality on challenging scenes,
            particularly fine-grained text and surface textures.
          </li>
        </ul>
      </div>


      <div class="technical-note">
        <div class="note-label">RESULT</div>

        <p>
          The final pipeline achieved <strong>77.2%</strong> benchmark
          accuracy compared with a <strong>56.8%</strong> baseline,
          while reconstruction quality improved from approximately
          <strong>21 → 29 PSNR</strong> and <strong>75% → 90%+ SSIM</strong>.
        </p>
      </div>

    </div>

  </section>


  <!-- OTHER PROJECTS -->

  <section class="other-projects">

    <div class="section-label">OTHER PROJECTS</div>


    <!-- GAME THEORY -->

    <article class="project-row">

      <div class="project-index">02</div>

      <div class="project-content">

        <div class="project-row-header">
          <div>
            <h2>Equilibrium Learning in Games</h2>

            <p class="project-meta">
              EE6417 · Incentive-Centered Design
              <span>·</span>
              Feb 2026 – Present
            </p>
          </div>
        </div>

        <div class="project-tags">
          <span>Game Theory</span>
          <span>Coarse Correlated Equilibrium</span>
          <span>Multi-Agent Learning</span>
          <span>Strategic Learning</span>
        </div>

        <p class="project-description">
          Studying learning dynamics in repeated strategic interactions,
          with a focus on how agents can approach equilibrium through
          adaptive forecasting and play.
        </p>

        <ul>
          <li>
            Implementing <strong>coarse correlated equilibrium</strong>
            algorithms based on the Foster–Vohra framework for
            multi-agent strategic learning.
          </li>

          <li>
            Exploring repeated-game settings to study how learning
            dynamics can lead toward equilibrium without explicitly
            computing the equilibrium.
          </li>

          <li>
            Investigating connections between equilibrium learning,
            <strong>fictitious play, no-regret learning</strong>,
            and multi-agent coordination.
          </li>

          <li>
            Exploring applications of equilibrium learning dynamics
            to <strong>financial-market and strategic decision-making</strong>
            settings.
          </li>
        </ul>

      </div>

    </article>


    <!-- ADAS -->

    <article class="project-row">

      <div class="project-index">03</div>

      <div class="project-content">

        <div class="project-row-header">
          <div>
            <h2>Radar-Based ADAS System</h2>

            <p class="project-meta">
              ED3010 · Human Factors in Design
              <span>·</span>
              Aug 2025 – Nov 2025
            </p>
          </div>
        </div>

        <div class="project-tags">
          <span>CARLA</span>
          <span>FMCW Radar</span>
          <span>ADAS</span>
          <span>Real-time Perception</span>
        </div>

        <p class="project-description">
          Designed a radar-based perception and driver-alert system
          for collision-risk assessment under low-visibility conditions.
        </p>

        <ul>
          <li>
            Built a <strong>CARLA/FMCW-radar perception pipeline</strong>
            for collision-risk assessment in fog with &lt;20 m visibility.
          </li>

          <li>
            Converted radar detections to Cartesian coordinates in real time
            and classified threats into <strong>four hazard levels</strong>.
          </li>

          <li>
            Combined <strong>TTC ≤ 5 s</strong> risk thresholds with
            radar-HUD alerts and CSV telemetry for decision support.
          </li>

          <li>
            Tested early hazard detection in simulated highway scenarios
            with closing speeds up to <strong>90 km/h</strong>.
          </li>

          <li>
            Designed a low-cognitive-load HUD using TTC-mapped pulsation
            to communicate hazard urgency without text.
          </li>
        </ul>

      </div>

    </article>

  </section>


  <!-- CLOSING -->

  <section class="projects-closing">

    <p>
      More research work can be found across my
      <a href="/research/">research</a> and
      <a href="/publications/">publications</a>.
    </p>

  </section>

</div>


<style>

/* =========================
   PAGE INTRO
========================= */

.projects-page {
  max-width: 900px;
}

.projects-intro {
  padding: 0.5rem 0 2.5rem;
  border-bottom: 1px solid rgba(120, 130, 150, 0.18);
}

.section-label {
  font-size: 0.72rem;
  font-weight: 700;
  letter-spacing: 0.13em;
  color: var(--link-color, #3a6ea5);
}

.projects-intro h1 {
  margin: 0.7rem 0 0.45rem;
  font-size: clamp(2rem, 5vw, 3rem);
}

.projects-intro p {
  max-width: 650px;
  margin: 0;
  color: var(--text-muted-color, #6b7280);
  line-height: 1.7;
}


/* =========================
   FEATURED PROJECT
========================= */

.featured-project {
  margin-top: 3rem;
  padding: 1.8rem;
  border: 1px solid rgba(120, 130, 150, 0.2);
  border-radius: 12px;
  background: rgba(120, 130, 150, 0.035);
}

.project-kicker {
  font-size: 0.7rem;
  font-weight: 700;
  letter-spacing: 0.13em;
  color: var(--link-color, #3a6ea5);
}

.featured-header {
  margin-top: 0.75rem;
}

.featured-header h2 {
  margin: 0;
  font-size: clamp(1.55rem, 4vw, 2.15rem);
  line-height: 1.2;
}

.project-meta {
  margin: 0.5rem 0 0;
  color: var(--text-muted-color, #6b7280);
  font-size: 0.88rem;
}

.project-meta span {
  margin: 0 0.35rem;
  opacity: 0.5;
}


/* =========================
   TAGS
========================= */

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4rem;
  margin-top: 1.15rem;
}

.project-tags span {
  padding: 0.3rem 0.6rem;
  border: 1px solid rgba(120, 130, 150, 0.2);
  border-radius: 999px;
  font-size: 0.75rem;
}


/* =========================
   DESCRIPTION
========================= */

.featured-description {
  max-width: 760px;
  margin: 1.25rem 0 1.5rem;
  line-height: 1.7;
  font-size: 1rem;
}


/* =========================
   RESULTS
========================= */

.results {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  border-top: 1px solid rgba(120, 130, 150, 0.17);
  border-bottom: 1px solid rgba(120, 130, 150, 0.17);
}

.result {
  padding: 1rem 0.7rem;
  text-align: center;
  border-right: 1px solid rgba(120, 130, 150, 0.17);
}

.result:last-child {
  border-right: none;
}

.result strong {
  display: block;
  font-size: 1.05rem;
}

.result span {
  display: block;
  margin-top: 0.3rem;
  color: var(--text-muted-color, #6b7280);
  font-size: 0.7rem;
}


/* =========================
   FEATURED DETAILS
========================= */

.project-details {
  display: grid;
  grid-template-columns: 1.5fr 1fr;
  gap: 2rem;
  margin-top: 1.6rem;
}

.project-details h3 {
  margin: 0 0 0.7rem;
  font-size: 1rem;
}

.project-details ul,
.project-content ul {
  margin: 0;
  padding-left: 1.1rem;
}

.project-details li,
.project-content li {
  margin-bottom: 0.55rem;
  line-height: 1.6;
}

.project-details li:last-child,
.project-content li:last-child {
  margin-bottom: 0;
}

.technical-note {
  align-self: start;
  padding: 1rem 1.1rem;
  border-left: 3px solid var(--link-color, #3a6ea5);
  background: rgba(120, 130, 150, 0.04);
}

.note-label {
  font-size: 0.67rem;
  font-weight: 700;
  letter-spacing: 0.12em;
  color: var(--link-color, #3a6ea5);
}

.technical-note p {
  margin: 0.5rem 0 0;
  color: var(--text-muted-color, #6b7280);
  font-size: 0.88rem;
  line-height: 1.6;
}


/* =========================
   OTHER PROJECTS
========================= */

.other-projects {
  margin-top: 3.5rem;
}

.project-row {
  display: grid;
  grid-template-columns: 45px 1fr;
  gap: 1rem;
  margin-top: 1rem;
  padding-top: 1.3rem;
  border-top: 1px solid rgba(120, 130, 150, 0.18);
}

.project-index {
  padding-top: 0.25rem;
  color: var(--text-muted-color, #6b7280);
  font-size: 0.75rem;
}

.project-row h2 {
  margin: 0;
  font-size: 1.35rem;
}

.project-description {
  max-width: 750px;
  margin: 1rem 0 1rem;
  color: var(--text-muted-color, #6b7280);
  line-height: 1.7;
}


/* =========================
   CLOSING
========================= */

.projects-closing {
  margin-top: 3rem;
  padding-top: 1.5rem;
  border-top: 1px solid rgba(120, 130, 150, 0.18);
  color: var(--text-muted-color, #6b7280);
}

.projects-closing a {
  text-decoration: none;
}


/* =========================
   CHIRPY CLEANUP
========================= */

.dynamic-title,
.page-header {
  display: none !important;
}


/* =========================
   MOBILE
========================= */

@media (max-width: 767px) {

  .projects-page {
    max-width: 100%;
  }

  .featured-project {
    padding: 1.25rem;
  }

  .featured-header h2 {
    font-size: 1.55rem;
  }

  .results {
    grid-template-columns: repeat(2, 1fr);
  }

  .result:nth-child(2) {
    border-right: none;
  }

  .result:nth-child(-n+2) {
    border-bottom: 1px solid rgba(120, 130, 150, 0.17);
  }

  .project-details {
    grid-template-columns: 1fr;
    gap: 1.3rem;
  }

  .project-row {
    grid-template-columns: 32px 1fr;
  }

  .project-row h2 {
    font-size: 1.2rem;
  }

}

</style>
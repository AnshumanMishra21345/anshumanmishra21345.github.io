---
title: About
icon: fas fa-user
order: 1
---

<div class="academic-page">

  <section class="about-intro">
    <h2>Anshuman Mishra</h2>
    <p class="about-subtitle">
      M.Tech Data Science + B.Tech Engineering Design · IIT Madras
    </p>

    <p>
      I am a student at the Indian Institute of Technology Madras working
      across <strong>computer vision, 3D vision, geometric learning,
      and computational geometry</strong>.
    </p>

    <p>
      My research interests include <strong>3D reconstruction, geometric
      representations, shape analysis, skeletonization, and learning-based
      approaches to geometry</strong>.
    </p>
  </section>


  <section class="about-section">
    <h2>Education</h2>

    <div class="education-item">
      <div>
        <h3>Indian Institute of Technology Madras</h3>
        <p>M.Tech Data Science + B.Tech Engineering Design</p>
      </div>
      <div class="education-meta">
        <strong>9.26 / 10</strong>
        <span>Expected 2028</span>
      </div>
    </div>

    <div class="education-item">
      <div>
        <h3>Babaji Vidhyashram, Chennai</h3>
        <p>Class XII · CBSE</p>
      </div>
      <div class="education-meta">
        <strong>96.4%</strong>
        <span>2022–23</span>
      </div>
    </div>

    <div class="education-item">
      <div>
        <h3>Babaji Vidhyashram, Chennai</h3>
        <p>Class X · CBSE</p>
      </div>
      <div class="education-meta">
        <strong>97.4%</strong>
        <span>2020–21</span>
      </div>
    </div>
  </section>


  <section class="about-section">
    <h2>Scholastic Achievements</h2>

    <ul class="achievement-list">
      <li>
        <strong>IIT Madras Young Research Fellowship</strong> —
        selected among the top 25 of 300+ applicants.
      </li>
      <li>
        <strong>Global Engagement Travel Grant</strong> —
        received an INR 82k grant as one of two IIT Madras undergraduates
        attending AI conferences.
      </li>
      <li>
        <strong>Ranked 3rd of 78</strong> after sophomore year.
      </li>
      <li>
        <strong>9.56 SGPA</strong> in the first semester of M.Tech Data Science.
      </li>
    </ul>
  </section>


  <section class="about-section">
    <h2>Research Interests</h2>

    <div class="interest-grid">
      <span>Computer Vision</span>
      <span>3D Vision</span>
      <span>Geometric Deep Learning</span>
      <span>Computational Geometry</span>
      <span>Shape Analysis</span>
      <span>Skeletonization</span>
      <span>3D Reconstruction</span>
      <span>Geometric Representations</span>
    </div>
  </section>


  <section class="about-section">
    <h2>Technical Skills</h2>

    <div class="skill-groups">

      <div class="skill-group">
        <h3>Programming & Tools</h3>
        <p>
          Python · C++ · Git · VSCode · Docker · Linux · Meshlab · Blender
        </p>
      </div>

      <div class="skill-group">
        <h3>Machine Learning</h3>
        <p>
          PyTorch · JAX · CNNs · U-Nets · GNNs · Graph Transformers ·
          Knowledge Distillation
        </p>
      </div>

      <div class="skill-group">
        <h3>3D Vision & Geometry</h3>
        <p>
          OpenCV · Multi-view Geometry · NeRFs · Gaussian Splatting ·
          Point-cloud Processing · SDFs
        </p>
      </div>

    </div>
  </section>


  <section class="about-section">
    <h2>Coursework</h2>

    <p class="coursework">
      Modern Computer Vision · Mathematics for Data Science ·
      Mechatronics System Design · Probability and Statistics ·
      Digital Signal Processing · Control Systems ·
      Data Structures and Algorithms · Human Factors in Design
    </p>
  </section>

</div>


<style>
  .academic-page {
    max-width: 900px;
  }

  .about-intro {
    margin-bottom: 3rem;
  }

  .about-intro h2 {
    font-size: 2rem;
    margin-bottom: 0.25rem;
  }

  .about-subtitle {
    color: var(--text-muted-color, #6b7280);
    font-size: 1rem;
    margin-bottom: 1.5rem;
  }

  .about-intro p {
    font-size: 1rem;
    line-height: 1.8;
  }

  .about-section {
    margin-top: 2.8rem;
  }

  .about-section > h2 {
    font-size: 1.35rem;
    margin-bottom: 1.2rem;
    padding-bottom: 0.55rem;
    border-bottom: 1px solid rgba(120, 130, 150, 0.18);
  }

  .education-item {
    display: flex;
    justify-content: space-between;
    gap: 2rem;
    padding: 1rem 0;
    border-bottom: 1px solid rgba(120, 130, 150, 0.12);
  }

  .education-item:first-of-type {
    padding-top: 0;
  }

  .education-item h3 {
    font-size: 1rem;
    margin: 0 0 0.25rem;
  }

  .education-item p {
    margin: 0;
    color: var(--text-muted-color, #6b7280);
  }

  .education-meta {
    min-width: 110px;
    text-align: right;
    display: flex;
    flex-direction: column;
    gap: 0.2rem;
  }

  .education-meta span {
    color: var(--text-muted-color, #6b7280);
    font-size: 0.9rem;
  }

  .achievement-list {
    padding-left: 1.2rem;
  }

  .achievement-list li {
    margin-bottom: 0.75rem;
    line-height: 1.65;
  }

  .interest-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 0.55rem;
  }

  .interest-grid span {
    padding: 0.4rem 0.75rem;
    border: 1px solid rgba(120, 130, 150, 0.22);
    border-radius: 999px;
    font-size: 0.88rem;
  }

  .skill-groups {
    display: grid;
    gap: 1.2rem;
  }

  .skill-group h3 {
    font-size: 0.95rem;
    margin-bottom: 0.35rem;
  }

  .skill-group p {
    margin: 0;
    color: var(--text-muted-color, #6b7280);
    line-height: 1.7;
  }

  .coursework {
    color: var(--text-muted-color, #6b7280);
    line-height: 1.8;
  }

  .dynamic-title,
  .page-header {
    display: none !important;
  }

  @media (max-width: 767px) {
    .academic-page {
      max-width: 100%;
    }

    .about-intro h2 {
      font-size: 1.7rem;
    }

    .education-item {
      flex-direction: column;
      gap: 0.4rem;
    }

    .education-meta {
      min-width: 0;
      text-align: left;
      flex-direction: row;
      gap: 0.7rem;
    }

    .about-section {
      margin-top: 2.3rem;
    }
  }
</style>
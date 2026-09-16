---
title: Research
icon: fas fa-flask
order: 2
---

<div class="research-page">

  <section class="research-intro">
    <h2>Research Interests</h2>
    <p>
      My interests lie at the intersection of <strong>computer vision,
      3D vision, geometric deep learning, and computational geometry</strong>.
      I am particularly interested in learning representations that capture
      the structure, geometry, and topology of visual data.
    </p>
  </section>


  <section class="research-grid">

    <article class="research-area">
      <div class="research-icon">
        <i class="fas fa-cube"></i>
      </div>

      <h3>3D Vision &amp; Scene Understanding</h3>

      <p>
        Learning geometric representations of real-world scenes from
        multi-view visual data.
      </p>

      <div class="research-tags">
        <span>Multi-view Geometry</span>
        <span>3D Reconstruction</span>
        <span>Structure-from-Motion</span>
        <span>NeRFs</span>
        <span>Gaussian Splatting</span>
        <span>Point Clouds</span>
      </div>
    </article>


    <article class="research-area">
      <div class="research-icon">
        <i class="fas fa-project-diagram"></i>
      </div>

      <h3>Geometric Deep Learning</h3>

      <p>
        Designing learning methods for data with non-Euclidean structure,
        including graphs, shapes, and geometric objects.
      </p>

      <div class="research-tags">
        <span>Graph Neural Networks</span>
        <span>Graph Transformers</span>
        <span>Geometric Representations</span>
        <span>Implicit Representations</span>
        <span>Signed Distance Fields</span>
      </div>
    </article>


    <article class="research-area">
      <div class="research-icon">
        <i class="fas fa-shapes"></i>
      </div>

      <h3>Shape Analysis &amp; Geometry</h3>

      <p>
        Understanding and reconstructing geometric structure from
        incomplete, noisy, or sparse shape observations.
      </p>

      <div class="research-tags">
        <span>Shape Reconstruction</span>
        <span>Skeletonization</span>
        <span>Medial-axis Geometry</span>
        <span>Midcurves</span>
        <span>Midsurfaces</span>
        <span>Shape Analysis</span>
      </div>
    </article>


    <article class="research-area">
      <div class="research-icon">
        <i class="fas fa-brain"></i>
      </div>

      <h3>Visual Representation Learning</h3>

      <p>
        Learning compact and robust visual representations for
        reconstruction, perception, and downstream vision tasks.
      </p>

      <div class="research-tags">
        <span>Representation Learning</span>
        <span>Feature Learning</span>
        <span>Knowledge Distillation</span>
        <span>Data Augmentation</span>
        <span>Deep Learning</span>
      </div>
    </article>

  </section>


  <section class="research-direction">

    <div class="direction-content">
      <span class="eyebrow">Current Direction</span>

      <h2>Learning Geometry from Visual Data</h2>

      <p>
        A recurring theme across my work is combining geometric structure
        with learned representations. This includes recovering shape
        structure from noisy observations, building compact geometric
        representations, and improving the robustness of 3D reconstruction
        pipelines.
      </p>
    </div>

  </section>

</div>


<style>
  .research-page {
    max-width: 900px;
  }

  .research-intro {
    margin-bottom: 2.8rem;
  }

  .research-intro h2 {
    font-size: 1.8rem;
    margin-bottom: 0.75rem;
  }

  .research-intro p {
    max-width: 780px;
    line-height: 1.8;
    color: var(--text-muted-color, #6b7280);
  }

  .research-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1rem;
  }

  .research-area {
    padding: 1.35rem;
    border: 1px solid rgba(120, 130, 150, 0.18);
    border-radius: 12px;
    background: rgba(255, 255, 255, 0.02);
  }

  .research-icon {
    font-size: 1rem;
    margin-bottom: 0.8rem;
    color: var(--link-color, #3a6ea5);
  }

  .research-area h3 {
    margin: 0;
    font-size: 1.08rem;
  }

  .research-area > p {
    margin: 0.65rem 0 1rem;
    line-height: 1.65;
    color: var(--text-muted-color, #6b7280);
    font-size: 0.92rem;
  }

  .research-tags {
    display: flex;
    flex-wrap: wrap;
    gap: 0.4rem;
  }

  .research-tags span {
    padding: 0.3rem 0.6rem;
    border: 1px solid rgba(120, 130, 150, 0.18);
    border-radius: 999px;
    font-size: 0.76rem;
  }

  .research-direction {
    margin-top: 2.8rem;
    padding: 1.5rem 1.6rem;
    border-left: 3px solid var(--link-color, #3a6ea5);
    background: rgba(120, 130, 150, 0.05);
  }

  .eyebrow {
    display: block;
    margin-bottom: 0.45rem;
    font-size: 0.72rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--text-muted-color, #6b7280);
  }

  .research-direction h2 {
    margin: 0 0 0.6rem;
    font-size: 1.2rem;
  }

  .research-direction p {
    margin: 0;
    line-height: 1.75;
    color: var(--text-muted-color, #6b7280);
  }

  .dynamic-title,
  .page-header {
    display: none !important;
  }

  @media (max-width: 767px) {
    .research-page {
      max-width: 100%;
    }

    .research-grid {
      grid-template-columns: 1fr;
    }

    .research-intro h2 {
      font-size: 1.55rem;
    }
  }
</style>
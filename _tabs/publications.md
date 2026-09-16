---
title: Publications
icon: fas fa-book-open
order: 3
---

<div class="publications-page">
  <div class="publication-card card">
    <div class="publication-header">
      <h2>ConvPSNet: A convolution-based single-step approach for pruned skeleton extraction</h2>
      <span class="venue-badge">SIGGRAPH Asia 2025, Technical Communications</span>
    </div>

    <p><strong>Location:</strong> Hong Kong</p>
    <p><strong>Authors:</strong> Bincy Antony, Anshuman Mishra, Ananthakrishnan A, Dharanivendhan V, Ramanathan Muthuganapathy</p>
    <p>Developed a single-step convolutional framework to extract pruned skeletons directly from noisy 2D shape samples.</p>

    <h3>Additional contributions</h3>
    <ul>
      <li>Curated a synthetic dataset of diverse shapes with pruned skeletons through a human-in-the-loop workflow.</li>
      <li>Designed scalable boundary perturbation and augmentation pipelines to generate varied noisy shape configurations.</li>
      <li>Developed a lightweight convolution-only architecture with large kernels and a neighborhood-consistency loss to suppress spurious branches and preserve structural connectivity.</li>
    </ul>

    <p class="placeholder-note"><strong>Paper:</strong> <a href="https://doi.org/10.1145/3757376.3771414" target="_blank">ACM Digital Library</a></p>
  </div>

  <div class="publication-card card">
    <div class="publication-header">
      <h2>DistillSkel: Learning pruned skeletons of 2D shapes through progressive knowledge distillation</h2>
      <span class="venue-badge">Shape Modelling International 2026, Technical Paper</span>
    </div>

    <p><strong>Location:</strong> Istanbul, Türkiye</p>
    <p><strong>Authors:</strong> Bincy Antony Mangottu, Anshuman Mishra, Pranav Raghuram, Dharunpathi Tamilselvan, Ramanathan Muthuganapathy</p>
    <ul>
      <li>Progressively distilled a 31M-parameter U-Net teacher into a 31K-parameter student, achieving a 1000× reduction in model size.</li>
      <li>Matched teacher-level skeleton quality with an average F1-score of 0.693 versus 0.697 for the teacher across six unseen benchmarks.</li>
      <li>Achieved 6.3× faster inference while reducing the parameter count by 1000×.</li>
      <li>Introduced a differentiable junction-preservation loss to reduce broken junctions and preserve skeleton connectivity.</li>
      <li>Curated a human-annotated benchmark of noisy shapes and pruned skeletons from multiple shape repositories for systematic evaluation.</li>
    </ul>

    <p class="placeholder-note"><strong>Paper:</strong> <a href="https://doi.org/10.1016/j.cag.2026.104647" target="_blank">ScienceDirect</a></p>
  </div>
</div>

<style>
  .publications-page { max-width: 100%; }
  .publication-card {
    border: 1px solid rgba(120, 130, 150, 0.18);
    border-radius: 14px;
    padding: 1.5rem 1.4rem;
    margin-top: 1.25rem;
    background: rgba(255, 255, 255, 0.02);
  }
  .publication-header {
    display: flex;
    flex-direction: column;
    gap: 0.45rem;
    margin-bottom: 0.9rem;
  }
  .publication-card h2 {
    margin: 0;
    line-height: 1.4;
  }
  .venue-badge {
    display: inline-block;
    font-size: 0.8rem;
    letter-spacing: 0.02em;
    color: var(--link-color, #3a6ea5);
    font-weight: 600;
  }
  .placeholder-note {
    margin-top: 1rem;
    color: var(--text-muted-color, #6b7280);
  }
  .dynamic-title,
  .page-header {
    display: none !important;
  }
</style>
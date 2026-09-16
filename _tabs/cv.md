---
title: CV
icon: fas fa-file-lines
order: 6
---

<div class="cv-page">

  <section class="cv-intro">
    <h2>Curriculum Vitae</h2>

    <p>
      My current research CV, including education, research experience,
      publications, projects, and technical skills.
    </p>

    <div class="cv-actions">
      <a
        class="cv-button"
        href="{{ '/assets/pdf/Anshuman%20Mishra%20Research%20Resume.pdf' | relative_url }}"
        target="_blank"
        rel="noopener noreferrer"
      >
        <i class="fas fa-file-pdf"></i>
        Open CV
      </a>

      <a
        class="cv-button cv-button-secondary"
        href="{{ '/assets/pdf/Anshuman%20Mishra%20Research%20Resume.pdf' | relative_url }}"
        download
      >
        <i class="fas fa-download"></i>
        Download PDF
      </a>
    </div>
  </section>


  <section class="cv-preview">
    <div class="preview-header">
      <span>Research Resume</span>
      <span>PDF</span>
    </div>

    <iframe
      src="{{ '/assets/pdf/Anshuman%20Mishra%20Research%20Resume.pdf' | relative_url }}"
      title="Anshuman Mishra Research Resume"
      loading="lazy">
    </iframe>
  </section>

</div>


<style>
  .cv-page {
    max-width: 900px;
  }

  .cv-intro {
    margin-bottom: 2rem;
  }

  .cv-intro h2 {
    font-size: 1.8rem;
    margin-bottom: 0.7rem;
  }

  .cv-intro p {
    max-width: 700px;
    line-height: 1.75;
    color: var(--text-muted-color, #6b7280);
  }

  .cv-actions {
    display: flex;
    flex-wrap: wrap;
    gap: 0.7rem;
    margin-top: 1.4rem;
  }

  .cv-button {
    display: inline-flex;
    align-items: center;
    gap: 0.5rem;
    padding: 0.65rem 1rem;
    border-radius: 0.55rem;
    font-size: 0.9rem;
    font-weight: 600;
    text-decoration: none;
    border: 1px solid var(--link-color, #3a6ea5);
    background: var(--link-color, #3a6ea5);
    color: #fff !important;
    transition: opacity 0.2s ease;
  }

  .cv-button:hover {
    opacity: 0.85;
  }

  .cv-button-secondary {
    background: transparent;
    color: var(--link-color, #3a6ea5) !important;
  }

  .cv-preview {
    margin-top: 2.5rem;
    border: 1px solid rgba(120, 130, 150, 0.18);
    border-radius: 12px;
    overflow: hidden;
    background: rgba(255, 255, 255, 0.02);
  }

  .preview-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 0.75rem 1rem;
    border-bottom: 1px solid rgba(120, 130, 150, 0.15);
    font-size: 0.85rem;
    font-weight: 600;
  }

  .preview-header span:last-child {
    color: var(--text-muted-color, #6b7280);
    font-weight: 500;
  }

  .cv-preview iframe {
    display: block;
    width: 100%;
    height: 1100px;
    border: 0;
    background: #fff;
  }

  .dynamic-title,
  .page-header {
    display: none !important;
  }

  @media (max-width: 767px) {
    .cv-page {
      max-width: 100%;
    }

    .cv-intro h2 {
      font-size: 1.55rem;
    }

    .cv-actions {
      flex-direction: column;
      align-items: stretch;
    }

    .cv-button {
      justify-content: center;
    }

    .cv-preview {
      margin-top: 2rem;
    }

    .cv-preview iframe {
      height: 800px;
    }
  }
</style>
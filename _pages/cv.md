---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---

{% assign cv_path = '/assets/UrviMaheshwari_CV_Nov26.pdf' | relative_url %}

<div class="document-container">

  <!-- Black-and-white download button -->
  <div class="document-actions">
    <a
      href="{{ cv_path }}"
      class="download-button"
      download="UrviMaheshwari_CV_Nov26.pdf"
      aria-label="Download CV as PDF"
    >
      ↓ Download PDF
    </a>
  </div>

  <!-- Embedded PDF -->
  <div class="document-frame">
    <object
      data="{{ cv_path }}#toolbar=0&navpanes=0"
      type="application/pdf"
      aria-label="Embedded CV">
      <p class="pdf-fallback">
        Your browser can't display the PDF inline.
        <a href="{{ cv_path }}" target="_blank" rel="noopener noreferrer">Open the CV in a new tab</a>
        or use the download button above.
      </p>
    </object>
  </div>

</div>

<style>
  .document-container {
    width: 100%;
    max-width: 100%;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }

  .document-actions {
    display: flex;
    justify-content: flex-end;
    margin: 0 0 12px 0;
  }

  .download-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 8px;
    padding: 10px 16px;
    background-color: #ffffff;
    color: #000000;
    border: 1px solid #000000;
    border-radius: 4px;
    font-family: Arial, sans-serif;
    font-size: 14px;
    font-weight: 600;
    text-decoration: none;
    cursor: pointer;
    transition: background-color 0.2s, color 0.2s;
  }

  .download-button:hover {
    background-color: #000000;
    color: #ffffff;
  }

  .document-frame {
    width: 100%;
    height: 100vh;
    min-height: 600px;
    overflow: hidden;
  }

  .document-frame object {
    display: block;
    width: 100%;
    height: 100%;
    border: none;
  }

  .pdf-fallback {
    padding: 16px;
    font-family: Arial, sans-serif;
    font-size: 14px;
  }

  @media (max-width: 600px) {
    .document-actions {
      justify-content: center;
      margin-bottom: 10px;
    }

    .download-button {
      width: 100%;
      box-sizing: border-box;
      padding: 12px 16px;
      font-size: 16px;
    }

    .document-frame {
      height: 85vh;
      min-height: 500px;
    }
  }
</style>

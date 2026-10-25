---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
---

<div class="document-container">

  <!-- Black-and-white download button -->
  <div class="document-actions">
    <a
      href="https://docs.google.com/document/d/13SmAmiU46pZHb3BbJMQa6AihOLB_16Hz/export?format=pdf"
      class="download-button"
      target="_blank"
      rel="noopener noreferrer"
      aria-label="Download document as PDF"
    >
      ↓ Download PDF
    </a>
  </div>

  <!-- Responsive embedded document -->
  <div class="document-frame">
    <iframe
      src="https://docs.google.com/document/d/13SmAmiU46pZHb3BbJMQa6AihOLB_16Hz/edit?usp=sharing&ouid=108036607132632181935&rtpof=true&sd=true"
      title="Embedded document"
      loading="lazy">
    </iframe>
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

  .document-frame iframe {
    display: block;
    width: 100%;
    height: 100%;
    border: none;
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


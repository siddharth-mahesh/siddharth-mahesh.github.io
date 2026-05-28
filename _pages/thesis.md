---
layout: page
title: PhD Thesis
permalink: /thesis/
description: My PhD thesis.
nav: false
_styles: |
  .thesis-viewer {
    width: 100%;
  }

  .thesis-viewer iframe {
    width: 100%;
    height: 85vh;
    border: 1px solid var(--global-divider-color, #d8d8d8);
    border-radius: 0.5rem;
    background: #fff;
  }

  @media (max-width: 768px) {
    .thesis-viewer iframe {
      height: 75vh;
    }
  }
---

<div class="thesis-viewer">
  <iframe
    src="{{ '/thesis.pdf' | relative_url }}"
    title="PhD Thesis PDF"
    loading="lazy"
  ></iframe>
</div>

<p class="mt-3">
  <a href="{{ '/Thesis.pdf' | relative_url }}" target="_blank" rel="noopener">Open the thesis PDF in a new tab</a>
</p>

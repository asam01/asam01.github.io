---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

{% assign cv_pdf_path = '/files/AneeshaResume10.27.2025.docx.pdf' | relative_url %}

<div class="page__content">
  <p>You can view my most recent CV below. A download link is also provided in case the embedded viewer does not load in your browser.</p>

  <p><a class="btn" href="{{ cv_pdf_path }}" target="_blank" rel="noopener">Download CV (PDF)</a></p>

  <object data="{{ cv_pdf_path }}" type="application/pdf" width="100%" height="900" aria-label="Embedded CV for Aneesha Sampath">
    <p>Your browser does not support embedded PDFs. Please <a href="{{ cv_pdf_path }}">download the CV</a> to view it.</p>
  </object>
</div>

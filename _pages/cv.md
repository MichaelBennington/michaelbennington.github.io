---
layout: single
title: "Curriculum Vitae"
permalink: /cv/
---

<div class="cv-box">
  <div class="cv-box__header">
    <h2 class="cv-box__title">Curriculum Vitae</h2>

    <!-- Corrected Download Button -->
    <a
      class="cv-download btn"
      href="{{ '/files/Michael Bennington - CV.pdf' | relative_url }}"
      download
      target="_blank"
      rel="noopener"
    >
      Download PDF
    </a>
  </div>

  <div class="cv-box__viewer">
    <!-- Primary: iframe points to the PDF (NOT /cv/) -->
    <iframe
      src="{{ '/files/Michael Bennington - CV.pdf' | relative_url }}"
      width="100%"
      height="800"
      style="border: none;"
      title="CV PDF"
    ></iframe>

    <!-- Fallback: object
    <object
      data="{{ '/files/Michael Bennington - CV.pdf' | relative_url }}"
      type="application/pdf"
      width="100%"
      height="900"
    >
      <p>
        Your browser can’t display PDFs inline.
        <a href="{{ '/files/Michael Bennington - CV.pdf' | relative_url }}" download>Download the CV</a>.
      </p>
    </object> -->
  </div>
</div>

<style>
/* === CV box styles (scoped; won’t touch global layout) === */
.cv-box {
  background: #121212;        /* to match your publication card background */
  color: #F0F0F0;
  border: 1px solid #e3e6e8;  /* matches your card border tone */
  border-radius: 12px;
  padding: 12px 14px 14px;    /* same as .pub-card-body */
  box-shadow: 0 8px 24px rgba(0,0,0,0.08);
}

/* Header row */
.cv-box__header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  margin-bottom: 8px;
}
.cv-box__title {
  margin: 0;
  font-size: 1.05rem;
  line-height: 1.3;
  font-weight: 700;
}

/* Button styling in your accent color */
.cv-download.btn {
  background-color: #9c27b0;
  color: #fff;
  font-weight: 700;
  padding: 10px 16px;
  border-radius: 8px;
  text-decoration: none !important;
  display: inline-block;
}
.cv-download.btn:hover { background-color: #7b1fa2; }

/* Viewer box */
.cv-box__viewer {
  border-radius: 10px;
  overflow: hidden;
  background: #1a1a1a;
}

/* IMPORTANT: Do NOT force full-width page containers here.
   Let the theme manage the content column and sidebar sizes. */

/* Responsive height tweak (optional) */
@media (max-width: 768px) {
  .cv-box__viewer iframe,
  .cv-box__viewer object {
    height: 70vh;
  }
}
</style>

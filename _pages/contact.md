---
layout: page
permalink: /contact/
title: Contact
#description: Contact information and professional social media links.
nav: true
nav_order: 6
---

<style>
  /* =========================================================
     CONTACT PAGE — CLEAN ACADEMIC WHITE STYLE
     ========================================================= */

  .contact-page {
    width: 100%;
    max-width: 1000px;
    margin: 0 auto;
    padding: 15px 0 35px;

    background: #ffffff !important;
    color: #222222 !important;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;
  }


  /* =========================================================
     CONTACT GRID
     ========================================================= */

  .contact-grid {
    display: grid;

    grid-template-columns: repeat(3, 1fr);

    gap: 22px;

    align-items: stretch;
  }


  /* =========================================================
     CONTACT CARD
     ========================================================= */

  .contact-card {
    display: flex;

    flex-direction: column;

    align-items: center;

    justify-content: space-between;

    min-height: 210px;

    padding: 28px 20px;

    text-align: center;

    background: #ffffff !important;

    border: 1px solid #d2d2d2;

    border-radius: 7px;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.07);

    transition:
      transform 0.2s ease,
      box-shadow 0.2s ease,
      border-color 0.2s ease;
  }


  .contact-card:hover {
    transform: translateY(-3px);

    border-color: #999999;

    box-shadow:
      0 7px 20px rgba(0, 0, 0, 0.10);

    background: #ffffff !important;
  }


  /* =========================================================
     ICON
     ========================================================= */

  .contact-icon {
    display: flex;

    align-items: center;

    justify-content: center;

    width: 58px;

    height: 58px;

    margin-bottom: 15px;

    background: #ffffff !important;

    color: #000000 !important;

    font-size: 32px;
  }


  /* =========================================================
     TITLE
     ========================================================= */

  .contact-title {
    margin: 0 0 20px;

    background: transparent !important;

    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-size: 20px;

    font-weight: 700;

    line-height: 1.4;
  }


  /* =========================================================
     ALL CONTACT BUTTONS
     ========================================================= */

  .contact-button {
    display: inline-flex;

    align-items: center;

    justify-content: center;

    min-height: 40px;

    max-width: 100%;

    padding: 8px 15px;

    background: #ffffff !important;

    color: #000000 !important;

    border: 1px solid #000000 !important;

    border-radius: 4px;

    font-family:
      Arial,
      Helvetica,
      sans-serif;

    font-size: 13px;

    font-weight: 600;

    line-height: 1.4;

    text-decoration: none !important;

    word-break: break-word;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }


  /* =========================================================
     BUTTON HOVER
     ========================================================= */

  .contact-button:hover {
    background: #f5f5f5 !important;

    color: #000000 !important;

    border-color: #000000 !important;

    text-decoration: none !important;

    transform: translateY(-1px);
  }


  /* =========================================================
     PRIMARY EMAIL BUTTON
     IMPORTANT: WHITE BOX
     ========================================================= */

  .contact-button.primary {
    background: #ffffff !important;

    color: #000000 !important;

    border: 1px solid #000000 !important;
  }


  .contact-button.primary:hover {
    background: #f5f5f5 !important;

    color: #000000 !important;

    border-color: #000000 !important;
  }


  /* =========================================================
     PAGE BACKGROUND
     ========================================================= */

  body {
    background: #ffffff !important;
  }


  main {
    background: #ffffff !important;
  }


  .container {
    background: #ffffff !important;
  }


  /* =========================================================
     FOOTER
     ========================================================= */

  .site-footer {
    background: #ffffff !important;

    color: #111111 !important;

    border-top: 2px solid #000000;

    margin-top: 40px;

    padding: 25px 0;
  }


  .site-footer p {
    margin: 0;

    background: transparent !important;

    color: #111111 !important;

    text-align: center;

    font-family:
      Arial,
      Helvetica,
      sans-serif;

    font-size: 14px;

    line-height: 1.5;
  }


  /* =========================================================
     TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .contact-page {
      padding-left: 20px;
      padding-right: 20px;
    }

    .contact-grid {
      grid-template-columns: repeat(2, 1fr);
    }
  }


  /* =========================================================
     MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .contact-page {
      padding-left: 15px;
      padding-right: 15px;
    }

    .contact-grid {
      grid-template-columns: 1fr;

      max-width: 430px;

      margin: 0 auto;

      gap: 18px;
    }

    .contact-card {
      min-height: 190px;

      padding: 25px 18px;
    }

    .contact-title {
      font-size: 19px;
    }

    .contact-button {
      font-size: 13px;
    }
  }


  /* =========================================================
     SMALL MOBILE
     ========================================================= */

  @media (max-width: 480px) {

    .contact-page {
      padding-left: 10px;
      padding-right: 10px;
    }

    .contact-card {
      min-height: 180px;

      padding: 23px 15px;
    }

    .contact-icon {
      width: 50px;

      height: 50px;

      font-size: 29px;
    }

    .contact-title {
      font-size: 18px;

      margin-bottom: 17px;
    }

    .contact-button {
      font-size: 12px;

      padding: 7px 12px;
    }

    .site-footer {
      padding: 22px 0;
    }
  }
</style>


<div class="contact-page">

  <div class="contact-grid">

    <!-- Email -->
    <div class="contact-card">

      <div>

        <div class="contact-icon">
          <i class="fas fa-envelope"></i>
        </div>

        <h3 class="contact-title">
          Email
        </h3>

      </div>

      <a
        href="mailto:shakil.ahmed@bubt.edu.bd"
        class="contact-button primary"
      >
        shakil.ahmed@bubt.edu.bd
      </a>

    </div>


    <!-- LinkedIn -->
    <div class="contact-card">

      <div>

        <div class="contact-icon">
          <i class="fab fa-linkedin"></i>
        </div>

        <h3 class="contact-title">
          LinkedIn
        </h3>

      </div>

      <a
        href="https://www.linkedin.com/in/md-shakil-ahmed-6482b13b3/"
        class="contact-button"
        target="_blank"
        rel="noopener noreferrer"
      >
        Connect
      </a>

    </div>


    <!-- Twitter / X -->
    <div class="contact-card">

      <div>

        <div class="contact-icon">
          <i class="fab fa-twitter"></i>
        </div>

        <h3 class="contact-title">
          Twitter
        </h3>

      </div>

      <a
        href="https://x.com/home"
        class="contact-button"
        target="_blank"
        rel="noopener noreferrer"
      >
        Follow
      </a>

    </div>

  </div>

</div>


<footer class="site-footer">

  <div class="container text-center">

    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>

  </div>

</footer>
---
layout: page
permalink: /contact/
title: Contact
nav: true
nav_order: 6
---

<style>
  :root {
    --contact-card: #213d69;
    --contact-border: #4c6d9f;
    --contact-text: #ffffff;
    --contact-icon: #a9c3ff;
    --contact-button-bg: #1e3559;
    --contact-button-border: #a9c3ff;
  }

  .contact-page {
    width: 100%;
    max-width: 1100px;
    margin: 0 auto;
    padding: 20px 0 20px;
  }

  .contact-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 24px;
    width: 100%;
  }

  .contact-card {
    min-height: 230px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: space-between;
    padding: 32px 20px 30px;
    text-align: center;

    background: var(--contact-card);
    border: 1px solid var(--contact-border);
    border-radius: 16px;

    box-shadow: 0 8px 20px rgba(0, 0, 0, 0.22);

    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .contact-card:hover {
    transform: translateY(-5px);
    border-color: #6d8fca;
    box-shadow: 0 12px 28px rgba(0, 0, 0, 0.3);
  }

  .contact-card-top {
    display: flex;
    flex-direction: column;
    align-items: center;
  }

  .contact-icon {
    display: flex;
    align-items: center;
    justify-content: center;

    width: 58px;
    height: 58px;
    margin-bottom: 14px;

    color: var(--contact-icon);
    font-size: 34px;
  }

  .contact-title {
    margin: 0;
    color: var(--contact-text);
    font-size: 20px;
    font-weight: 700;
  }

  .contact-button {
    display: inline-flex;
    align-items: center;
    justify-content: center;

    min-height: 42px;
    max-width: 100%;
    padding: 9px 16px;

    border: 1px solid var(--contact-button-border);
    border-radius: 7px;

    color: #ffffff !important;
    background: var(--contact-button-bg);

    text-decoration: none !important;
    font-size: 14px;
    font-weight: 600;
    line-height: 1.4;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }

  .contact-button:hover {
    background: #a9c3ff;
    color: #172b4d !important;
    text-decoration: none !important;
    transform: translateY(-2px);
  }

  .contact-button.primary {
    background: #a9bde8;
    border-color: #a9bde8;
    color: #172b4d !important;
  }

  .contact-button.primary:hover {
    background: #c0d0f2;
    color: #172b4d !important;
  }

  .contact-email {
    white-space: nowrap;
  }

  .site-footer {
    margin-top: 40px;
  }

  @media (max-width: 768px) {
    .contact-grid {
      grid-template-columns: 1fr;
      max-width: 420px;
      margin: 0 auto;
    }

    .contact-card {
      min-height: 210px;
    }
  }

  @media (max-width: 576px) {
    .contact-page {
      padding: 10px 0 20px;
    }

    .contact-card {
      padding: 28px 18px;
    }

    .contact-title {
      font-size: 19px;
    }

    .contact-button {
      font-size: 13px;
    }

    .contact-email {
      white-space: normal;
      overflow-wrap: anywhere;
    }

    .site-footer {
      margin-top: 30px;
    }
  }
</style>

<div class="contact-page">

  <div class="contact-grid">

    <div class="contact-card">

      <div class="contact-card-top">
        <div class="contact-icon">
          <i class="fas fa-envelope"></i>
        </div>

        <h3 class="contact-title">Email</h3>
      </div>

      <a
        href="mailto:shakil.ahmed@bubt.edu.bd"
        class="contact-button primary contact-email"
      >
        shakil.ahmed@bubt.edu.bd
      </a>

    </div>

    <div class="contact-card">

      <div class="contact-card-top">
        <div class="contact-icon">
          <i class="fab fa-linkedin"></i>
        </div>

        <h3 class="contact-title">LinkedIn</h3>
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

    <div class="contact-card">

      <div class="contact-card-top">
        <div class="contact-icon">
          <i class="fab fa-twitter"></i>
        </div>

        <h3 class="contact-title">Twitter</h3>
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
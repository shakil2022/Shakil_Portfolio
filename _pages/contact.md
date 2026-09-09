---
layout: page
permalink: /contact/
title: Contact
nav: true
nav_order: 6
---

<style>

/* =========================================================
   CONTACT PAGE
   Clean white + black academic design
   ========================================================= */

.contact-page {
  width: 100%;
  max-width: 1100px;

  margin: 0 auto;

  padding: 20px 0 35px;
}


/* =========================================================
   CONTACT GRID
   ========================================================= */

.contact-grid {
  display: grid;

  grid-template-columns: repeat(3, 1fr);

  gap: 22px;

  width: 100%;
}


/* =========================================================
   CONTACT CARD
   ========================================================= */

.contact-card {
  min-height: 220px;

  display: flex;

  flex-direction: column;

  align-items: center;

  justify-content: space-between;

  padding: 30px 22px 28px;

  text-align: center;

  /*
    Very light white/gray card.
    The subtle shadow makes the box visible
    without introducing another color.
  */
  background: #ffffff;

  border: 1px solid #d6d6d6;

  border-radius: 8px;

  box-shadow:
    0 4px 14px rgba(0, 0, 0, 0.08);

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}


/* =========================================================
   CARD HOVER
   ========================================================= */

.contact-card:hover {
  transform: translateY(-4px);

  border-color: #999999;

  box-shadow:
    0 10px 25px rgba(0, 0, 0, 0.13);
}


/* =========================================================
   CARD TOP AREA
   ========================================================= */

.contact-card-top {
  display: flex;

  flex-direction: column;

  align-items: center;

  justify-content: center;
}


/* =========================================================
   CONTACT ICON
   ========================================================= */

.contact-icon {
  display: flex;

  align-items: center;

  justify-content: center;

  width: 60px;

  height: 60px;

  margin-bottom: 15px;

  /*
    Black icon only.
  */
  color: #000000;

  font-size: 32px;
}


/* =========================================================
   CONTACT TITLE
   ========================================================= */

.contact-title {
  margin: 0;

  color: #000000;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 20px;

  font-weight: 700;

  line-height: 1.4;
}


/* =========================================================
   EMAIL LINK
   ========================================================= */

.contact-card > a:not(.contact-button) {
  display: inline-block;

  max-width: 100%;

  color: #000000 !important;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 15px;

  font-weight: 500;

  line-height: 1.5;

  text-decoration: underline;

  text-decoration-thickness: 1px;

  text-underline-offset: 3px;

  overflow-wrap: anywhere;

  transition: opacity 0.2s ease;
}


.contact-card > a:not(.contact-button):hover {
  color: #000000 !important;

  opacity: 0.6;
}


/* =========================================================
   CONTACT BUTTON
   ========================================================= */

.contact-button {
  display: inline-flex;

  align-items: center;

  justify-content: center;

  min-width: 105px;

  min-height: 42px;

  max-width: 100%;

  padding: 9px 20px;

  border: 1px solid #000000;

  border-radius: 5px;

  /*
    White button with black text.
  */
  color: #000000 !important;

  background: #ffffff;

  text-decoration: none !important;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 14px;

  font-weight: 600;

  line-height: 1.4;

  transition:
    background-color 0.2s ease,
    color 0.2s ease,
    transform 0.2s ease;
}


/* =========================================================
   BUTTON HOVER
   ========================================================= */

.contact-button:hover {
  background: #000000;

  color: #ffffff !important;

  border-color: #000000;

  text-decoration: none !important;

  transform: translateY(-2px);
}


/* =========================================================
   EMAIL
   ========================================================= */

.contact-email {
  white-space: nowrap;
}


/* =========================================================
   FOOTER
   ========================================================= */

.site-footer {
  background: #ffffff !important;

  color: #111111 !important;

  border-top: 2px solid #000000;

  margin-top: 0;

  padding: 25px 0;
}


.site-footer p {
  margin: 0;

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

  .contact-grid {
    grid-template-columns: 1fr;

    max-width: 480px;

    margin: 0 auto;

    gap: 18px;
  }


  .contact-card {
    min-height: 205px;

    padding: 28px 20px 25px;
  }


  .contact-title {
    font-size: 19px;
  }


  .contact-icon {
    font-size: 30px;

    width: 55px;

    height: 55px;
  }

}


/* =========================================================
   SMALL MOBILE
   ========================================================= */

@media (max-width: 576px) {

  .contact-page {
    padding: 10px 18px 25px;
  }


  .contact-card {
    min-height: 195px;

    padding: 25px 18px;
  }


  .contact-title {
    font-size: 18px;
  }


  .contact-button {
    min-width: 95px;

    min-height: 40px;

    font-size: 13px;

    padding: 8px 16px;
  }


  .contact-card > a:not(.contact-button) {
    font-size: 14px;
  }


  .contact-email {
    white-space: normal;

    overflow-wrap: anywhere;
  }


  .site-footer {
    margin-top: 0;

    padding: 22px 0;
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
        href="shakil.ahmed@bubt.edu.bd">
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
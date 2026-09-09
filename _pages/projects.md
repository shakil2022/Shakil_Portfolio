---
layout: page
title: Projects
permalink: /projects/
nav: true
nav_order: 3
horizontal: false
---
<style>
  /* =========================================================
     PROJECTS PAGE — WHITE / BLACK ACADEMIC STYLE
     ========================================================= */

  .projects,
  .projects .container {
    width: 100%;
    color: #111111;
    font-family: "Source Serif 4", Georgia, "Times New Roman", serif;
    font-size: 18px;
    line-height: 1.8;
  }

  /* Main headings */
  .projects h1,
  .projects h2,
  .projects h3,
  .projects h4,
  .projects h5,
  .projects h6,
  .projects .card-title {
    color: #000000 !important;
    font-family: Georgia, "Times New Roman", serif;
    font-weight: 700;
  }

  .projects h1 {
    font-size: 32px;
  }

  /* =========================================================
     PROJECT GRID
     ========================================================= */

  .projects > .row {
    max-width: 1100px;
    margin-left: auto;
    margin-right: auto;
    row-gap: 24px;
  }

  /* =========================================================
     PROJECT CARDS
     ========================================================= */

  .projects .card {
    height: 100%;
    background: #ffffff;
    color: #111111;

    border: 1px solid #d2d2d2;
    border-radius: 8px;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.07);

    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .projects .card:hover {
    transform: translateY(-4px);

    border-color: #999999;

    box-shadow:
      0 10px 26px rgba(0, 0, 0, 0.13);
  }

  /* =========================================================
     CARD BODY
     ========================================================= */

  .projects .card-body {
    padding: 24px;
    background: #ffffff;
  }

  /* Project title */
  .projects .card-title {
    margin-top: 0;
    margin-bottom: 12px;

    color: #000000 !important;

    font-family: Georgia, "Times New Roman", serif;
    font-size: 21px;
    line-height: 1.45;
    font-weight: 700;
  }

  /* Project description */
  .projects .card-text,
  .projects .card-subtitle {
    color: #2b2b2b !important;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 16px;
    line-height: 1.75;

    text-align: justify;
    text-justify: inter-word;
  }

  /* Muted text */
  .projects .text-muted {
    color: #555555 !important;
  }

  /* =========================================================
     PROJECT LINKS
     ========================================================= */

  .projects .card a,
  .projects a.stretched-link {
    color: #000000 !important;
    text-decoration: underline;

    text-decoration-thickness: 1px;
    text-underline-offset: 3px;

    transition: opacity 0.2s ease;
  }

  .projects .card a:hover,
  .projects a.stretched-link:hover {
    color: #000000 !important;
    opacity: 0.6;
  }

  /* =========================================================
     PROJECT IMAGE
     ========================================================= */

  .projects .card-img-top {
    width: 100%;
    height: 210px;
    object-fit: cover;

    border-bottom: 1px solid #d6d6d6;
  }

  /* =========================================================
     TAGS / BADGES
     ========================================================= */

  .projects .badge,
  .projects .tag {
    display: inline-block;

    padding: 5px 10px;

    background: #f5f5f5 !important;
    color: #222222 !important;

    border: 1px solid #cfcfcf;

    border-radius: 4px;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 12px;
    font-weight: 600;

    line-height: 1.4;
  }

  /* =========================================================
     BUTTONS
     ========================================================= */

  .projects .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;

    padding: 8px 17px;

    background: #ffffff !important;
    color: #000000 !important;

    border: 1px solid #000000;
    border-radius: 5px;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 13px;
    font-weight: 600;

    text-decoration: none !important;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }

  .projects .btn:hover {
    background: #000000 !important;
    color: #ffffff !important;

    border-color: #000000;

    transform: translateY(-2px);
  }

  /* =========================================================
     DIVIDERS
     ========================================================= */

  .projects hr,
  .projects .divider {
    border: none;
    border-top: 2px solid #000000;
    margin: 30px auto;
  }

  /* =========================================================
     HORIZONTAL PROJECTS
     ========================================================= */

  .projects .row-cols-md-2 .card {
    min-height: 200px;
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

    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
    line-height: 1.5;
  }

  /* =========================================================
     TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .projects {
      font-size: 17px;
    }

    .projects > .row {
      padding-left: 20px;
      padding-right: 20px;
      row-gap: 20px;
    }

    .projects .card-body {
      padding: 22px;
    }

    .projects .card-title {
      font-size: 20px;
    }

    .projects .card-text,
    .projects .card-subtitle {
      font-size: 16px;
    }
  }

  /* =========================================================
     MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .projects {
      font-size: 17px;
      line-height: 1.75;
    }

    .projects > .row {
      padding-left: 15px;
      padding-right: 15px;
    }

    .projects .card {
      border-radius: 7px;
    }

    .projects .card-body {
      padding: 20px;
    }

    .projects .card-title {
      font-size: 19px;
    }

    .projects .card-text,
    .projects .card-subtitle {
      font-size: 15.5px;
      line-height: 1.7;
      text-align: left;
    }

    .projects .card-img-top {
      height: 190px;
    }
  }

  /* =========================================================
     SMALL MOBILE
     ========================================================= */

  @media (max-width: 480px) {

    .projects > .row {
      padding-left: 10px;
      padding-right: 10px;
      row-gap: 16px;
    }

    .projects .card-body {
      padding: 18px;
    }

    .projects .card-title {
      font-size: 18px;
    }

    .projects .card-text,
    .projects .card-subtitle {
      font-size: 15px;
    }

    .projects .card-img-top {
      height: 170px;
    }

    .site-footer {
      padding: 22px 0;
    }
  }
</style>

<div class="projects">

  {% assign sorted_projects = site.projects | sort: "importance" %}

  {% if page.horizontal %}

    <div class="container">
      <div class="row row-cols-1 row-cols-md-2">

        {% for project in sorted_projects %}
          {% include projects_horizontal.liquid %}
        {% endfor %}

      </div>
    </div>

  {% else %}

    <div class="row row-cols-1 row-cols-md-3">

      {% for project in sorted_projects %}
        {% include projects.liquid %}
      {% endfor %}

    </div>

  {% endif %}

</div>

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>
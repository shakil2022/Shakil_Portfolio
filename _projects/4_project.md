---
layout: page
title: Learning Management System
description: A full-stack Learning Management System with React, Node.js, Express, MongoDB, and Docker.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---
<style>
  /* =========================================================
     PROJECT DETAIL PAGE
     WHITE / BLACK ACADEMIC STYLE
     ========================================================= */

  .project-card,
  .project-content {
    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    color: #111111;
  }

  /* =========================================================
     MAIN PROJECT HEADER CARD
     ========================================================= */

  .project-card {
    position: relative;

    padding: 28px 30px;
    margin: 20px 0 35px;

    background: #ffffff;

    border: 1px solid #d2d2d2;
    border-radius: 8px;

    box-shadow:
      0 5px 16px rgba(0, 0, 0, 0.08);

    color: #111111;

    transition:
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .project-card:hover {
    border-color: #999999;

    box-shadow:
      0 10px 26px rgba(0, 0, 0, 0.12);
  }

  /* =========================================================
     PROJECT HEADER
     ========================================================= */

  .project-header {
    display: flex;
    align-items: center;

    gap: 16px;

    margin-bottom: 18px;
  }

  .project-icon {
    width: 58px;
    height: 58px;

    display: flex;
    align-items: center;
    justify-content: center;

    flex-shrink: 0;

    background: #f5f5f5;

    border: 1px solid #bdbdbd;
    border-radius: 7px;

    color: #000000;

    font-size: 28px;
  }

  .project-title {
    margin: 0 !important;

    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-size: 26px;
    font-weight: 700;

    line-height: 1.4;
  }

  .project-subtitle {
    margin: 6px 0 0;

    color: #444444;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 16px;
    font-weight: 400;

    line-height: 1.65;
  }

  /* =========================================================
     PROJECT DESCRIPTION
     ========================================================= */

  .project-description {
    margin-top: 20px;

    color: #222222;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 16px;
    line-height: 1.8;

    text-align: justify;
    text-justify: inter-word;
  }

  .project-description strong {
    color: #000000;
    font-weight: 700;
  }

  /* =========================================================
     PROJECT TAGS
     ========================================================= */

  .project-tags {
    display: flex;
    flex-wrap: wrap;

    gap: 8px;

    margin-top: 20px;
  }

  .project-tag {
    display: inline-block;

    padding: 5px 10px;

    background: #f4f4f4;

    border: 1px solid #cccccc;
    border-radius: 4px;

    color: #222222;

    font-family: Arial, Helvetica, sans-serif;

    font-size: 12px;
    font-weight: 600;

    line-height: 1.4;
  }

  /* =========================================================
     PROJECT BUTTONS
     ========================================================= */

  .project-buttons {
    display: flex;
    flex-wrap: wrap;

    gap: 10px;

    margin-top: 22px;
  }

  .project-button {
    display: inline-flex;

    align-items: center;
    justify-content: center;

    gap: 8px;

    padding: 9px 17px;

    background: #ffffff;

    border: 1px solid #000000;
    border-radius: 5px;

    color: #000000 !important;

    font-family: Arial, Helvetica, sans-serif;

    font-size: 13px;
    font-weight: 600;

    line-height: 1.4;

    text-decoration: none !important;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }

  .project-button:hover {
    background: #000000;

    color: #ffffff !important;

    border-color: #000000;

    transform: translateY(-2px);

    text-decoration: none !important;
  }

  .project-button.primary,
  .project-button.secondary {
    background: #ffffff;
    color: #000000 !important;
  }

  .project-button.primary:hover,
  .project-button.secondary:hover {
    background: #000000;
    color: #ffffff !important;
  }

  /* =========================================================
     PROJECT CONTENT
     ========================================================= */

  .project-content {
    max-width: 1000px;

    margin: 0 auto;

    color: #111111;
  }

  .project-content p {
    margin-top: 0;
    margin-bottom: 18px;

    color: #222222;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 17px;

    line-height: 1.8;

    text-align: justify;
    text-justify: inter-word;
  }

  .project-content strong {
    color: #000000;
    font-weight: 700;
  }

  /* =========================================================
     SECTION HEADINGS
     ========================================================= */

  .project-section-title {
    margin-top: 34px;
    margin-bottom: 18px;

    padding-bottom: 8px;

    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-size: 27px;

    font-weight: 700;

    line-height: 1.4;

    border-bottom: 2px solid #000000;
  }

  /* =========================================================
     FEATURE CARDS
     ========================================================= */

  .project-content .card,
  .feature-card {
    height: 100%;

    background: #ffffff !important;

    border: 1px solid #d2d2d2;

    border-radius: 7px;

    color: #111111;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.06);

    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .project-content .card:hover,
  .feature-card:hover {
    transform: translateY(-3px);

    border-color: #999999;

    box-shadow:
      0 9px 22px rgba(0, 0, 0, 0.11);
  }

  .project-content .card-body {
    padding: 22px;
  }

  /* =========================================================
     CARD TITLES
     ========================================================= */

  .project-content .card-title {
    margin-top: 0;
    margin-bottom: 12px;

    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-size: 19px;

    font-weight: 700;

    line-height: 1.45;
  }

  .project-content .card-title i {
    margin-right: 7px;

    color: #000000;
  }

  /* =========================================================
     CARD TEXT
     ========================================================= */

  .project-content .card-text {
    margin-bottom: 0;

    color: #333333;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 15.5px;

    line-height: 1.75;

    text-align: justify;
    text-justify: inter-word;
  }

  /* =========================================================
     LISTS
     ========================================================= */

  .project-content ul {
    margin-top: 8px;
    margin-bottom: 10px;

    padding-left: 22px;

    color: #222222;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 16px;

    line-height: 1.75;
  }

  .project-content li {
    margin-bottom: 6px;
  }

  .project-content li strong {
    color: #000000;
  }

  /* =========================================================
     IMAGES
     ========================================================= */

  .project-content img {
    border: 1px solid #d2d2d2;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.08);

    border-radius: 6px;
  }

  .caption {
    margin-top: 10px;
    margin-bottom: 20px;

    color: #555555;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 14px;

    line-height: 1.6;

    text-align: center;

    font-style: italic;
  }

  /* =========================================================
     TABLES
     ========================================================= */

  .project-content .table {
    width: 100%;

    margin-top: 10px;
    margin-bottom: 25px;

    background: #ffffff;

    color: #222222;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 15.5px;

    line-height: 1.6;

    border: 1px solid #cfcfcf;
  }

  .project-content .table th {
    padding: 11px 14px;

    background: #f3f3f3;

    color: #000000;

    font-family:
      Arial,
      Helvetica,
      sans-serif;

    font-size: 14px;

    font-weight: 700;

    border: 1px solid #cfcfcf;
  }

  .project-content .table td {
    padding: 10px 14px;

    background: #ffffff;

    color: #222222;

    border: 1px solid #d2d2d2;

    vertical-align: top;
  }

  .project-content .table tbody tr:hover td {
    background: #f8f8f8;
  }

  /* =========================================================
     GENERAL LINKS
     ========================================================= */

  .project-content a {
    color: #000000 !important;

    text-decoration: underline;

    text-decoration-thickness: 1px;
    text-underline-offset: 3px;
  }

  .project-content a:hover {
    color: #000000 !important;
    opacity: 0.6;
  }

  /* =========================================================
     RESPONSIVE — TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .project-card {
      margin-left: 20px;
      margin-right: 20px;

      padding: 25px;
    }

    .project-content {
      padding-left: 20px;
      padding-right: 20px;
    }

    .project-title {
      font-size: 24px;
    }

    .project-content p {
      font-size: 16px;
    }

    .project-section-title {
      font-size: 25px;
    }
  }

  /* =========================================================
     RESPONSIVE — MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .project-card {
      margin: 15px 15px 30px;

      padding: 21px;

      border-radius: 7px;
    }

    .project-header {
      gap: 12px;
    }

    .project-icon {
      width: 52px;
      height: 52px;

      font-size: 25px;
    }

    .project-title {
      font-size: 21px;
    }

    .project-subtitle {
      font-size: 14px;
    }

    .project-description {
      font-size: 15px;

      line-height: 1.75;

      text-align: left;
    }

    .project-content {
      padding-left: 15px;
      padding-right: 15px;
    }

    .project-content p {
      font-size: 15.5px;

      line-height: 1.75;

      text-align: left;
    }

    .project-section-title {
      margin-top: 30px;

      font-size: 23px;
    }

    .project-content .card-title {
      font-size: 18px;
    }

    .project-content .card-text {
      font-size: 15px;

      text-align: left;
    }

    .project-content ul {
      font-size: 15px;
    }

    .project-content .table {
      font-size: 14px;
    }

    .project-content .table th,
    .project-content .table td {
      padding: 9px 10px;
    }
  }

  /* =========================================================
     RESPONSIVE — SMALL MOBILE
     ========================================================= */

  @media (max-width: 576px) {

    .project-card {
      margin-left: 10px;
      margin-right: 10px;

      padding: 18px;
    }

    .project-header {
      align-items: flex-start;
    }

    .project-icon {
      width: 46px;
      height: 46px;

      font-size: 22px;
    }

    .project-title {
      font-size: 19px;
    }

    .project-subtitle {
      font-size: 13.5px;
    }

    .project-description {
      font-size: 14px;
    }

    .project-tags {
      gap: 6px;
    }

    .project-tag {
      font-size: 11px;
      padding: 5px 8px;
    }

    .project-button {
      padding: 8px 13px;

      font-size: 12px;
    }

    .project-content {
      padding-left: 10px;
      padding-right: 10px;
    }

    .project-section-title {
      font-size: 21px;
    }

    .caption {
      font-size: 13px;
    }

    .project-content .table {
      font-size: 13px;
    }
  }
</style>


<div class="project-card">

  <div class="project-header">

    <div class="project-icon">
      <i class="fas fa-graduation-cap"></i>
    </div>

    <div>
      <h1 class="project-title">
        Learning Management System
      </h1>

      <p class="project-subtitle">
        A full-stack Learning Management System for B-JET.
      </p>
    </div>

  </div>


  <div class="project-description">

    Developed a full-stack <strong>Learning Management System (LMS)</strong>
    consisting of separate frontend and backend services. The backend is
    built using <strong>Node.js, Express, and MongoDB</strong>, while the
    frontend is developed using <strong>React</strong>.

    The project is containerized using <strong>Docker</strong> and
    <strong>Docker Compose</strong>, allowing the frontend and backend
    services to be built and launched together in a local development
    environment.

  </div>

Technology:,, Toolkit,Material ,,,.
  <div class="project-tags">

    <span class="project-tag">React</span>
    <span class="project-tag">React</span>
    <span class="project-tag">NRedux</span>
    <span class="project-tag">UI</span>
    <span class="project-tag">TypeScript</span>
    <span class="project-tag">Express.js</span>
    <span class="project-tag">Node.js</span>
    <span class="project-tag">Mongoose</span>

  </div>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Learning-Management-System"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      View Code
    </a>

  </div>

</div>


<div class="project-content">

  <h2 class="project-section-title">
    Project Overview
  </h2>

  <p>
    The Learning Management System (LMS) is a full-stack web application
    developed for B-JET. The system consists of both frontend and backend
    services, providing a structured architecture for developing and
    running the application.
  </p>


  <h2 class="project-section-title">
    System Architecture
  </h2>

  <div class="row justify-content-sm-center">

    <div class="col-sm-6 mt-3 mt-md-0">

      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Frontend
          </h4>

          <p class="card-text">
            The frontend of the LMS is developed using
            <strong>React</strong>.
          </p>

        </div>
      </div>

    </div>


    <div class="col-sm-6 mt-3 mt-md-0">

      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">
            Backend
          </h4>

          <p class="card-text">
            The backend is developed using
            <strong>Node.js, Express, and MongoDB</strong>.
          </p>

        </div>
      </div>

    </div>

  </div>


  <h2 class="project-section-title">
    Key Features
  </h2>

  <ul>

    <li>
      Full-stack Learning Management System architecture.
    </li>

    <li>
      React-based frontend application.
    </li>

    <li>
      Node.js and Express-based backend.
    </li>

    <li>
      MongoDB database integration.
    </li>

    <li>
      Separate frontend and backend services.
    </li>

    <li>
      Docker-based application environment.
    </li>

    <li>
      Docker Compose configuration for running the services together.
    </li>

  </ul>


  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <p>
    <strong>Frontend:</strong> React
  </p>

  <p>
    <strong>Backend:</strong> Node.js, Express
  </p>

  <p>
    <strong>Database:</strong> MongoDB
  </p>

  <p>
    <strong>Deployment & Containerization:</strong> Docker, Docker Compose
  </p>


  <h2 class="project-section-title">
    Running the Project
  </h2>

  <p>
    The project can be run locally using Docker Compose. After configuring
    the required environment variables in the backend directory, the
    frontend and backend services can be built and started together using
    Docker Compose.
  </p>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Learning-Management-System"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>
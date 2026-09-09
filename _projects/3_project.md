---
layout: page
title: QR Code Scanner
description: A feature-rich Android application for generating, scanning, and decoding QR codes with a simple and user-friendly mobile interface.
img: assets/img/qr-code-scanner.jpg
importance: 3
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
      <i class="fas fa-qrcode"></i>
    </div>

    <div>
      <h1 class="project-title">
        QR Code Scanner
      </h1>

      <p class="project-subtitle">
        A Java-based Android application for QR code generation, scanning, and decoding.
      </p>
    </div>

  </div>


  <div class="project-description">

    Developed an Android-based <strong>QR Code Scanner</strong> application
    that provides convenient QR code generation and camera-based scanning
    functionality. The application allows users to generate QR codes from
    text and scan existing QR codes to retrieve their encoded information.

    The project demonstrates practical Android application development
    concepts including <strong>camera integration, QR code encoding and
    decoding, user input processing, and mobile user-interface design</strong>.
    The application is designed to provide a simple, fast, and accessible
    solution for QR-based information sharing and retrieval.

  </div>


  <div class="project-tags">

    <span class="project-tag">Java</span>
    <span class="project-tag">Android</span>
    <span class="project-tag">Android Studio</span>
    <span class="project-tag">Android SDK</span>
    <span class="project-tag">Gradle</span>
    <span class="project-tag">QR Generation</span>
    <span class="project-tag">QR Scanning</span>
    <span class="project-tag">QR Decoding</span>
    <span class="project-tag">Camera Integration</span>

  </div>


  <div class="project-buttons">

    <a
      https://github.com/shakil2022/Remote-Control-Fire-Detection-Car"
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
    The <strong>QR Code Scanner</strong> is an Android mobile application
    developed using <strong>Java</strong> to provide QR code generation,
    scanning, and decoding capabilities. The application combines
    camera-based QR detection with a straightforward mobile interface,
    allowing users to process QR codes efficiently.
  </p>

  <p>
    The application supports two primary operations: users can generate
    QR codes from text-based input and scan existing QR codes using the
    smartphone camera. After successful detection, the encoded information
    can be decoded and displayed to the user.
  </p>


  <h2 class="project-section-title">
    Core Features
  </h2>


  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-qrcode"></i>
            QR Code Generation
          </h4>

          <ul>
            <li>Generate QR codes from user-provided text.</li>
            <li>Convert textual information into QR-code format.</li>
            <li>Provide an easy way to represent information digitally.</li>
            <li>Generate QR codes directly within the Android application.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-camera"></i>
            Camera-Based Scanning
          </h4>

          <ul>
            <li>Scan QR codes using the smartphone camera.</li>
            <li>Detect QR codes through camera-based processing.</li>
            <li>Process QR information directly from the camera view.</li>
            <li>Provide a convenient mobile scanning experience.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-barcode"></i>
            QR Decoding
          </h4>

          <ul>
            <li>Automatically decode detected QR codes.</li>
            <li>Retrieve the information encoded inside the QR code.</li>
            <li>Display decoded content to the user.</li>
            <li>Support fast information retrieval after scanning.</li>
          </ul>

        </div>
      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-mobile-alt"></i>
            Mobile Interface
          </h4>

          <ul>
            <li>Simple and intuitive Android interface.</li>
            <li>Designed for touch-based mobile interaction.</li>
            <li>Lightweight application workflow.</li>
            <li>Easy access to scanning and generation functionality.</li>
          </ul>

        </div>
      </div>
    </div>

  </div>


  <h2 class="project-section-title">
    QR Code Generation & Scanning
  </h2>

  <p>
    The application provides a simple workflow for both creating and
    processing QR codes. Users can enter information into the application
    and generate a corresponding QR code. Alternatively, the scanning
    functionality allows users to use the smartphone camera to detect
    and decode an existing QR code.
  </p>


  <div class="row justify-content-sm-center">

    <div class="col-sm-8 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/qr1.jpg" title="QR Code Scanner Home Interface" class="img-fluid rounded z-depth-1" %}
    </div>

    <div class="col-sm-4 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/qr2.jpg" title="QR Code Generation Interface" class="img-fluid rounded z-depth-1" %}
    </div>

  </div>

  <div class="caption">
    The application provides dedicated functionality for accessing QR code scanning and generation features.
  </div>


  <h2 class="project-section-title">
    Key Features
  </h2>

  <ul>

    <li>
      Generate QR codes from user-provided text.
    </li>

    <li>
      Scan QR codes using the smartphone camera.
    </li>

    <li>
      Automatically detect and decode QR code content.
    </li>

    <li>
      Display decoded information after successful scanning.
    </li>

    <li>
      Camera-based QR code recognition.
    </li>

    <li>
      Fast QR information retrieval.
    </li>

    <li>
      Simple and intuitive Android user interface.
    </li>

    <li>
      Lightweight mobile application workflow.
    </li>

    <li>
      Text-based QR code generation.
    </li>

    <li>
      Integrated QR generation and scanning functionality.
    </li>

  </ul>


  <div class="row">

    <div class="col-sm-6 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/qr3.jpg" title="Camera Based QR Code Scanning" class="img-fluid rounded z-depth-1" %}
    </div>

    <div class="col-sm-6 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/qr4.jpg" title="Decoded QR Code Information" class="img-fluid rounded z-depth-1" %}
    </div>

  </div>

  <div class="caption">
    Camera-based QR scanning allows encoded information to be detected and decoded directly through the Android device.
  </div>


  <h2 class="project-section-title">
    Technical Attributes
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Attribute</th>
          <th>Details</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>Platform</td>
          <td>Android</td>
        </tr>

        <tr>
          <td>Programming Language</td>
          <td>Java</td>
        </tr>

        <tr>
          <td>Development Environment</td>
          <td>Android Studio</td>
        </tr>

        <tr>
          <td>Build System</td>
          <td>Gradle</td>
        </tr>

        <tr>
          <td>Application Type</td>
          <td>Mobile Application</td>
        </tr>

        <tr>
          <td>QR Generation</td>
          <td>Supported</td>
        </tr>

        <tr>
          <td>QR Scanning</td>
          <td>Camera Based</td>
        </tr>

        <tr>
          <td>QR Decoding</td>
          <td>Automatic</td>
        </tr>

        <tr>
          <td>User Interface</td>
          <td>Android XML Layout</td>
        </tr>

        <tr>
          <td>Hardware Integration</td>
          <td>Smartphone Camera</td>
        </tr>

      </tbody>

    </table>

  </div>


  <h2 class="project-section-title">
    Application Workflow
  </h2>


  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-edit"></i>
            1. Enter Information
          </h4>

          <p class="card-text">
            The user provides text or other supported information that
            needs to be converted into a QR code.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-qrcode"></i>
            2. Generate QR Code
          </h4>

          <p class="card-text">
            The application processes the input and generates a QR code
            representing the provided information.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-camera"></i>
            3. Scan QR Code
          </h4>

          <p class="card-text">
            The user activates the camera-based scanner and points the
            smartphone toward an existing QR code.
          </p>

        </div>

      </div>
    </div>


    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-check-circle"></i>
            4. Decode Information
          </h4>

          <p class="card-text">
            After detection, the application decodes the QR content and
            presents the resulting information to the user.
          </p>

        </div>

      </div>
    </div>

  </div>


  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <p>
    <strong>Programming Language:</strong> Java
  </p>

  <p>
    <strong>Platform:</strong> Android
  </p>

  <p>
    <strong>Development Environment:</strong> Android Studio
  </p>

  <p>
    <strong>Build System:</strong> Gradle
  </p>

  <p>
    <strong>UI Technology:</strong> Android XML Layout
  </p>

  <p>
    <strong>Hardware Integration:</strong> Smartphone Camera
  </p>

  <p>
    <strong>Core Functionality:</strong> QR Code Encoding, Scanning, and Decoding
  </p>


  <div class="row justify-content-sm-center">

    <div class="col-sm-10 mt-3 mt-md-0">
      {% include figure.liquid loading="eager" path="assets/img/qr5.jpg" title="Complete QR Code Scanner Application" class="img-fluid rounded z-depth-1" %}
    </div>

  </div>

  <div class="caption">
    Complete QR Code Scanner application demonstrating the integration of QR generation, camera-based scanning, and information decoding.
  </div>


  <h2 class="project-section-title">
    Project Highlights
  </h2>

  <p>
    This project showcases practical experience in
    <strong>Android mobile application development, QR code generation,
    camera integration, real-time QR scanning, data decoding, and
    user-interface design</strong>. The application provides a compact
    implementation of QR-based information creation and retrieval within
    a standalone Android application.
  </p>


  <h2 class="project-section-title">
    GitHub Repository
  </h2>

  <p>
    The complete source code of the QR Code Scanner application is
    available in the GitHub repository.
  </p>


  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Remote-Control-Fire-Detection-Car"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>
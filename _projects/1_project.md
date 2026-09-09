---
layout: page
title: Training Program Management System
description: A web-based Training Program Management System for managing courses, trainees, enrollment, payments, communication, and training activities.
img: assets/img/training-program.jpg
importance: 4
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
      <i class="fas fa-chalkboard-teacher"></i>
    </div>

    <div>
      <h1 class="project-title">
        Training Program Management System
      </h1>

      <p class="project-subtitle">
        A web-based platform for managing training programs, courses,
        trainees, enrollment, payments, and communication.
      </p>
    </div>

  </div>

  <div class="project-description">

    Developed a <strong>Training Program Management System (TPMS)</strong>
    designed to streamline the administration, organization, and delivery
    of training programs. The system provides a centralized platform for
    managing courses, trainees, enrollment, payments, communication, and
    training-related activities.

    The application was developed using <strong>PHP</strong> with
    <strong>MySQL</strong> for database management. The user interface
    incorporates <strong>HTML, CSS, JavaScript, and Bootstrap</strong>,
    while GitHub was used for source-code management and collaboration.

  </div>

  <div class="project-tags">
    <span class="project-tag">PHP</span>
    <span class="project-tag">MySQL</span>
    <span class="project-tag">HTML</span>
    <span class="project-tag">CSS</span>
    <span class="project-tag">JavaScript</span>
    <span class="project-tag">Bootstrap</span>
    <span class="project-tag">Web Application</span>
    <span class="project-tag">Training Management</span>
    <span class="project-tag">Live Chat</span>
    <span class="project-tag">Online Payment</span>
  </div>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Training-Program-Management-System"
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
    The <strong>Training Program Management System (TPMS)</strong> is a
    web-based platform developed to support the administration,
    documentation, tracking, and management of training programs.
    The system provides a centralized environment where administrators,
    instructors, and trainees can perform their respective activities.
  </p>

  <p>
    The system allows administrators or instructors to create and maintain
    course categories, add and manage courses, monitor trainee enrollment,
    communicate with trainees, and configure payment and language settings.
    Trainees can create accounts, manage their profiles, search for courses,
    add courses to a cart, purchase courses, review courses, view enrolled
    courses, and communicate through the live chat facility.
  </p>

  <div class="row justify-content-sm-center">

    <div class="col-sm-8 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-1.jpg"
        title="Training Program Management System Dashboard"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

    <div class="col-sm-4 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-2.jpg"
        title="Training Program Management System Course Management"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

  </div>

  <div class="caption">
    The Training Program Management System provides centralized management
    of training programs, courses, trainees, enrollment, and related
    activities.
  </div>

  <h2 class="project-section-title">
    System Features
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-shield"></i>
            Admin &amp; Instructor Management
          </h4>

          <ul>
            <li>Provides a dedicated admin/instructor dashboard.</li>
            <li>Creates and manages course categories.</li>
            <li>Adds, updates, and deletes courses.</li>
            <li>Manages trainee enrollment.</li>
            <li>Controls payment and language settings.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-graduate"></i>
            Trainee Management
          </h4>

          <ul>
            <li>Provides trainee registration and login.</li>
            <li>Allows users to view and update their profiles.</li>
            <li>Allows trainees to search for courses.</li>
            <li>Supports course enrollment and purchasing.</li>
            <li>Displays enrolled courses.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comments"></i>
            Live Chat
          </h4>

          <ul>
            <li>Provides direct communication between trainees and instructors.</li>
            <li>Helps trainees ask questions about courses.</li>
            <li>Supports communication about enrollment and payment.</li>
            <li>Improves interaction between trainees and instructors.</li>
          </ul>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-credit-card"></i>
            Online Payment
          </h4>

          <ul>
            <li>Supports online course purchasing.</li>
            <li>Provides payment configuration for administrators.</li>
            <li>Supports different currency options.</li>
            <li>Allows trainees to confirm course payments.</li>
          </ul>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    System Components
  </h2>

  <div class="row">

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Admin Dashboard</h4>

          <p class="card-text">
            Provides administrative control over courses, categories,
            trainees, enrollment, payments, and language settings.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Course Management</h4>

          <p class="card-text">
            Allows administrators or instructors to add, update, delete,
            categorize, and maintain training courses.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Trainee Management</h4>

          <p class="card-text">
            Maintains registered trainees and provides access to their
            enrollment and course-related information.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Enrollment Management</h4>

          <p class="card-text">
            Tracks course enrollment history and provides information
            about overall and pending enrollment.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">Payment Management</h4>

          <p class="card-text">
            Provides payment-related configuration and supports course
            purchasing by trainees.
          </p>

        </div>
      </div>
    </div>

    <div class="col-sm-6 col-md-4 mt-3">
      <div class="card h-100">
        <div class="card-body">

          <h4 class="card-title">User Profile</h4>

          <p class="card-text">
            Provides trainees with a profile containing their account
            information and allows profile information to be updated.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    User Workflow
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-user-plus"></i>
            1. Registration
          </h4>

          <p class="card-text">
            New instructors and trainees first create an account by
            providing the required information.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-sign-in-alt"></i>
            2. Login
          </h4>

          <p class="card-text">
            Users log into the system using their registered username
            and password. The system provides separate administrative
            and user-oriented functionality.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            3. Course Search
          </h4>

          <p class="card-text">
            Trainees can browse and search available courses using
            course categories to find their desired training program.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-shopping-cart"></i>
            4. Course Purchase
          </h4>

          <p class="card-text">
            Trainees can add courses to their cart, purchase their
            selected courses, and access the courses after enrollment.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comments"></i>
            5. Communication
          </h4>

          <p class="card-text">
            Trainees can communicate directly with instructors through
            the live chat facility when they need assistance.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-book-open"></i>
            6. Course Access
          </h4>

          <p class="card-text">
            After purchasing and enrolling in a course, trainees can
            view their enrolled courses and access the available
            course materials.
          </p>

        </div>
      </div>
    </div>

  </div>

  <div class="row justify-content-sm-center">

    <div class="col-sm-10 mt-3 mt-md-0">
      {% include figure.liquid
        loading="eager"
        path="assets/img/training-management-3.jpg"
        title="Training Program Management System User Interface"
        class="img-fluid rounded z-depth-1"
      %}
    </div>

  </div>

  <div class="caption">
    The system supports course discovery, enrollment, purchasing,
    course access, profile management, and communication between
    trainees and instructors.
  </div>

  <h2 class="project-section-title">
    Technology Stack
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Technology / Tool</th>
          <th>Purpose</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>PHP</td>
          <td>Server-side application development</td>
        </tr>

        <tr>
          <td>MySQL</td>
          <td>Database management and data storage</td>
        </tr>

        <tr>
          <td>HTML</td>
          <td>Web page structure and content</td>
        </tr>

        <tr>
          <td>CSS</td>
          <td>User interface styling</td>
        </tr>

        <tr>
          <td>JavaScript</td>
          <td>Client-side web functionality</td>
        </tr>

        <tr>
          <td>Bootstrap</td>
          <td>Responsive user interface development</td>
        </tr>

        <tr>
          <td>MySQL Workbench</td>
          <td>Database design and management</td>
        </tr>

        <tr>
          <td>Visual Studio Code</td>
          <td>Development environment</td>
        </tr>

        <tr>
          <td>GitHub</td>
          <td>Version control and code collaboration</td>
        </tr>

      </tbody>

    </table>

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
          <td>Project Type</td>
          <td>Web-Based Training Management System</td>
        </tr>

        <tr>
          <td>Backend</td>
          <td>PHP</td>
        </tr>

        <tr>
          <td>Database</td>
          <td>MySQL</td>
        </tr>

        <tr>
          <td>Frontend</td>
          <td>HTML, CSS, JavaScript, Bootstrap</td>
        </tr>

        <tr>
          <td>User Roles</td>
          <td>Administrator / Instructor and Trainee</td>
        </tr>

        <tr>
          <td>Course Management</td>
          <td>Course creation, updating, deletion, and categorization</td>
        </tr>

        <tr>
          <td>Enrollment</td>
          <td>Course enrollment and enrollment history</td>
        </tr>

        <tr>
          <td>Payment</td>
          <td>Online course payment and payment configuration</td>
        </tr>

        <tr>
          <td>Communication</td>
          <td>Live chat between trainees and instructors</td>
        </tr>

        <tr>
          <td>Primary Objective</td>
          <td>Centralized management of training programs</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Key Contributions
  </h2>

  <ul>

    <li>
      <strong>Centralized Management:</strong>
      Provides a centralized platform for managing training-related
      activities.
    </li>

    <li>
      <strong>Course Management:</strong>
      Supports course categories, course creation, maintenance, and
      course-related information.
    </li>

    <li>
      <strong>Online Enrollment:</strong>
      Allows trainees to search for desired courses and enroll in them.
    </li>

    <li>
      <strong>Online Payment:</strong>
      Provides an online purchasing and payment mechanism for courses.
    </li>

    <li>
      <strong>Live Communication:</strong>
      Includes a live chat facility that allows trainees to communicate
      directly with instructors.
    </li>

    <li>
      <strong>User Management:</strong>
      Provides registration, login, profile management, and
      enrolled-course functionality.
    </li>

  </ul>

  <h2 class="project-section-title">
    Future Improvements
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-clipboard-check"></i>
            Assessment System
          </h4>

          <p class="card-text">
            Introduce an assessment system to evaluate trainee knowledge,
            performance, and progress during training programs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-mobile-alt"></i>
            Mobile Accessibility
          </h4>

          <p class="card-text">
            Extend the platform with improved mobile accessibility so
            trainees can access training services conveniently from
            mobile devices.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-gamepad"></i>
            Gamification
          </h4>

          <p class="card-text">
            Introduce gamification techniques to make training activities
            more engaging and interactive for trainees.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-tachometer-alt"></i>
            Response Optimization
          </h4>

          <p class="card-text">
            Improve system performance and minimize response time for a
            faster and more efficient user experience.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    Project Highlights
  </h2>

  <p>
    This project demonstrates practical experience in
    <strong>full-stack web development, PHP application development,
    MySQL database management, responsive interface design, course
    management, user management, online enrollment, payment management,
    and live communication</strong>.
  </p>

  <p>
    The system provides an integrated platform for managing online
    training programs and course purchases while allowing administrators
    or instructors to maintain course information and trainees to
    search, purchase, and access their enrolled courses.
  </p>

  <h2 class="project-section-title">
    Project Report
  </h2>

  <p>
    The project was developed as a semester project at the
    <strong>Institute of Information Technology, Jahangirnagar University</strong>.
    The project report identifies the development technologies as PHP,
    MySQL, HTML, CSS, JavaScript, and Bootstrap.
  </p>

  <p>
    The project team consisted of
    <strong>Mst. Sumiya Siddika, Md. Shakil Ahmed, Shariful Islam,
    and Amit Azim Amit</strong>, under the supervision of
    <strong>Professor Dr. M. Shamim Kaiser</strong>.
  </p>

  <h2 class="project-section-title">
    GitHub Repository
  </h2>

  <p>
    The complete source code of the project is available in the GitHub
    repository.
  </p>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/Training-Program-Management-System"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>
---
layout: course
title: Software Engineering Laboratory
description: This laboratory course provides hands-on experience in applying software engineering methods, tools, and techniques to practical software projects. Students will apply software process models, Agile methodologies, requirements engineering, UML modeling, architectural design, software testing, configuration management, project management, software metrics, and estimation techniques to real-world software projects.
instructor: Md. Shakil Ahmed
year: 2026
term: Spring
importance: 4
course_id: cse-328-software-engineering-laboratory
---

<style>

/* =========================================================
   COURSE DETAIL PAGE
   WHITE / BLACK ACADEMIC STYLE
   SAME TYPOGRAPHY AS PROJECT PAGES
   ========================================================= */

.course-card,
.course-content {

  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  color: #111111;

}


/* =========================================================
   MAIN COURSE HEADER CARD
   ========================================================= */

.course-card {

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

.course-card:hover {

  border-color: #999999;

  box-shadow:
    0 10px 26px rgba(0, 0, 0, 0.12);

}


/* =========================================================
   COURSE HEADER
   ========================================================= */

.course-header {

  display: flex;

  align-items: center;

  gap: 16px;

  margin-bottom: 18px;

}

.course-icon {

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

.course-title {

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

.course-subtitle {

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
   COURSE DESCRIPTION
   ========================================================= */

.course-description {

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

.course-description strong {

  color: #000000;

  font-weight: 700;

}


/* =========================================================
   COURSE TAGS
   ========================================================= */

.course-tags {

  display: flex;

  flex-wrap: wrap;

  gap: 8px;

  margin-top: 20px;

}

.course-tag {

  display: inline-block;

  padding: 5px 10px;

  background: #f4f4f4;

  border: 1px solid #cccccc;

  border-radius: 4px;

  color: #222222;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 12px;

  font-weight: 600;

  line-height: 1.4;

}


/* =========================================================
   COURSE CONTENT
   ========================================================= */

.course-content {

  max-width: 1000px;

  margin: 0 auto;

  color: #111111;

}

.course-content p {

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

.course-content strong {

  color: #000000;

  font-weight: 700;

}


/* =========================================================
   SECTION HEADINGS
   ========================================================= */

.course-section-title {

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

.course-content .card,
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

.course-content .card:hover,
.feature-card:hover {

  transform: translateY(-3px);

  border-color: #999999;

  box-shadow:
    0 9px 22px rgba(0, 0, 0, 0.11);

}

.course-content .card-body {

  padding: 22px;

}


/* =========================================================
   CARD TITLES
   ========================================================= */

.course-content .card-title {

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

.course-content .card-title i {

  margin-right: 7px;

  color: #000000;

}


/* =========================================================
   CARD TEXT
   ========================================================= */

.course-content .card-text {

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

.course-content ul {

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

.course-content li {

  margin-bottom: 6px;

}

.course-content li strong {

  color: #000000;

}


/* =========================================================
   TABLES
   ========================================================= */

.course-content .table {

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

.course-content .table th {

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

.course-content .table td {

  padding: 10px 14px;

  background: #ffffff;

  color: #222222;

  border: 1px solid #d2d2d2;

  vertical-align: top;

}

.course-content .table tbody tr:hover td {

  background: #f8f8f8;

}


/* =========================================================
   GENERAL LINKS
   ========================================================= */

.course-content a {

  color: #000000 !important;

  text-decoration: underline;

  text-decoration-thickness: 1px;

  text-underline-offset: 3px;

}

.course-content a:hover {

  color: #000000 !important;

  opacity: 0.6;

}


/* =========================================================
   RESPONSIVE — TABLET
   ========================================================= */

@media (max-width: 900px) {

  .course-card {

    margin-left: 20px;

    margin-right: 20px;

    padding: 25px;

  }

  .course-content {

    padding-left: 20px;

    padding-right: 20px;

  }

  .course-title {

    font-size: 24px;

  }

  .course-content p {

    font-size: 16px;

  }

  .course-section-title {

    font-size: 25px;

  }

}


/* =========================================================
   RESPONSIVE — MOBILE
   ========================================================= */

@media (max-width: 768px) {

  .course-card {

    margin: 15px 15px 30px;

    padding: 21px;

    border-radius: 7px;

  }

  .course-header {

    gap: 12px;

  }

  .course-icon {

    width: 52px;

    height: 52px;

    font-size: 25px;

  }

  .course-title {

    font-size: 21px;

  }

  .course-subtitle {

    font-size: 14px;

  }

  .course-description {

    font-size: 15px;

    line-height: 1.75;

    text-align: left;

  }

  .course-content {

    padding-left: 15px;

    padding-right: 15px;

  }

  .course-content p {

    font-size: 15.5px;

    line-height: 1.75;

    text-align: left;

  }

  .course-section-title {

    margin-top: 30px;

    font-size: 23px;

  }

  .course-content .card-title {

    font-size: 18px;

  }

  .course-content .card-text {

    font-size: 15px;

    text-align: left;

  }

  .course-content ul {

    font-size: 15px;

  }

  .course-content .table {

    font-size: 14px;

  }

  .course-content .table th,
  .course-content .table td {

    padding: 9px 10px;

  }

}


/* =========================================================
   RESPONSIVE — SMALL MOBILE
   ========================================================= */

@media (max-width: 576px) {

  .course-card {

    margin-left: 10px;

    margin-right: 10px;

    padding: 18px;

  }

  .course-header {

    align-items: flex-start;

  }

  .course-icon {

    width: 46px;

    height: 46px;

    font-size: 22px;

  }

  .course-title {

    font-size: 19px;

  }

  .course-subtitle {

    font-size: 13.5px;

  }

  .course-description {

    font-size: 14px;

  }

  .course-tags {

    gap: 6px;

  }

  .course-tag {

    font-size: 11px;

    padding: 5px 8px;

  }

  .course-content {

    padding-left: 10px;

    padding-right: 10px;

  }

  .course-section-title {

    font-size: 21px;

  }

  .course-content .table {

    font-size: 13px;

  }

}

</style>

<div class="course-card">

  <div class="course-header">

    <div class="course-icon">
      <i class="fas fa-laptop-code"></i>
    </div>

    <div>

      <h1 class="course-title">
        Software Engineering Laboratory
      </h1>

      <p class="course-subtitle">
        CSE 328 · Laboratory Course · 1.5 Credit Hours
      </p>

    </div>

  </div>

  <div class="course-description">

    This laboratory course provides hands-on experience in applying
    <strong>software engineering methods, tools, and techniques</strong>
    to practical software projects. Students will apply software process
    models, Agile methodologies, requirements engineering, UML modeling,
    architectural design, software testing, configuration management,
    project management, software metrics, and estimation techniques.

  </div>

  <div class="course-tags">

    <span class="course-tag">Software Engineering</span>
    <span class="course-tag">Agile</span>
    <span class="course-tag">Requirements Engineering</span>
    <span class="course-tag">UML</span>
    <span class="course-tag">Software Architecture</span>
    <span class="course-tag">Design Patterns</span>
    <span class="course-tag">Software Testing</span>
    <span class="course-tag">Git &amp; GitHub</span>
    <span class="course-tag">Project Management</span>
    <span class="course-tag">Software Metrics</span>

  </div>

</div>


<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>
    This laboratory course provides hands-on experience in applying
    software engineering principles and techniques to practical software
    projects. Students will work with commonly used software engineering
    tools and development practices to understand how software systems
    are analyzed, designed, implemented, tested, managed, and evaluated.
  </p>

  <p>
    The course combines practical laboratory exercises with project-based
    activities. Students will develop software artifacts, create UML
    models, practice Agile development, use version control systems,
    implement software testing strategies, and apply project management
    and software quality techniques.
  </p>


  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-project-diagram"></i>

            CLO1 — Software Development Processes

          </h4>

          <p class="card-text">

            Apply software development process models and Agile
            methodologies to practical software projects.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-file-alt"></i>

            CLO2 — Requirements Engineering

          </h4>

          <p class="card-text">

            Analyze, document, and validate software requirements using
            appropriate requirements engineering techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-sitemap"></i>

            CLO3 — UML Modeling and Design

          </h4>

          <p class="card-text">

            Develop UML models and apply software architecture and design
            patterns to represent and structure software systems.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-code"></i>

            CLO4 — Software Implementation

          </h4>

          <p class="card-text">

            Implement maintainable software systems using systematic
            development practices, version control, and code quality
            principles.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-vial"></i>

            CLO5 — Software Testing and Quality

          </h4>

          <p class="card-text">

            Design and execute software testing activities and apply
            software quality assurance practices to identify and improve
            software defects and quality issues.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-tasks"></i>

            CLO6 — Software Project Management

          </h4>

          <p class="card-text">

            Apply configuration management, project planning, software
            metrics, estimation, scheduling, and project monitoring
            techniques.

          </p>

        </div>

      </div>

    </div>

  </div>


  <h2 class="course-section-title">
    Prerequisites
  </h2>

  <ul>

    <li>
      CSE 327: Software Engineering.
    </li>

    <li>
      Basic programming knowledge.
    </li>

    <li>
      Basic understanding of software development processes.
    </li>

    <li>
      Familiarity with object-oriented programming concepts.
    </li>

  </ul>


  <h2 class="course-section-title">
    Textbooks
  </h2>

  <ul>

    <li>

      <strong>Primary:</strong>
      <em>Software Engineering</em>
      by Ian Sommerville, 9th Edition.

    </li>

    <li>

      <strong>Reference:</strong>
      <em>Software Engineering: A Practitioner's Approach</em>
      by Roger S. Pressman.

    </li>

  </ul>


  <h2 class="course-section-title">
    Reference Books
  </h2>

  <ul>

    <li>
      <em>Fundamentals of Software Engineering</em>
      by R. Mall.
    </li>

    <li>
      <em>An Integrated Approach to Software Engineering</em>
      by P. Jalote.
    </li>

  </ul>


  <h2 class="course-section-title">
    Tools and Platforms
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-code"></i>

            Development and Version Control

          </h4>

          <p class="card-text">

            Visual Studio Code, Git, GitHub, and related development and
            version control tools for collaborative software development.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-vial"></i>

            Modeling and Testing Tools

          </h4>

          <p class="card-text">

            UML modeling tools, project management platforms, software
            testing tools, and related tools for software design, testing,
            and project management activities.

          </p>

        </div>

      </div>

    </div>

  </div>


  <h2 class="course-section-title">
    Online Resources
  </h2>

  <ul>

    <li>

      <a
        href="https://www.atlassian.com/agile"
        target="_blank"
        rel="noopener noreferrer"
      >
        Atlassian Agile Resources
      </a>

    </li>

    <li>

      <a
        href="https://git-scm.com/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Git
      </a>

    </li>

    <li>

      <a
        href="https://github.com/"
        target="_blank"
        rel="noopener noreferrer"
      >
        GitHub
      </a>

    </li>

    <li>

      <a
        href="https://www.uml.org/"
        target="_blank"
        rel="noopener noreferrer"
      >
        UML Resources
      </a>

    </li>

  </ul>


  <h2 class="course-section-title">
    Course Information
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

          <td>
            Course Code
          </td>

          <td>
            CSE 328
          </td>

        </tr>

        <tr>

          <td>
            Course Title
          </td>

          <td>
            Software Engineering Laboratory
          </td>

        </tr>

        <tr>

          <td>
            Course Type
          </td>

          <td>
            Laboratory Course
          </td>

        </tr>

        <tr>

          <td>
            Credit Hours
          </td>

          <td>
            1.5
          </td>

        </tr>

        <tr>

          <td>
            Academic Term
          </td>

          <td>
            Spring 2026
          </td>

        </tr>

        <tr>

          <td>
            Instructor
          </td>

          <td>
            Md. Shakil Ahmed
          </td>

        </tr>

      </tbody>

    </table>

  </div>


  <h2 class="course-section-title">
    Grading
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>

        <tr>

          <th>Assessment</th>
          <th>Weight</th>

        </tr>

      </thead>

      <tbody>

        <tr>

          <td>
            Class Participation and Lab Activity
          </td>

          <td>
            5%
          </td>

        </tr>

        <tr>

          <td>
            Lab Assignments / Reports and Presentation
          </td>

          <td>
            10%
          </td>

        </tr>

        <tr>

          <td>
            Class Test / Lab Performance
          </td>

          <td>
            15%
          </td>

        </tr>

        <tr>

          <td>
            Midterm Examination / Project Evaluation
          </td>

          <td>
            30%
          </td>

        </tr>

        <tr>

          <td>
            Final Examination / Project Evaluation
          </td>

          <td>
            40%
          </td>

        </tr>

        <tr>

          <td>
            <strong>Total</strong>
          </td>

          <td>
            <strong>100%</strong>
          </td>

        </tr>

      </tbody>

    </table>

  </div>


  <h2 class="course-section-title">
    Course Schedule
  </h2>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>

        <tr>

          <th>Week</th>
          <th>Topic</th>
          <th>Description</th>

        </tr>

      </thead>

      <tbody>

        <tr>

          <td>1</td>

          <td>
            Introduction to Software Engineering Tools
          </td>

          <td>
            Introduction to software engineering laboratory tools,
            development environments, version control systems, project
            repositories, and collaborative software development platforms.
          </td>

        </tr>

        <tr>

          <td>2</td>

          <td>
            Software Process Models
          </td>

          <td>
            Practical exploration of software development process models
            including Waterfall, Incremental, Iterative, and Spiral models
            and their application to software projects.
          </td>

        </tr>

        <tr>

          <td>3</td>

          <td>
            Agile Software Development
          </td>

          <td>
            Hands-on activities involving Agile principles, Scrum framework,
            user stories, sprint planning, sprint execution, and Agile
            project management practices.
          </td>

        </tr>

        <tr>

          <td>4</td>

          <td>
            Requirements Engineering
          </td>

          <td>
            Practical requirements elicitation, analysis, specification,
            documentation, and validation using appropriate requirements
            engineering techniques.
          </td>

        </tr>

        <tr>

          <td>5</td>

          <td>
            Use Case and Activity Diagrams
          </td>

          <td>
            Development of UML Use Case and Activity Diagrams to model
            system functionality, actors, workflows, and business processes.
          </td>

        </tr>

        <tr>

          <td>6</td>

          <td>
            Class and Object Modeling
          </td>

          <td>
            Development of UML Class and Object Diagrams to represent system
            structure, classes, attributes, methods, objects, and
            relationships.
          </td>

        </tr>

        <tr>

          <td>7</td>

          <td>
            Behavioral Modeling
          </td>

          <td>
            Creation of UML Sequence and State Diagrams to model system
            interactions, object behavior, events, and state transitions.
          </td>

        </tr>

        <tr>

          <td>8</td>

          <td>
            Software Architecture and Design
          </td>

          <td>
            Practical application of software architecture principles,
            architectural styles, modular design, component identification,
            and system-level design.
          </td>

        </tr>

        <tr>

          <td>9</td>

          <td>
            Software Design Patterns
          </td>

          <td>
            Implementation and application of common software design
            patterns such as Singleton, Factory, Observer, and Strategy
            patterns to improve software structure and maintainability.
          </td>

        </tr>

        <tr>

          <td>10</td>

          <td>
            Software Implementation and Version Control
          </td>

          <td>
            Practical software implementation using coding standards,
            Git-based version control, branching, merging, commit
            management, and collaborative development practices.
          </td>

        </tr>

        <tr>

          <td>11</td>

          <td>
            Software Testing
          </td>

          <td>
            Practical implementation of unit testing, integration testing,
            system testing, test case development, test execution, and
            defect identification.
          </td>

        </tr>

        <tr>

          <td>12</td>

          <td>
            Software Quality Assurance and Metrics
          </td>

          <td>
            Application of software quality assurance practices, software
            metrics, code quality measures, defect tracking, and quality
            evaluation techniques.
          </td>

        </tr>

        <tr>

          <td>13</td>

          <td>
            Configuration Management and Project Management
          </td>

          <td>
            Practical configuration management, project planning, task
            allocation, scheduling, progress tracking, risk management,
            and project monitoring.
          </td>

        </tr>

        <tr>

          <td>14</td>

          <td>
            Software Estimation and Project Planning
          </td>

          <td>
            Application of software estimation techniques, effort and cost
            estimation, scheduling, resource planning, and project
            documentation.
          </td>

        </tr>

        <tr>

          <td>15</td>

          <td>
            Software Project Development
          </td>

          <td>
            Development and integration of the laboratory project using
            requirements, UML models, software architecture, implementation,
            version control, and testing practices.
          </td>

        </tr>

        <tr>

          <td>16</td>

          <td>
            Project Evaluation and Problem Solving
          </td>

          <td>
            Project demonstration, software evaluation, problem-solving
            activities, debugging, documentation review, and preparation
            for final project assessment.
          </td>

        </tr>

        <tr>

          <td>17</td>

          <td>
            Final Project Evaluation and Review
          </td>

          <td>
            Final project presentation and evaluation, comprehensive review
            of software engineering laboratory activities, questions and
            answers, and final assessment preparation.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
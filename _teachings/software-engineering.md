---
layout: course
title: Software Engineering
description: This course introduces the fundamental concepts, methods, tools, and procedures of software engineering. Students will learn software processes, life-cycle models, requirements engineering, software analysis and design, implementation, testing, quality assurance, design patterns, and software project management.
instructor: Md. Shakil Ahmed
year: 2026
term: Spring
importance: 3
course_id: cse-327-software-engineering

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
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  font-size: 15px;

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
      <i class="fas fa-code"></i>
    </div>

    <div>

      <h1 class="course-title">
        Software Engineering
      </h1>

      <p class="course-subtitle">
        CSE 327 · Core Course · 3.0 Credit Hours
      </p>

    </div>

  </div>

  <div class="course-description">

    This course introduces the fundamental concepts, methods, tools, and
    procedures of <strong>software engineering</strong>. Students will learn
    software processes, life-cycle models, requirements engineering,
    software analysis and design, implementation, testing, quality
    assurance, design patterns, and software project management.

  </div>

  <div class="course-tags">

    <span class="course-tag">Software Engineering</span>
    <span class="course-tag">Software Processes</span>
    <span class="course-tag">Agile Development</span>
    <span class="course-tag">Requirements Engineering</span>
    <span class="course-tag">UML</span>
    <span class="course-tag">Software Architecture</span>
    <span class="course-tag">Design Patterns</span>
    <span class="course-tag">Software Testing</span>
    <span class="course-tag">Quality Assurance</span>
    <span class="course-tag">Project Management</span>

  </div>

</div>


<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>
    This course provides a comprehensive introduction to software
    engineering principles, processes, methods, tools, and practices used
    in the development and maintenance of software systems.
  </p>

  <p>
    Students will study software life-cycle models, Agile development,
    requirements engineering, analysis and modeling, architectural design,
    design patterns, implementation, software testing, quality assurance,
    maintenance, configuration management, project management, software
    metrics, and estimation techniques.
  </p>


  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-cogs"></i>

            CLO1 — Software Engineering Fundamentals

          </h4>

          <p class="card-text">

            Explain fundamental software engineering concepts, software
            processes, life-cycle models, software architecture, quality,
            and project management principles.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-project-diagram"></i>

            CLO2 — Software Process and Analysis

          </h4>

          <p class="card-text">

            Analyze software engineering problems using appropriate
            software processes, methodologies, tools, and analytical
            techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-file-alt"></i>

            CLO3 — Requirements Engineering

          </h4>

          <p class="card-text">

            Apply requirements elicitation, analysis, specification,
            validation, and management techniques to software development
            problems.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-sitemap"></i>

            CLO4 — Software Design

          </h4>

          <p class="card-text">

            Design software systems using UML models, architectural
            principles, modular design, abstraction, and appropriate
            software design patterns.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-code"></i>

            CLO5 — Software Implementation

          </h4>

          <p class="card-text">

            Apply software implementation, reuse, refactoring, and
            maintainable development practices to construct software
            solutions.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-vial"></i>

            CLO6 — Testing and Quality Assurance

          </h4>

          <p class="card-text">

            Apply software testing, verification, validation, quality
            assurance, software standards, and quality management
            techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-tasks"></i>

            CLO7 — Software Project Management

          </h4>

          <p class="card-text">

            Apply software configuration management, project planning,
            scheduling, risk management, software metrics, and estimation
            techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-tools"></i>

            CLO8 — Software Engineering Practice

          </h4>

          <p class="card-text">

            Apply software engineering principles, methodologies, tools,
            and techniques to develop effective software solutions for
            real-world problems.

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
      CSE 317.
    </li>

    <li>
      Basic programming and problem-solving knowledge.
    </li>

    <li>
      Familiarity with fundamental computer science concepts.
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

      <strong>Primary:</strong>
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

            Development and Modeling

          </h4>

          <p class="card-text">

            UML modeling tools, software development environments,
            documentation tools, and related platforms for software
            analysis, modeling, and design.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-tasks"></i>

            Project and Quality Management

          </h4>

          <p class="card-text">

            Git, GitHub, project management tools, software testing tools,
            issue tracking systems, and related platforms for software
            development and quality management.

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
        href="https://web.stanford.edu/class/archive/cs/cs295/cs295.1086/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Stanford University Software Engineering
      </a>

    </li>

    <li>

      <a
        href="https://ocw.mit.edu/courses/1-124j-foundations-of-software-engineering-fall-2000/pages/lecture-notes/"
        target="_blank"
        rel="noopener noreferrer"
      >
        MIT OpenCourseWare — Foundations of Software Engineering
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

          <td>Course Code</td>
          <td>CSE 327</td>

        </tr>

        <tr>

          <td>Course Title</td>
          <td>Software Engineering</td>

        </tr>

        <tr>

          <td>Course Type</td>
          <td>Core Course</td>

        </tr>

        <tr>

          <td>Credit Hours</td>
          <td>3.0</td>

        </tr>

        <tr>

          <td>Academic Term</td>
          <td>Spring 2026</td>

        </tr>

        <tr>

          <td>Instructor</td>
          <td>Md. Shakil Ahmed</td>

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

          <td>Class Participation and Activity</td>
          <td>5%</td>

        </tr>

        <tr>

          <td>Assignment / Report and Presentation</td>
          <td>10%</td>

        </tr>

        <tr>

          <td>Class Tests</td>
          <td>15%</td>

        </tr>

        <tr>

          <td>Midterm Examination</td>
          <td>30%</td>

        </tr>

        <tr>

          <td>Final Examination</td>
          <td>40%</td>

        </tr>

        <tr>

          <td><strong>Total</strong></td>
          <td><strong>100%</strong></td>

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
            Introduction to Software Engineering
          </td>

          <td>
            Introduction to software, software engineering, software
            products, essential software attributes, software engineering
            ethics, legacy software, software process layers, framework
            activities, and software myths.
          </td>

        </tr>

        <tr>

          <td>2</td>

          <td>
            Software Processes and Process Models
          </td>

          <td>
            Introduction to software processes, process descriptions,
            plan-driven and Agile processes, Waterfall, V-Model,
            Incremental, and reuse-oriented software development models.
          </td>

        </tr>

        <tr>

          <td>3</td>

          <td>
            Agile Software Development
          </td>

          <td>
            Software prototyping, Spiral model, Rational Unified Process,
            Agile principles, Agile modeling, Agile Unified Process,
            Extreme Programming, refactoring, and pair programming.
          </td>

        </tr>

        <tr>

          <td>4</td>

          <td>
            Requirements Engineering
          </td>

          <td>
            Introduction to requirements engineering, functional and
            non-functional requirements, requirements documentation,
            specification, elicitation, analysis, validation, and
            requirements management.
          </td>

        </tr>

        <tr>

          <td>5</td>

          <td>
            Scenario-Based and Class-Based Modeling
          </td>

          <td>
            Development of Use Case, Activity, and Swim Lane diagrams,
            along with Class Diagrams, CRC cards, and analysis packages.
          </td>

        </tr>

        <tr>

          <td>6</td>

          <td>
            Behavioral Modeling
          </td>

          <td>
            Introduction to behavioral models including State Diagrams and
            Sequence Diagrams for representing system behavior and
            interactions.
          </td>

        </tr>

        <tr>

          <td>7</td>

          <td>
            Architectural Design
          </td>

          <td>
            Introduction to software architectural design, architectural
            views, architectural patterns, and software architecture
            principles.
          </td>

        </tr>

        <tr>

          <td>8</td>

          <td>
            Software Design and Design Patterns
          </td>

          <td>
            Study of software design principles, modularity, abstraction,
            design strategies, and commonly used software design patterns.
          </td>

        </tr>

        <tr>

          <td>9</td>

          <td>
            Software Implementation and Reuse
          </td>

          <td>
            Software implementation practices, component reuse, software
            development environments, and implementation-related design
            considerations.
          </td>

        </tr>

        <tr>

          <td>10</td>

          <td>
            Software Testing
          </td>

          <td>
            Introduction to software testing principles, testing
            strategies, unit testing, integration testing, system testing,
            and test case development.
          </td>

        </tr>

        <tr>

          <td>11</td>

          <td>
            Software Quality Assurance
          </td>

          <td>
            Software quality concepts, quality assurance activities,
            verification and validation, software standards, and quality
            management.
          </td>

        </tr>

        <tr>

          <td>12</td>

          <td>
            Software Maintenance and Evolution
          </td>

          <td>
            Software evolution, maintenance processes, legacy systems,
            software change, and techniques for maintaining software
            systems.
          </td>

        </tr>

        <tr>

          <td>13</td>

          <td>
            Software Configuration and Project Management
          </td>

          <td>
            Introduction to software configuration management, version
            control, project organization, planning, scheduling, and
            management activities.
          </td>

        </tr>

        <tr>

          <td>14</td>

          <td>
            Software Risk and Project Planning
          </td>

          <td>
            Software project planning, risk management, resource
            allocation, project scheduling, and software project management
            techniques.
          </td>

        </tr>

        <tr>

          <td>15</td>

          <td>
            Software Metrics and Estimation
          </td>

          <td>
            Process and product metrics, project metrics, software
            measurement, software project estimation, resources, and
            estimation techniques.
          </td>

        </tr>

        <tr>

          <td>16</td>

          <td>
            Brainstorming and Project Development
          </td>

          <td>
            Brainstorming activities, software project development,
            problem-solving, project discussion, and preparation for the
            final examination.
          </td>

        </tr>

        <tr>

          <td>17</td>

          <td>
            Case Study and Final Review
          </td>

          <td>
            Comprehensive case studies, problem-solving activities, course
            review, questions and answers, and preparation for the semester
            final examination.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
--- 
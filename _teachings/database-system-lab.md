---
layout: course
title: Database Systems Lab
description: This laboratory course provides hands-on experience in designing, creating, modifying, and managing relational database systems. Students will develop practical skills in SQL, database design, data manipulation, constraints, joins, subqueries, indexes, views, triggers, and database application development through laboratory exercises and a group project.
instructor: Md. Shakil Ahmed
year: 2025
term: Spring
importance: 6
course_id: cse-208-database-systems-lab
---

<style>

/* =========================================================
   COURSE DETAIL PAGE
   WHITE / BLACK ACADEMIC STYLE
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
  box-shadow: 0 5px 16px rgba(0, 0, 0, 0.08);
  color: #111111;
  transition:
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.course-card:hover {
  border-color: #999999;
  box-shadow: 0 10px 26px rgba(0, 0, 0, 0.12);
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
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.06);
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}

.course-content .card:hover,
.feature-card:hover {
  transform: translateY(-3px);
  border-color: #999999;
  box-shadow: 0 9px 22px rgba(0, 0, 0, 0.11);
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
      <i class="fas fa-database"></i>
    </div>

    <div>

      <h1 class="course-title">
        Database Systems Lab
      </h1>

      <p class="course-subtitle">
        CSE 208 · Database Laboratory Course · 1.0 Credit Hour
      </p>

    </div>

  </div>

  <div class="course-description">

    This laboratory course provides hands-on experience in
    <strong>designing, creating, modifying, and managing relational database systems</strong>.
    Students will develop practical skills in SQL, database design,
    data manipulation, constraints, joins, subqueries, indexes, views,
    triggers, and database application development through laboratory
    exercises and a group project.

  </div>

  <div class="course-tags">

    <span class="course-tag">Database Systems</span>
    <span class="course-tag">SQL</span>
    <span class="course-tag">Relational Databases</span>
    <span class="course-tag">Database Design</span>
    <span class="course-tag">ER Diagrams</span>
    <span class="course-tag">Data Manipulation</span>
    <span class="course-tag">Joins</span>
    <span class="course-tag">Subqueries</span>
    <span class="course-tag">Indexes</span>
    <span class="course-tag">Views</span>
    <span class="course-tag">Triggers</span>
    <span class="course-tag">Database Applications</span>

  </div>

</div>


<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>

    This laboratory course provides students with practical experience in
    designing, creating, modifying, and managing relational database systems.
    The course is based on <strong>CSE 207: Database Management Systems</strong>
    and focuses on the practical implementation of database concepts using
    SQL and relational database management systems.

  </p>

  <p>
    By the end of this course, students will be able to:
  </p>

  <ul>

    <li>
      Demonstrate the use of a relational database management system to
      create, secure, populate, and maintain databases.
    </li>

    <li>
      Apply SQL commands to create and modify database structures.
    </li>

    <li>
      Perform data manipulation operations, including insertion, deletion,
      and updating of records.
    </li>

    <li>
      Design and execute SQL queries using selection, projection,
      restrictions, joins, grouping, and subqueries.
    </li>

    <li>
      Implement database constraints, indexes, views, and triggers.
    </li>

    <li>
      Design relational databases and develop ER diagrams for real-world
      applications.
    </li>

    <li>
      Develop a database application using a relational database management
      system.
    </li>

    <li>
      Demonstrate teamwork, problem-solving, and project management skills
      through a database project.
    </li>

  </ul>


  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-database"></i>
            CLO1 — Database Fundamentals
          </h4>

          <p class="card-text">

            Demonstrate the use of a relational database management system
            to create, secure, populate, and maintain relational databases.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-code"></i>
            CLO2 — SQL Programming
          </h4>

          <p class="card-text">

            Apply SQL commands to create and modify database structures
            and perform data manipulation and retrieval operations.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            CLO3 — Query Development
          </h4>

          <p class="card-text">

            Design and execute SQL queries using selection, projection,
            restrictions, joins, grouping, aggregate functions, and
            subqueries.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-laptop-code"></i>
            CLO4 — Database Application Development
          </h4>

          <p class="card-text">

            Design relational databases, develop ER diagrams, implement
            database structures, and develop a database application for
            a real-world problem.

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
      <strong>CSE 207:</strong> Database Management Systems
    </li>

    <li>
      Basic computer literacy
    </li>

    <li>
      Basic understanding of database concepts and SQL
    </li>

  </ul>


  <h2 class="course-section-title">
    Textbooks
  </h2>

  <ul>

    <li>

      <strong>Primary:</strong>
      <em>Database System Concepts</em>
      by Abraham Silberschatz, Henry F. Korth, and S. Sudarshan.

    </li>

  </ul>


  <h2 class="course-section-title">
    Reference Books
  </h2>

  <ul>

    <li>

      <em>Database Design</em>
      by Adrienne Watt and Nelson Eng.

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
            <i class="fas fa-database"></i>
            Database Management Systems
          </h4>

          <p class="card-text">

            MySQL, Oracle Database, relational database management systems,
            and SQL development environments.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-project-diagram"></i>
            Database Design
          </h4>

          <p class="card-text">

            ER diagram development, relational schema design,
            database modeling, and database application development.

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
        href="https://dev.mysql.com/doc/"
        target="_blank"
        rel="noopener noreferrer"
      >
        MySQL Documentation
      </a>

    </li>

    <li>

      <a
        href="https://docs.oracle.com/en/database/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Oracle Database Documentation
      </a>

    </li>

  </ul>


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
            Introduction to Database Systems and SQL
          </td>

          <td>
            Introduction to relational database management systems,
            database creation, SQL environments, and the basic structure
            of relational databases.
          </td>

        </tr>

        <tr>

          <td>2</td>

          <td>
            Data Definition Language
          </td>

          <td>
            Practical implementation of CREATE, ALTER, and DROP statements
            to create and modify databases and tables.
          </td>

        </tr>

        <tr>

          <td>3</td>

          <td>
            Data Manipulation Language
          </td>

          <td>
            Practical implementation of INSERT, DELETE, and UPDATE statements
            to populate and modify database records.
          </td>

        </tr>

        <tr>

          <td>4</td>

          <td>
            Selection, Projection, and Restrictions
          </td>

          <td>
            Implementation of SELECT statements, selection and projection
            operations, filtering records, and applying restrictions using SQL.
          </td>

        </tr>

        <tr>

          <td>5</td>

          <td>
            Joins
          </td>

          <td>
            Practical implementation of inner joins, outer joins, and other
            join operations to retrieve data from multiple related tables.
          </td>

        </tr>

        <tr>

          <td>6</td>

          <td>
            Grouping and Aggregate Functions
          </td>

          <td>
            Implementation of GROUP BY, HAVING, and aggregate functions
            to summarize and analyze database records.
          </td>

        </tr>

        <tr>

          <td>7</td>

          <td>
            Midterm Review and Examination
          </td>

          <td>
            Review of SQL concepts and laboratory exercises covered during
            the first six weeks, followed by the midterm laboratory examination.
          </td>

        </tr>

        <tr>

          <td>8</td>

          <td>
            Project Proposal and Database Design
          </td>

          <td>
            Submission and finalization of project proposals, identification
            of entities and relationships, and introduction to database
            design and ER diagrams.
          </td>

        </tr>

        <tr>

          <td>9</td>

          <td>
            Subqueries
          </td>

          <td>
            Practical implementation of single-row and multiple-row subqueries,
            nested queries, and subqueries within SELECT, WHERE, and FROM clauses.
          </td>

        </tr>

        <tr>

          <td>10</td>

          <td>
            Indexes
          </td>

          <td>
            Introduction to database indexes, index creation, and practical
            implementation to improve query performance.
          </td>

        </tr>

        <tr>

          <td>11</td>

          <td>
            Database Design and ER Diagrams
          </td>

          <td>
            Supervision of database design, ER diagram development,
            relational schema design, and implementation of database
            structures for the project.
          </td>

        </tr>

        <tr>

          <td>12</td>

          <td>
            Views
          </td>

          <td>
            Practical implementation of views, creation of virtual tables,
            and execution of queries through views.
          </td>

        </tr>

        <tr>

          <td>13</td>

          <td>
            Triggers
          </td>

          <td>
            Introduction to database triggers and practical implementation
            for automated database operations and data integrity.
          </td>

        </tr>

        <tr>

          <td>14</td>

          <td>
            Final Project Development
          </td>

          <td>
            Development of the final database application, implementation
            of SQL operations through a user interface, and supervision
            of project progress.
          </td>

        </tr>

        <tr>

          <td>15</td>

          <td>
            Final Project Evaluation
          </td>

          <td>
            Evaluation of the final database project, demonstration
            of database functionality, and assessment of project implementation.
          </td>

        </tr>

        <tr>

          <td>16</td>

          <td>
            Brainstorming and Problem Solving
          </td>

          <td>
            Intensive discussion, brainstorming, and problem-solving
            activities to strengthen database design and SQL skills.
          </td>

        </tr>

        <tr>

          <td>17</td>

          <td>
            Final Project Evaluation and Review
          </td>

          <td>
            Final project evaluation, comprehensive review of database
            concepts, questions and answers, and preparation for final assessment.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
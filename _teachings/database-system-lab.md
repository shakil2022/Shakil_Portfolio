---

layout: course

title: Database Systems Lab

description: This laboratory course provides hands-on experience in designing, creating, modifying, and managing relational database systems. Students will develop practical skills in SQL, database design, data manipulation, constraints, joins, subqueries, indexes, views, triggers, and database application development through laboratory exercises and a group project.

instructor: Md. Shakil Ahmed

year: 2025

term: Spring

importance: 6

course_id: cse-208-database-systems-lab

schedule:

* week: 1
  date: Week 1
  topic: Introduction to Database Systems and SQL
  description: Introduction to relational database management systems, database creation, SQL environments, and the basic structure of relational databases.

* week: 2
  date: Week 2
  topic: Data Definition Language
  description: Practical implementation of CREATE, ALTER, and DROP statements to create and modify databases and tables.

* week: 3
  date: Week 3
  topic: Data Manipulation Language
  description: Practical implementation of INSERT, DELETE, and UPDATE statements to populate and modify database records.

* week: 4
  date: Week 4
  topic: Selection, Projection, and Restrictions
  description: Implementation of SELECT statements, selection and projection operations, filtering records, and applying restrictions using SQL.

* week: 5
  date: Week 5
  topic: Joins
  description: Practical implementation of inner joins, outer joins, and other join operations to retrieve data from multiple related tables.

* week: 6
  date: Week 6
  topic: Grouping and Aggregate Functions
  description: Implementation of GROUP BY, HAVING, and aggregate functions to summarize and analyze database records.

* week: 7
  date: Week 7
  topic: Midterm Review and Examination
  description: Review of SQL concepts and laboratory exercises covered during the first six weeks, followed by the midterm laboratory examination.

* week: 8
  date: Week 8
  topic: Project Proposal and Database Design
  description: Submission and finalization of project proposals, identification of entities and relationships, and introduction to database design and ER diagrams.

* week: 9
  date: Week 9
  topic: Subqueries
  description: Practical implementation of single-row and multiple-row subqueries, nested queries, and subqueries within SELECT, WHERE, and FROM clauses.

* week: 10
  date: Week 10
  topic: Indexes
  description: Introduction to database indexes, index creation, and practical implementation of indexes to improve query performance.

* week: 11
  date: Week 11
  topic: Database Design and ER Diagrams
  description: Supervision of database design, ER diagram development, relational schema design, and implementation of database structures for the project.

* week: 12
  date: Week 12
  topic: Views
  description: Practical implementation of views, creation of virtual tables, and execution of queries through views.

* week: 13
  date: Week 13
  topic: Triggers
  description: Introduction to database triggers and practical implementation of triggers for automated database operations and data integrity.

* week: 14
  date: Week 14
  topic: Final Project Development
  description: Development of the final database application, implementation of SQL operations through a user interface, and supervision of project progress.

* week: 15
  date: Week 15
  topic: Final Project Evaluation
  description: Evaluation of the final database project, demonstration of database functionality, and assessment of project implementation.

* week: 16
  date: Week 16
  topic: Brainstorming and Problem Solving
  description: Intensive discussion, brainstorming, and problem-solving activities to strengthen database design and SQL skills.

* week: 17
  date: Week 17
  topic: Final Project Evaluation and Review
  description: Final project evaluation, comprehensive review of database concepts, questions and answers, and preparation for the final assessment.

---

<style>
  /* =========================================================
     COURSE PAGE — WHITE / BLACK ACADEMIC STYLE
     Typography aligned with Teaching and Project pages
     ========================================================= */

  .course-page,
  .course-content,
  .course-overview {
    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    color: #111111;

    font-size: 17px;
    line-height: 1.8;
  }

  /* =========================================================
     COURSE HEADER
     ========================================================= */

  .course-page h1,
  .course-page h2,
  .course-page h3,
  .course-page h4,
  .course-content h1,
  .course-content h2,
  .course-content h3,
  .course-content h4 {
    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-weight: 700;
  }

  .course-page h1 {
    font-size: 32px;
  }

  .course-page h2 {
    font-size: 28px;
  }

  .course-page h3 {
    font-size: 22px;
  }

  /* =========================================================
     MAIN COURSE CONTENT
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
     LISTS
     ========================================================= */

  .course-content ul {
    margin-top: 8px;
    margin-bottom: 20px;

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
    margin-bottom: 7px;
  }

  .course-content li strong {
    color: #000000;
  }

  /* =========================================================
     LINKS
     ========================================================= */

  .course-content a {
    color: #000000 !important;

    text-decoration: underline;

    text-decoration-thickness: 1px;
    text-underline-offset: 3px;

    transition: opacity 0.2s ease;
  }

  .course-content a:hover {
    color: #000000 !important;

    opacity: 0.6;
  }

  /* =========================================================
     COURSE INFORMATION CARDS
     ========================================================= */

  .course-content .card {
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

  .course-content .card:hover {
    transform: translateY(-3px);

    border-color: #999999;

    box-shadow:
      0 9px 22px rgba(0, 0, 0, 0.11);
  }

  .course-content .card-body {
    padding: 22px;
  }

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
     DIVIDERS
     ========================================================= */

  .course-content hr {
    border: none;

    border-top: 2px solid #000000;

    margin: 30px auto;
  }

  /* =========================================================
     RESPONSIVE — TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .course-page,
    .course-content,
    .course-overview {
      font-size: 16px;
    }

    .course-content {
      padding-left: 20px;
      padding-right: 20px;
    }

    .course-content p {
      font-size: 16px;
    }

    .course-section-title {
      font-size: 25px;
    }

    .course-content .card-body {
      padding: 21px;
    }
  }

  /* =========================================================
     RESPONSIVE — MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .course-page,
    .course-content,
    .course-overview {
      font-size: 15.5px;

      line-height: 1.75;
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

      line-height: 1.75;
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

    .course-content {
      padding-left: 10px;
      padding-right: 10px;
    }

    .course-section-title {
      font-size: 21px;
    }

    .course-content p {
      font-size: 15px;
    }

    .course-content .card-body {
      padding: 18px;
    }

    .course-content .card-title {
      font-size: 17px;
    }

    .course-content .card-text {
      font-size: 14.5px;
    }

    .course-content ul {
      font-size: 14.5px;

      padding-left: 20px;
    }

    .course-content .table {
      font-size: 13px;
    }

    .course-content .table th,
    .course-content .table td {
      padding: 8px 9px;
    }
  }
</style>

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

```
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
```

  </ul>

  <h2 class="course-section-title">
    Prerequisites
  </h2>

  <ul>
    <li><strong>CSE 207:</strong> Database Management Systems</li>
    <li>Basic computer literacy</li>
    <li>Basic understanding of database concepts and SQL</li>
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

```
<li>
  <a
    href="https://docs.oracle.com/en/database/"
    target="_blank"
    rel="noopener noreferrer"
  >
    Oracle Database Documentation
  </a>
</li>
```

  </ul>

  <h2 class="course-section-title">
    Grading
  </h2>

  <div class="table-responsive">

```
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
      <td>Continuous Lab Evaluation &amp; Assignments</td>
      <td>25%</td>
    </tr>

    <tr>
      <td>Lab Midterm Examination</td>
      <td>30%</td>
    </tr>

    <tr>
      <td>Final Project Evaluation &amp; Report</td>
      <td>40%</td>
    </tr>

    <tr>
      <td><strong>Total</strong></td>
      <td><strong>100%</strong></td>
    </tr>

  </tbody>

</table>


  </div>

</div>

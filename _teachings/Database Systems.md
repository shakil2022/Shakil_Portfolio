
---
layout: course

title: Database Systems

description: This course introduces the fundamental concepts and practices of database systems, with emphasis on database design, relational models, SQL, relational algebra, normalization, indexing, hashing, transaction management, and concurrency control. Students will develop the ability to design, query, optimize, and manage relational databases efficiently.

instructor: Md. Shakil Ahmed

year: 2025

term: Fall

importance: 5

course_id: cse-207-database-systems

schedule:
  - week: 1
    date: Week 1
    topic: Introduction to Database Systems
    description: Overview of database systems, database applications, limitations of traditional file processing systems, levels of data abstraction, database instances, database languages, storage management, query processing, transaction management, history of database systems, database users, and database administrators.

  - week: 2
    date: Week 2
    topic: Relational Model
    description: Introduction to the relational model, relations, attributes and their types, relation schema and instances, keys, schema diagrams, and relational query languages.

  - week: 3
    date: Week 3
    topic: Introduction to SQL
    description: Introduction to Structured Query Language, SQL data definition, basic data types, schema definition, integrity constraints, basic SQL queries, queries on single and multiple relations, Cartesian products, natural joins, filtering, ordering, set operations, and aggregate functions.

  - week: 4
    date: Week 4
    topic: Database Modification and Nested Queries
    description: Practical application of INSERT, UPDATE, and DELETE operations, nested subqueries, and complex SQL query construction.

  - week: 5
    date: Week 5
    topic: Intermediate SQL
    description: Advanced SQL operations including inner joins, outer joins, views, materialized views, and view modification and update operations.

  - week: 6
    date: Week 6
    topic: Integrity Constraints and Relational Algebra
    description: Application of NOT NULL, UNIQUE, PRIMARY KEY, CHECK, and referential integrity constraints. Introduction to authorization, user-defined domains, and relational algebra operations.

  - week: 7
    date: Week 7
    topic: Relational Algebra
    description: Detailed study and problem solving using select, project, set operations, Cartesian product, rename, natural join, assignment, outer join, division, aggregate functions, and relational algebra-based queries.

  - week: 8
    date: Week 8
    topic: Entity-Relationship Model
    description: Introduction to entity sets, relationship sets, cardinality constraints, participation constraints, ER diagrams, degrees of relationships, and attribute types.

  - week: 9
    date: Week 9
    topic: Advanced ER Modeling and Database Design
    description: Mapping cardinalities, entity roles, weak entity sets, reduction of ER models to relational models, specialization, generalization, aggregation, and real-world database design.

  - week: 10
    date: Week 10
    topic: Relational Database Design
    description: Study of atomic attributes, decomposition, functional dependencies, closure sets, super keys, candidate keys, and primary keys. Students will analyze functional dependencies for relational database design.

  - week: 11
    date: Week 11
    topic: Functional Dependencies and Canonical Cover
    description: Determination of attribute closure, identification of keys, analysis of functional dependencies, and construction of canonical covers.

  - week: 12
    date: Week 12
    topic: Normalization and Database Design
    description: Practical application of First Normal Form, Second Normal Form, Third Normal Form, and Boyce-Codd Normal Form. Students will determine normal forms, normalize relational schemas, and study denormalization.

  - week: 13
    date: Week 13
    topic: Indexing and Hashing
    description: Introduction to search keys, index files, ordered indices, dense and sparse indices, hash indices, and evaluation of indexing strategies.

  - week: 14
    date: Week 14
    topic: B+ Trees and Hashing
    description: Introduction to multilevel indexing, B+ tree construction, insertion, updating, deletion, hash functions, buckets, static hashing, bucket overflow, dynamic hashing, and extendible hashing.

  - week: 15
    date: Week 15
    topic: Transactions and Concurrency Control
    description: Study of transaction states, ACID properties, transaction atomicity and durability, storage structures, concurrency control, and transaction management techniques.

  - week: 16
    date: Week 16
    topic: Database Case Study and Problem Solving
    description: Application of database design, SQL, normalization, indexing, and transaction concepts to a real-world database case study through problem solving and discussion.

  - week: 17
    date: Week 17
    topic: Final Review and Case Study
    description: Comprehensive review of database systems concepts, SQL, database design, normalization, indexing, hashing, transactions, and concurrency control in preparation for the final examination.

---

<style>

/* =========================================================
   COURSE DETAIL PAGE
   WHITE / BLACK ACADEMIC STYLE
   ========================================================= */

.course-content,
.course-page,
.course-description {

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
   HEADINGS
   ========================================================= */

.course-content h1,
.course-content h2,
.course-content h3,
.course-content h4,
.course-page h1,
.course-page h2,
.course-page h3,
.course-page h4 {

  color: #000000 !important;

  font-family:
    Georgia,
    "Times New Roman",
    serif;

  font-weight: 700;
}


.course-content h1,
.course-page h1 {

  font-size: 32px;

  line-height: 1.4;

  margin-top: 0;
  margin-bottom: 20px;
}


.course-content h2,
.course-page h2 {

  font-size: 27px;

  line-height: 1.4;

  margin-top: 34px;
  margin-bottom: 18px;

  padding-bottom: 8px;

  border-bottom: 2px solid #000000;
}


.course-content h3,
.course-page h3 {

  font-size: 22px;

  line-height: 1.45;

  margin-top: 25px;
  margin-bottom: 12px;
}


.course-content h4,
.course-page h4 {

  font-size: 19px;

  line-height: 1.45;
}


/* =========================================================
   PARAGRAPHS
   ========================================================= */

.course-content p,
.course-page p,
.course-description {

  color: #222222;

  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  font-size: 17px;

  line-height: 1.8;

  margin-top: 0;

  margin-bottom: 18px;

  text-align: justify;

  text-justify: inter-word;
}


/* =========================================================
   BOLD TEXT
   ========================================================= */

.course-content strong,
.course-page strong {

  color: #000000;

  font-weight: 700;
}


/* =========================================================
   LISTS
   ========================================================= */

.course-content ul,
.course-content ol,
.course-page ul,
.course-page ol {

  margin-top: 8px;

  margin-bottom: 18px;

  padding-left: 25px;

  color: #222222;

  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  font-size: 16px;

  line-height: 1.75;
}


.course-content li,
.course-page li {

  margin-bottom: 7px;
}


/* =========================================================
   LINKS
   ========================================================= */

.course-content a,
.course-page a {

  color: #000000 !important;

  text-decoration: underline;

  text-decoration-thickness: 1px;

  text-underline-offset: 3px;

  transition: opacity 0.2s ease;
}


.course-content a:hover,
.course-page a:hover {

  color: #000000 !important;

  opacity: 0.6;
}


/* =========================================================
   COURSE INFORMATION
   ========================================================= */

.course-info,
.course-meta {

  color: #333333;

  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  font-size: 16px;

  line-height: 1.75;
}


/* =========================================================
   CARDS
   ========================================================= */

.course-content .card,
.course-page .card {

  background: #ffffff !important;

  color: #111111 !important;

  border: 1px solid #d2d2d2;

  border-radius: 7px;

  box-shadow:
    0 4px 14px rgba(0, 0, 0, 0.06);

  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease,
    border-color 0.25s ease;
}


.course-content .card:hover,
.course-page .card:hover {

  transform: translateY(-3px);

  border-color: #999999;

  box-shadow:
    0 9px 22px rgba(0, 0, 0, 0.11);
}


.course-content .card-body,
.course-page .card-body {

  padding: 22px;
}


.course-content .card-title,
.course-page .card-title {

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


.course-content .card-text,
.course-page .card-text {

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

.course-content .table,
.course-page .table {

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


.course-content .table th,
.course-page .table th {

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


.course-content .table td,
.course-page .table td {

  padding: 10px 14px;

  background: #ffffff;

  color: #222222;

  border: 1px solid #d2d2d2;

  vertical-align: top;
}


.course-content .table tbody tr:hover td,
.course-page .table tbody tr:hover td {

  background: #f8f8f8;
}


/* =========================================================
   CODE
   ========================================================= */

.course-content code,
.course-page code {

  font-family:
    "Courier New",
    Courier,
    monospace;

  font-size: 14px;
}


.course-content pre,
.course-page pre {

  padding: 15px;

  background: #f5f5f5;

  border: 1px solid #d2d2d2;

  border-radius: 6px;

  overflow-x: auto;

  font-size: 14px;

  line-height: 1.6;
}


/* =========================================================
   DIVIDERS
   ========================================================= */

.course-content hr,
.course-page hr {

  border: none;

  border-top: 2px solid #000000;

  margin: 30px auto;
}


/* =========================================================
   BUTTONS
   ========================================================= */

.course-content .btn,
.course-page .btn {

  display: inline-flex;

  align-items: center;

  justify-content: center;

  padding: 8px 16px;

  background: #ffffff !important;

  color: #000000 !important;

  border: 1px solid #000000;

  border-radius: 5px;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 13px;

  font-weight: 600;

  line-height: 1.4;

  text-decoration: none !important;

  transition:
    background-color 0.2s ease,
    color 0.2s ease,
    transform 0.2s ease;
}


.course-content .btn:hover,
.course-page .btn:hover {

  background: #000000 !important;

  color: #ffffff !important;

  border-color: #000000;

  transform: translateY(-2px);
}


/* =========================================================
   MUTED TEXT
   ========================================================= */

.course-content .text-muted,
.course-page .text-muted {

  color: #555555 !important;
}


/* =========================================================
   TABLET
   ========================================================= */

@media (max-width: 900px) {

  .course-content,
  .course-page,
  .course-description {

    font-size: 16px;

    line-height: 1.75;
  }


  .course-content h1,
  .course-page h1 {

    font-size: 30px;
  }


  .course-content h2,
  .course-page h2 {

    font-size: 25px;
  }


  .course-content h3,
  .course-page h3 {

    font-size: 21px;
  }


  .course-content p,
  .course-page p,
  .course-description {

    font-size: 16px;
  }


  .course-content .card-text,
  .course-page .card-text {

    font-size: 15px;
  }
}


/* =========================================================
   MOBILE
   ========================================================= */

@media (max-width: 768px) {

  .course-content,
  .course-page,
  .course-description {

    font-size: 15.5px;

    line-height: 1.75;
  }


  .course-content h1,
  .course-page h1 {

    font-size: 24px;
  }


  .course-content h2,
  .course-page h2 {

    font-size: 23px;

    margin-top: 30px;
  }


  .course-content h3,
  .course-page h3 {

    font-size: 20px;
  }


  .course-content p,
  .course-page p,
  .course-description {

    font-size: 15.5px;

    line-height: 1.75;

    text-align: left;
  }


  .course-content ul,
  .course-content ol,
  .course-page ul,
  .course-page ol {

    font-size: 15px;

    line-height: 1.7;
  }


  .course-content .card-title,
  .course-page .card-title {

    font-size: 18px;
  }


  .course-content .card-text,
  .course-page .card-text {

    font-size: 15px;

    line-height: 1.7;

    text-align: left;
  }


  .course-content .table,
  .course-page .table {

    font-size: 14px;
  }


  .course-content .table th,
  .course-content .table td,
  .course-page .table th,
  .course-page .table td {

    padding: 9px 10px;
  }
}


/* =========================================================
   SMALL MOBILE
   ========================================================= */

@media (max-width: 576px) {

  .course-content,
  .course-page,
  .course-description {

    font-size: 14px;

    line-height: 1.7;
  }


  .course-content h1,
  .course-page h1 {

    font-size: 21px;
  }


  .course-content h2,
  .course-page h2 {

    font-size: 21px;
  }


  .course-content h3,
  .course-page h3 {

    font-size: 19px;
  }


  .course-content p,
  .course-page p,
  .course-description {

    font-size: 14px;

    line-height: 1.7;
  }


  .course-content ul,
  .course-content ol,
  .course-page ul,
  .course-page ol {

    font-size: 14px;
  }


  .course-content .card-title,
  .course-page .card-title {

    font-size: 18px;
  }


  .course-content .card-text,
  .course-page .card-text {

    font-size: 14px;
  }


  .course-content .table,
  .course-page .table {

    font-size: 13px;
  }


  .course-content .btn,
  .course-page .btn {

    font-size: 12px;

    padding: 7px 13px;
  }
}

</style>


## Course Overview

This course introduces the fundamental concepts and practices of database systems, with emphasis on designing, implementing, maintaining, and retrieving information efficiently from database management systems. Students will develop practical and theoretical knowledge of relational databases, SQL, database design, normalization, indexing, hashing, and transaction management. The course also develops the ability to analyze database performance and apply appropriate techniques for efficient database management.

By the end of this course, students will be able to:

- Understand the fundamental concepts and terminology of database management systems.
- Explain and apply SQL and relational algebra for manipulation of relational data.
- Design well-defined relational databases using ER modeling and normalization techniques.
- Analyze functional dependencies and determine appropriate database keys.
- Apply indexing and hashing techniques for efficient database access.
- Understand transaction management, ACID properties, and concurrency control.


## Prerequisites

- No formal prerequisite.
- Basic programming knowledge.
- Basic understanding of data structures and algorithms.
- Basic mathematical and problem-solving skills.


## Textbooks

- **Primary:** *Database System Concepts* by Abraham Silberschatz, Henry F. Korth, and S. Sudarshan.
- **Reference:** *Database Management Systems* by Raghu Ramakrishnan and Johannes Gehrke.
- **Reference:** *Database Systems* by Ramez Elmasri and Shamkant B. Navathe.
- **Reference:** *Database Systems: Introduction to Databases and Data Warehouses* by Nenad Jukić, Susan Vrbsky, Svetlozar Nestorov, and Abhishek Sharma.


## Tools and Platforms

- MySQL
- PostgreSQL
- Microsoft SQL Server
- Oracle Database
- MySQL Workbench
- phpMyAdmin
- Visual Studio Code
- Git and GitHub
- ER Diagram / UML Modeling Tools


## Grading

- **Class Participation and Activity:** 5%
- **Class Tests:** 15%
- **Assignment/Report and Presentation/Viva:** 10%
- **Midterm Examination:** 30%
- **Final Examination:** 40%

**Total: 100%**


---
layout: course
title: Structured Programming Language Lab
description: This laboratory course provides hands-on experience in structured programming using the C programming language. Students will develop practical skills in programming fundamentals, conditional statements, loops, functions, arrays, recursion, strings, pointers, structures, file handling, and programming problem-solving techniques.
instructor: Md. Shakil Ahmed
year: 2025
term: Spring
importance: 8
course_id: cse-102-structured-programming-language-lab

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
      <i class="fas fa-code"></i>
    </div>

    <div>

      <h1 class="course-title">
        Structured Programming Language Lab
      </h1>

      <p class="course-subtitle">
        CSE 102 · Laboratory Course · 1.5 Credit Hours
      </p>

    </div>

  </div>

  <div class="course-description">

    This laboratory course provides practical experience in
    <strong>structured programming using the C programming language</strong>.
    Students develop programming and problem-solving skills through
    controlled laboratory exercises involving fundamental programming
    constructs, functions, arrays, recursion, strings, pointers,
    structures, file handling, and programming practice.

  </div>

  <div class="course-tags">

    <span class="course-tag">C Programming</span>
    <span class="course-tag">Programming Fundamentals</span>
    <span class="course-tag">Conditional Statements</span>
    <span class="course-tag">Loops</span>
    <span class="course-tag">Functions</span>
    <span class="course-tag">Arrays</span>
    <span class="course-tag">Recursion</span>
    <span class="course-tag">Strings</span>
    <span class="course-tag">Pointers</span>
    <span class="course-tag">Structures</span>
    <span class="course-tag">File Handling</span>
    <span class="course-tag">Problem Solving</span>

  </div>

</div>

<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>
    This laboratory course provides students with practical experience in
    structured programming using the C programming language. The course is
    designed to complement CSE 101: Structured Programming Language by
    providing hands-on implementation of fundamental programming concepts
    through laboratory exercises and programming problems.
  </p>

  <p>
    Laboratory activities cover programming fundamentals, conditional
    statements, loops, functions, arrays, recursion, strings, pointers,
    structures, file handling, and computational problem solving. Students
    will implement, test, debug, and analyze C programs while developing
    systematic and algorithmic approaches to programming problems.
  </p>

  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-code"></i>

            CLO1 — Programming Fundamentals

          </h4>

          <p class="card-text">

            Apply fundamental programming concepts, operators, conditional
            statements, and control structures to develop C programs.

          </p>

        </div>

      </div>

    </div>

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-sync-alt"></i>

            CLO2 — Functions and Control Structures

          </h4>

          <p class="card-text">

            Implement loops, nested control structures, functions, and
            recursion to solve computational and programming problems.

          </p>

        </div>

      </div>

    </div>

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-th"></i>

            CLO3 — Data Structures and Memory

          </h4>

          <p class="card-text">

            Apply arrays, strings, pointers, and structures to organize,
            manipulate, and process data in C programs.

          </p>

        </div>

      </div>

    </div>

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-file-code"></i>

            CLO4 — Problem Solving and Implementation

          </h4>

          <p class="card-text">

            Develop, test, debug, and implement C programs for computational
            problems, including file-handling and programming practice tasks.

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
      CSE 101: Structured Programming Language.
    </li>

    <li>
      Basic computer literacy.
    </li>

    <li>
      Basic understanding of programming concepts.
    </li>

  </ul>

  <h2 class="course-section-title">
    Textbooks
  </h2>

  <ul>

    <li>

      <strong>Primary:</strong>
      <em>Teach Yourself C</em>, 3rd Edition, by Herbert Schildt.

    </li>

  </ul>

  <h2 class="course-section-title">
    Reference Books
  </h2>

  <ul>

    <li>
      <em>Programming in ANSI C</em>, 8th Edition, by E. Balagurusamy.
    </li>

    <li>
      <em>The C Programming Language</em>, 2nd Edition, by Brian W. Kernighan and Dennis M. Ritchie.
    </li>

    <li>
      <em>Let Us C</em> by Yashavant Kanetkar.
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

            <i class="fas fa-terminal"></i>

            C Programming Environment

          </h4>

          <p class="card-text">

            GCC compiler, Code::Blocks, Visual Studio Code, and other
            development environments for writing, compiling, testing,
            and debugging C programs.

          </p>

        </div>

      </div>

    </div>

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-laptop-code"></i>

            Programming Practice

          </h4>

          <p class="card-text">

            Online judges and programming practice platforms for solving
            algorithmic problems and developing programming problem-solving
            skills.

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
        href="https://en.cppreference.com/w/c"
        target="_blank"
        rel="noopener noreferrer"
      >
        C Language Reference — cppreference
      </a>

    </li>

    <li>

      <a
        href="https://gcc.gnu.org/onlinedocs/gcc/"
        target="_blank"
        rel="noopener noreferrer"
      >
        GCC Documentation
      </a>

    </li>

    <li>

      <a
        href="https://www.onlinegdb.com/"
        target="_blank"
        rel="noopener noreferrer"
      >
        OnlineGDB
      </a>

    </li>

    <li>

      <a
        href="https://www.hackerrank.com/domains/c"
        target="_blank"
        rel="noopener noreferrer"
      >
        HackerRank C Practice
      </a>

    </li>

  </ul>

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
            Class Participation and Activity
          </td>

          <td>
            5%
          </td>

        </tr>

        <tr>

          <td>
            Continuous Lab Evaluation &amp; Assignments
          </td>

          <td>
            25%
          </td>

        </tr>

        <tr>

          <td>
            Lab Midterm Examination
          </td>

          <td>
            30%
          </td>

        </tr>

        <tr>

          <td>
            Final Lab Evaluation
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

          <td>
            1
          </td>

          <td>
            Introduction to Programming Tools and Basic C Programs
          </td>

          <td>
            Introduction to the C programming environment, compiler and
            IDE setup, and writing, compiling, and executing basic C
            programs.
          </td>

        </tr>

        <tr>

          <td>
            2
          </td>

          <td>
            Conditional Statements and Operators
          </td>

          <td>
            Practical implementation of arithmetic, relational, logical,
            and assignment operators, along with if, if-else, and nested
            if-else statements.
          </td>

        </tr>

        <tr>

          <td>
            3
          </td>

          <td>
            Looping Statements
          </td>

          <td>
            Practical implementation of for, while, and do-while loops
            for iterative problem solving.
          </td>

        </tr>

        <tr>

          <td>
            4
          </td>

          <td>
            Nested Loops and Loop-Based Problem Solving
          </td>

          <td>
            Implementation of nested loops, pattern printing, series,
            summation, and other loop-based programming problems.
          </td>

        </tr>

        <tr>

          <td>
            5
          </td>

          <td>
            Switch-Case, Break, and Continue
          </td>

          <td>
            Practical implementation of switch-case structures,
            menu-driven programs, and break and continue statements.
          </td>

        </tr>

        <tr>

          <td>
            6
          </td>

          <td>
            Functions and Argument Passing
          </td>

          <td>
            Implementation of function declaration, definition, calling,
            argument passing, return values, and modular programming.
          </td>

        </tr>

        <tr>

          <td>
            7
          </td>

          <td>
            One-Dimensional and Two-Dimensional Arrays
          </td>

          <td>
            Practical implementation of array declaration, initialization,
            traversal, searching, basic array operations, two-dimensional
            arrays, and matrix operations.
          </td>

        </tr>

        <tr>

          <td>
            8
          </td>

          <td>
            Midterm Laboratory Examination
          </td>

          <td>
            Midterm laboratory examination covering programming
            fundamentals, conditional statements, loops, functions,
            and arrays.
          </td>

        </tr>

        <tr>

          <td>
            9
          </td>

          <td>
            Recursive Functions
          </td>

          <td>
            Introduction to recursion and implementation of recursive
            functions for factorial, Fibonacci, summation, and other
            problem-solving tasks.
          </td>

        </tr>

        <tr>

          <td>
            10
          </td>

          <td>
            Strings and String Functions
          </td>

          <td>
            Practical implementation of character arrays, strings,
            string input and output, common string library functions,
            and string processing problems.
          </td>

        </tr>

        <tr>

          <td>
            11
          </td>

          <td>
            String Manipulation
          </td>

          <td>
            Implementation of string copying, comparison, reversal,
            concatenation, and other string manipulation operations.
          </td>

        </tr>

        <tr>

          <td>
            12
          </td>

          <td>
            Pointers and Pointer-Based Programming
          </td>

          <td>
            Introduction to pointers and practical implementation of
            pointers with arrays, strings, and functions.
          </td>

        </tr>

        <tr>

          <td>
            13
          </td>

          <td>
            File Handling and Structures
          </td>

          <td>
            Practical implementation of file creation, reading, writing,
            copying, and deletion, along with structures, typedef, and
            structure-based problem solving.
          </td>

        </tr>

        <tr>

          <td>
            14
          </td>

          <td>
            Online Judges and Competitive Programming
          </td>

          <td>
            Introduction to online judges, problem submission, verdicts,
            input and output specifications, time and memory limits, and
            basic competitive programming techniques.
          </td>

        </tr>

        <tr>

          <td>
            15
          </td>

          <td>
            Practice with Online Judge Problems
          </td>

          <td>
            Practice and discussion of programming problems from online
            judges, with emphasis on problem-solving and efficient
            implementation.
          </td>

        </tr>

        <tr>

          <td>
            16
          </td>

          <td>
            Final Laboratory Examination
          </td>

          <td>
            Final laboratory examination assessing programming
            implementation and problem-solving skills.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
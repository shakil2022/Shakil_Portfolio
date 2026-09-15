---
layout: course
title: Object Oriented Programming Language Lab
description: This laboratory course provides hands-on experience in Object-Oriented Programming using C++. Students will implement classes, objects, constructors, destructors, encapsulation, inheritance, polymorphism, abstraction, function overloading, operator overloading, file handling, templates, exception handling, and Standard Template Library components through practical programming exercises, problem-solving activities, and project development.
instructor: Md. Shakil Ahmed
year: 2024
term: Fall
importance: 10
course_id: cse-1201-2-object-oriented-programming-language-lab
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
        Object Oriented Programming Language Lab
      </h1>

      <p class="course-subtitle">
        CSE 1201-2 · Object-Oriented Programming Laboratory · 1.5 Credit Hours
      </p>

    </div>

  </div>

  <div class="course-description">

    This laboratory course provides hands-on experience in
    <strong>Object-Oriented Programming using C++</strong>.
    Students will implement classes, objects, constructors, destructors,
    encapsulation, inheritance, polymorphism, abstraction, function
    overloading, operator overloading, file handling, templates,
    exception handling, and Standard Template Library components through
    practical programming exercises, problem-solving activities, and
    project development.

  </div>

  <div class="course-tags">

    <span class="course-tag">C++</span>
    <span class="course-tag">Object-Oriented Programming</span>
    <span class="course-tag">Classes</span>
    <span class="course-tag">Objects</span>
    <span class="course-tag">Encapsulation</span>
    <span class="course-tag">Inheritance</span>
    <span class="course-tag">Polymorphism</span>
    <span class="course-tag">Abstraction</span>
    <span class="course-tag">File Handling</span>
    <span class="course-tag">Templates</span>
    <span class="course-tag">Exception Handling</span>
    <span class="course-tag">STL</span>
    <span class="course-tag">Problem Solving</span>
    <span class="course-tag">Project Development</span>

  </div>

</div>


<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>

    This laboratory course provides students with practical experience in
    Object-Oriented Programming using the C++ programming language. The course
    is designed to complement the theoretical concepts of object-oriented
    programming by providing hands-on implementation of fundamental and
    advanced object-oriented programming concepts.

  </p>

  <p>

    Students will develop programs using classes, objects, constructors,
    destructors, encapsulation, inheritance, polymorphism, abstraction,
    function overloading, operator overloading, file handling, templates,
    exception handling, and the Standard Template Library. The laboratory
    also emphasizes debugging, code reuse, software design, algorithmic
    problem-solving, and project development through practical programming
    exercises.

  </p>

  <p>
    By the end of this course, students will be able to:
  </p>

  <ul>

    <li>
      Implement C++ programs using fundamental programming and object-oriented
      programming principles.
    </li>

    <li>
      Design and implement classes and objects using appropriate access
      control and encapsulation.
    </li>

    <li>
      Implement constructors, destructors, function overloading, and
      operator overloading.
    </li>

    <li>
      Apply inheritance and polymorphism to develop reusable and extensible
      C++ programs.
    </li>

    <li>
      Implement abstraction using abstract classes and pure virtual functions.
    </li>

    <li>
      Perform file input and output operations using C++ file streams.
    </li>

    <li>
      Implement generic programs using function and class templates.
    </li>

    <li>
      Handle runtime errors using C++ exception-handling mechanisms.
    </li>

    <li>
      Use Standard Template Library containers, iterators, and algorithms
      to solve programming problems.
    </li>

    <li>
      Design, implement, debug, test, and document object-oriented
      programming projects.
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

            <i class="fas fa-cubes"></i>

            CLO1 — Classes and Objects

          </h4>

          <p class="card-text">

            Design and implement classes and objects using constructors,
            destructors, access specifiers, and encapsulation to develop
            structured C++ programs.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-sitemap"></i>

            CLO2 — Inheritance and Polymorphism

          </h4>

          <p class="card-text">

            Apply inheritance, function overriding, virtual functions,
            and polymorphism to develop reusable and extensible
            object-oriented programs.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-layer-group"></i>

            CLO3 — Advanced C++ Programming

          </h4>

          <p class="card-text">

            Implement abstraction, file handling, templates, exception
            handling, and other advanced C++ programming techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-laptop-code"></i>

            CLO4 — STL and Project Development

          </h4>

          <p class="card-text">

            Use Standard Template Library components to solve programming
            problems and develop, test, debug, document, and present
            object-oriented programming projects.

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
      Basic programming knowledge.
    </li>

    <li>
      Basic problem-solving skills.
    </li>

    <li>
      Familiarity with fundamental programming concepts.
    </li>

    <li>
      Basic understanding of procedural programming.
    </li>

    <li>
      Basic knowledge of C or C++ programming.
    </li>

  </ul>


  <h2 class="course-section-title">
    Textbooks
  </h2>

  <ul>

    <li>

      <strong>Primary:</strong>
      <em>The C++ Programming Language</em>
      by Bjarne Stroustrup.

    </li>

  </ul>


  <h2 class="course-section-title">
    Reference Books
  </h2>

  <ul>

    <li>

      <em>Object-Oriented Programming with C++</em>
      by E. Balagurusamy.

    </li>

    <li>

      <em>C++ Primer</em>, 5th Edition,
      by Stanley B. Lippman, Josée Lajoie, and Barbara E. Moo.

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

            C++ Development Environment

          </h4>

          <p class="card-text">

            C++ programming language, GCC/G++ compiler, Visual Studio Code,
            Code::Blocks, Microsoft Visual Studio, and other C++ development
            environments.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-tools"></i>

            Programming Libraries and Platforms

          </h4>

          <p class="card-text">

            C++ Standard Template Library, online C++ compilers, online
            programming platforms, and competitive programming platforms
            for practical problem solving.

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
        href="https://en.cppreference.com/w/"
        target="_blank"
        rel="noopener noreferrer"
      >
        C++ Reference — cppreference.com
      </a>

    </li>

    <li>

      <a
        href="https://cplusplus.com/doc/"
        target="_blank"
        rel="noopener noreferrer"
      >
        C++ Documentation — cplusplus.com
      </a>

    </li>

    <li>

      <a
        href="https://isocpp.org/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Standard C++ Foundation
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
            Introduction to C++ Programming and Object-Oriented Programming
          </td>

          <td>
            Introduction to the C++ programming environment, compiler and IDE
            setup, basic C++ program structure, input and output operations,
            namespaces, and implementation of simple C++ programs.
          </td>

        </tr>

        <tr>

          <td>2</td>

          <td>
            Data Types, Operators, Control Structures, and Functions
          </td>

          <td>
            Practical implementation of C++ data types, operators,
            expressions, conditional statements, loops, nested control
            structures, and functions through programming exercises and
            problem-solving tasks.
          </td>

        </tr>

        <tr>

          <td>3</td>

          <td>
            Functions and Function-Based Problem Solving
          </td>

          <td>
            Implementation of function declaration and definition,
            parameter passing, return values, default arguments, inline
            functions, recursion, and function-based programming problems
            in C++.
          </td>

        </tr>

        <tr>

          <td>4</td>

          <td>
            Classes, Objects, Constructors, and Destructors
          </td>

          <td>
            Practical implementation of classes and objects, access
            specifiers, data members, member functions, default constructors,
            parameterized constructors, copy constructors, and destructors.
          </td>

        </tr>

        <tr>

          <td>5</td>

          <td>
            Encapsulation, Function Overloading, and Operator Overloading
          </td>

          <td>
            Implementation of encapsulation using access specifiers and
            implementation of function overloading and operator overloading
            to demonstrate compile-time polymorphism in C++.
          </td>

        </tr>

        <tr>

          <td>6</td>

          <td>
            Inheritance and Its Types
          </td>

          <td>
            Practical implementation of single, multiple, multilevel,
            hierarchical, and hybrid inheritance using base and derived
            classes. Students will explore access control, code reuse,
            and relationships between classes.
          </td>

        </tr>

        <tr>

          <td>7</td>

          <td>
            Midterm Review and Examination
          </td>

          <td>
            Review of C++ programming, classes, objects, constructors,
            destructors, encapsulation, function overloading, operator
            overloading, and inheritance, followed by the midterm
            laboratory examination.
          </td>

        </tr>

        <tr>

          <td>8</td>

          <td>
            Polymorphism and Virtual Functions
          </td>

          <td>
            Practical implementation of compile-time and runtime
            polymorphism using function overloading, operator overloading,
            function overriding, virtual functions, base-class pointers,
            and dynamic binding.
          </td>

        </tr>

        <tr>

          <td>9</td>

          <td>
            Abstraction and Abstract Classes
          </td>

          <td>
            Implementation of abstraction using abstract classes and pure
            virtual functions. Students will design programs that demonstrate
            abstract behavior, reusable class structures, and object-oriented
            design principles.
          </td>

        </tr>

        <tr>

          <td>10</td>

          <td>
            File Handling in C++
          </td>

          <td>
            Practical implementation of file input and output using fstream,
            ifstream, and ofstream. Students will create, open, read, write,
            append, and process text and binary files.
          </td>

        </tr>

        <tr>

          <td>11</td>

          <td>
            Templates and Exception Handling
          </td>

          <td>
            Implementation of function templates and class templates for
            generic programming. Students will also implement exception
            handling using try, catch, and throw mechanisms to manage
            runtime errors.
          </td>

        </tr>

        <tr>

          <td>12</td>

          <td>
            Standard Template Library
          </td>

          <td>
            Practical use of the C++ Standard Template Library, including
            vectors, lists, stacks, queues, sets, maps, iterators, and
            standard algorithms for solving programming problems.
          </td>

        </tr>

        <tr>

          <td>13</td>

          <td>
            STL-Based Problem Solving and Project Development
          </td>

          <td>
            Application of object-oriented programming concepts and STL
            components to develop practical programming solutions. Students
            will solve programming problems and begin implementation of
            their final laboratory projects.
          </td>

        </tr>

        <tr>

          <td>14</td>

          <td>
            Final Project Implementation and Debugging
          </td>

          <td>
            Implementation, testing, debugging, and optimization of
            object-oriented programming projects. Students will apply
            appropriate concepts such as classes, inheritance, polymorphism,
            abstraction, file handling, templates, and STL.
          </td>

        </tr>

        <tr>

          <td>15</td>

          <td>
            Final Project Evaluation
          </td>

          <td>
            Evaluation of the final object-oriented programming project,
            including program functionality, code organization,
            object-oriented design, testing, documentation, and
            implementation quality.
          </td>

        </tr>

        <tr>

          <td>16</td>

          <td>
            Brainstorming and Problem Solving
          </td>

          <td>
            Intensive discussion, brainstorming, debugging, and
            problem-solving activities to strengthen C++ programming,
            object-oriented design, algorithmic thinking, and practical
            implementation skills.
          </td>

        </tr>

        <tr>

          <td>17</td>

          <td>
            Final Project Presentation, Viva, and Review
          </td>

          <td>
            Presentation and viva of laboratory projects, demonstration
            of program functionality, discussion of object-oriented
            concepts used, project design, implementation, testing,
            and comprehensive review of laboratory activities.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
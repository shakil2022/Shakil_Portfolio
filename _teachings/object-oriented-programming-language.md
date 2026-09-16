---

layout: course
title: Object Oriented Programming Language
description: This course introduces the fundamental concepts and principles of Object-Oriented Programming using C++. Students will develop programming logic, object-oriented design, and problem-solving skills through the study of classes, objects, encapsulation, inheritance, polymorphism, abstraction, function overloading, operator overloading, file handling, templates, exception handling, and the Standard Template Library.
instructor: Md. Shakil Ahmed
year: 2024
term: Fall
importance: 9
course_id: cse-1201-1-object-oriented-programming-language

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
  <i class="fas fa-cubes"></i>
</div>

<div>

  <h1 class="course-title">
    Object Oriented Programming Language
  </h1>

  <p class="course-subtitle">
    CSE 1201-1 · Core Engineering Course · 3.0 Credit Hours
  </p>

</div>


  </div>

  <div class="course-description">


This course introduces the fundamental concepts and principles of
<strong>Object-Oriented Programming using C++</strong>. Students develop
programming logic, object-oriented design, and problem-solving skills
through classes, objects, encapsulation, inheritance, polymorphism,
abstraction, file handling, templates, exception handling, and the
Standard Template Library.


  </div>

  <div class="course-tags">

<span class="course-tag">C++ Programming</span>
<span class="course-tag">Object-Oriented Programming</span>
<span class="course-tag">Classes and Objects</span>
<span class="course-tag">Encapsulation</span>
<span class="course-tag">Inheritance</span>
<span class="course-tag">Polymorphism</span>
<span class="course-tag">Abstraction</span>
<span class="course-tag">Operator Overloading</span>
<span class="course-tag">Templates</span>
<span class="course-tag">Exception Handling</span>
<span class="course-tag">STL</span>

  </div>

</div>

<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>
    This course introduces the fundamental concepts and principles of
    Object-Oriented Programming using the C++ programming language. Students
    will develop programming logic, computational thinking, and problem-solving
    skills while learning how to design and implement structured, reusable,
    maintainable, and efficient software solutions.
  </p>

  <p>
    The course covers classes, objects, encapsulation, inheritance,
    polymorphism, abstraction, function overloading, operator overloading,
    file handling, templates, exception handling, and the Standard Template
    Library. Emphasis is placed on object-oriented design, code reuse,
    modularity, maintainability, and practical problem solving using C++.
  </p>

  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">


<div class="col-md-6 mt-3">

  <div class="card h-100 feature-card">

    <div class="card-body">

      <h4 class="card-title">

        <i class="fas fa-lightbulb"></i>

        CLO1 — OOP Fundamentals

      </h4>

      <p class="card-text">

        Explain the fundamental concepts and principles of Object-Oriented
        Programming and distinguish object-oriented programming from
        procedural programming.

      </p>

    </div>

  </div>

</div>


<div class="col-md-6 mt-3">

  <div class="card h-100 feature-card">

    <div class="card-body">

      <h4 class="card-title">

        <i class="fas fa-cubes"></i>

        CLO2 — Classes and Objects

      </h4>

      <p class="card-text">

        Design and implement classes and objects using appropriate access
        specifiers, constructors, destructors, encapsulation, function
        overloading, and operator overloading.

      </p>

    </div>

  </div>

</div>


<div class="col-md-6 mt-3">

  <div class="card h-100 feature-card">

    <div class="card-body">

      <h4 class="card-title">

        <i class="fas fa-project-diagram"></i>

        CLO3 — Inheritance and Polymorphism

      </h4>

      <p class="card-text">

        Apply inheritance, polymorphism, virtual functions, and dynamic
        binding to develop reusable and extensible C++ programs.

      </p>

    </div>

  </div>

</div>


<div class="col-md-6 mt-3">

  <div class="card h-100 feature-card">

    <div class="card-body">

      <h4 class="card-title">

        <i class="fas fa-laptop-code"></i>

        CLO4 — Advanced C++ Programming

      </h4>

      <p class="card-text">

        Implement abstraction, file handling, templates, exception
        handling, and Standard Template Library components in C++ programs.

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

        <i class="fas fa-terminal"></i>

        Programming Environment

      </h4>

      <p class="card-text">

        C++ Programming Language, GCC Compiler, Visual Studio Code,
        Code::Blocks, and other standard C++ development environments.

      </p>

    </div>

  </div>

</div>


<div class="col-md-6 mt-3">

  <div class="card h-100 feature-card">

    <div class="card-body">

      <h4 class="card-title">

        <i class="fas fa-code"></i>

        Problem Solving

      </h4>

      <p class="card-text">

        C++ programming exercises, algorithmic problem-solving platforms,
        and online programming environments for practical implementation.

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
  C++ programming language documentation and language references.
</li>

<li>
  C++ Standard Template Library documentation.
</li>

<li>
  Online C++ programming resources and tutorials.
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
        10%
      </td>

    </tr>

    <tr>

      <td>
        Assignments and Continuous Evaluation
      </td>

      <td>
        20%
      </td>

    </tr>

    <tr>

      <td>
        Midterm Examination
      </td>

      <td>
        30%
      </td>

    </tr>

    <tr>

      <td>
        Final Examination
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
    Course Information
  </h2>

  <ul>

<li>
  <strong>Course Code:</strong>
  CSE 1201-1
</li>

<li>
  <strong>Course Type:</strong>
  Theory Course
</li>

<li>
  <strong>Credit Hours:</strong>
  3.0
</li>

<li>
  <strong>Academic Session:</strong>
  Fall 2024
</li>

<li>
  <strong>Year-Semester:</strong>
  1-2
</li>

<li>
  <strong>Contact Hours:</strong>
  48 hours
</li>

<li>
  <strong>Instructor:</strong>
  Md. Shakil Ahmed
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
        Introduction to Object-Oriented Programming and C++
      </td>

      <td>
        Introduction to Object-Oriented Programming, fundamental OOP
        concepts, object-oriented programming paradigms, advantages of
        OOP over procedural programming, and an overview of the C++
        programming language.
      </td>

    </tr>

    <tr>

      <td>2</td>

      <td>
        Data Types, Operators, Control Structures, and Functions
      </td>

      <td>
        Study of C++ data types, variables, constants, operators,
        expressions, decision-making statements, loops, control
        structures, and fundamental programming techniques.
      </td>

    </tr>

    <tr>

      <td>3</td>

      <td>
        Functions and Problem Solving in C++
      </td>

      <td>
        Detailed study of function declaration and definition, parameter
        passing, return values, default arguments, inline functions,
        recursion, scope, and function-based problem solving.
      </td>

    </tr>

    <tr>

      <td>4</td>

      <td>
        Classes, Objects, Constructors, and Destructors
      </td>

      <td>
        Introduction to classes and objects, data members, member
        functions, access specifiers, constructors, default constructors,
        parameterized constructors, copy constructors, and destructors.
      </td>

    </tr>

    <tr>

      <td>5</td>

      <td>
        Encapsulation, Function Overloading, and Operator Overloading
      </td>

      <td>
        Study of encapsulation and data hiding using access specifiers,
        function overloading, and operator overloading. Students will
        examine compile-time polymorphism and its applications in C++.
      </td>

    </tr>

    <tr>

      <td>6</td>

      <td>
        Inheritance and Its Types
      </td>

      <td>
        Introduction to inheritance, base and derived classes, access
        control, and different types of inheritance including single,
        multiple, multilevel, hierarchical, and hybrid inheritance.
      </td>

    </tr>

    <tr>

      <td>7</td>

      <td>
        Midterm Review and Examination
      </td>

      <td>
        Comprehensive review of C++ programming fundamentals, classes,
        objects, constructors, destructors, encapsulation, function
        overloading, operator overloading, and inheritance, followed by
        the midterm examination.
      </td>

    </tr>

    <tr>

      <td>8</td>

      <td>
        Polymorphism and Virtual Functions
      </td>

      <td>
        Study of compile-time and runtime polymorphism, function
        overloading, operator overloading, function overriding, virtual
        functions, pure virtual functions, base-class pointers, and
        dynamic binding.
      </td>

    </tr>

    <tr>

      <td>9</td>

      <td>
        Abstraction and Abstract Classes
      </td>

      <td>
        Introduction to abstraction, abstract classes, pure virtual
        functions, interfaces, and the role of abstraction in
        object-oriented software design.
      </td>

    </tr>

    <tr>

      <td>10</td>

      <td>
        File Handling in C++
      </td>

      <td>
        Study of file input and output operations using C++ file streams,
        including text and binary files, file opening and closing,
        reading, writing, appending, file pointers, and file management
        techniques.
      </td>

    </tr>

    <tr>

      <td>11</td>

      <td>
        Templates and Generic Programming
      </td>

      <td>
        Introduction to generic programming using function templates and
        class templates. Study of template parameters, template
        specialization concepts, and reusable generic program design.
      </td>

    </tr>

    <tr>

      <td>12</td>

      <td>
        Exception Handling
      </td>

      <td>
        Study of exception handling in C++ using try, catch, and throw
        mechanisms. Students will learn to identify, propagate, and handle
        runtime errors and develop robust programs.
      </td>

    </tr>

    <tr>

      <td>13</td>

      <td>
        Standard Template Library
      </td>

      <td>
        Introduction to the C++ Standard Template Library, including
        containers, iterators, algorithms, vectors, lists, stacks, queues,
        sets, maps, and practical applications of STL components.
      </td>

    </tr>

    <tr>

      <td>14</td>

      <td>
        Object-Oriented Design and Problem Solving
      </td>

      <td>
        Application of object-oriented principles to analyze and solve
        programming problems. Emphasis on class relationships, code reuse,
        modularity, maintainability, and efficient software design.
      </td>

    </tr>

    <tr>

      <td>15</td>

      <td>
        Advanced C++ Programming and Problem Solving
      </td>

      <td>
        Integration of inheritance, polymorphism, abstraction, templates,
        exception handling, file handling, and STL to solve comprehensive
        programming problems and develop efficient C++ solutions.
      </td>

    </tr>

    <tr>

      <td>16</td>

      <td>
        Review and Final Examination Preparation
      </td>

      <td>
        Comprehensive review of object-oriented programming concepts,
        C++ programming techniques, common programming problems, and
        preparation for the final examination.
      </td>

    </tr>

    <tr>

      <td>17</td>

      <td>
        Final Examination and Course Review
      </td>

      <td>
        Final examination covering the major theoretical and programming
        concepts of the course, followed by a comprehensive review and
        discussion of key object-oriented programming principles.
      </td>

    </tr>

  </tbody>

</table>


  </div>

</div>

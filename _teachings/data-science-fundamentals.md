---
layout: course
title: Cyber Security and Digital Forensic
description: This course introduces the fundamental concepts of cybersecurity, ethical hacking, and digital forensics, including web application security, authentication, OSINT, reverse engineering, network forensics, cryptography, blockchain security, and cybersecurity law.
instructor: Md. Shakil Ahmed
year: 2026
term: Summer
importance: 1
course_id: cse-413-cyber-security-and-digital-forensic

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
      <i class="fas fa-shield-alt"></i>
    </div>

    <div>

      <h1 class="course-title">
        Cyber Security and Digital Forensic
      </h1>

      <p class="course-subtitle">
        CSE 413 · Core Course · 3.0 Credit Hours
      </p>

    </div>

  </div>

  <div class="course-description">

    This course introduces <strong>cybersecurity, ethical hacking, and
    digital forensics</strong> through the study of web application security,
    authentication, security analysis, forensic investigation, cryptography,
    and cybersecurity law.

  </div>

  <div class="course-tags">

    <span class="course-tag">Cybersecurity</span>
    <span class="course-tag">Ethical Hacking</span>
    <span class="course-tag">Digital Forensics</span>
    <span class="course-tag">Web Security</span>
    <span class="course-tag">Authentication</span>
    <span class="course-tag">OSINT</span>
    <span class="course-tag">Python</span>
    <span class="course-tag">Reverse Engineering</span>
    <span class="course-tag">Network Forensics</span>
    <span class="course-tag">Cryptography</span>
    <span class="course-tag">Blockchain Security</span>
    <span class="course-tag">Cyber Law</span>

  </div>

</div>


<div class="course-content">

  <h2 class="course-section-title">
    Course Overview
  </h2>

  <p>
    This course provides a comprehensive study of cybersecurity and digital
    forensics, with emphasis on understanding security threats, vulnerabilities,
    attacks, authentication mechanisms, forensic evidence, and defensive
    practices. Students will examine common web application vulnerabilities,
    security testing techniques, information-gathering methods, reverse
    engineering, binary analysis, network forensics, cryptography, blockchain
    security, and cybersecurity law.
  </p>

  <p>
    The course combines theoretical concepts with practical security analysis
    and investigation scenarios. Students will develop the ability to identify
    vulnerabilities, analyze security incidents, investigate digital evidence,
    and apply ethical, legal, and responsible cybersecurity practices.
  </p>


  <h2 class="course-section-title">
    Course Learning Outcomes
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-shield-alt"></i>

            CLO1 — Cybersecurity Fundamentals

          </h4>

          <p class="card-text">

            Explain fundamental cybersecurity concepts, security principles,
            common threats, vulnerabilities, attacks, and defensive practices.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-user-shield"></i>

            CLO2 — Security Analysis

          </h4>

          <p class="card-text">

            Analyze web application vulnerabilities, authentication weaknesses,
            application logic flaws, and other common security issues using
            appropriate security concepts and techniques.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-search"></i>

            CLO3 — Digital Forensics

          </h4>

          <p class="card-text">

            Apply digital forensic methods to collect, examine, analyze, and
            interpret digital evidence from system, memory, and network sources.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-balance-scale"></i>

            CLO4 — Ethical and Legal Practice

          </h4>

          <p class="card-text">

            Demonstrate ethical, legal, and responsible practices when
            performing cybersecurity analysis, security testing, and forensic
            investigations.

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
      Basic computer and operating system knowledge.
    </li>

    <li>
      Basic networking concepts are recommended.
    </li>

    <li>
      Basic programming knowledge is recommended.
    </li>

  </ul>


  <h2 class="course-section-title">
    Textbooks
  </h2>

  <ul>

    <li>

      <strong>Primary:</strong>
      <em>The Web Application Hacker's Handbook</em>
      by Dafydd Stuttard and Marcus Pinto.

    </li>

    <li>

      <strong>Primary:</strong>
      <em>Guide to Computer Forensics and Investigations</em>
      by Bill Nelson.

    </li>

  </ul>


  <h2 class="course-section-title">
    Reference Books
  </h2>

  <ul>

    <li>
      <em>Cybersecurity Essentials</em> by Charles J. Brooks.
    </li>

    <li>
      <em>Social Engineering: The Science of Human Hacking</em>
      by Christopher Hadnagy.
    </li>

    <li>
      <em>Black Hat Python: Python Programming for Hackers and Pentesters</em>
      by Justin Seitz and Tim Arnold.
    </li>

    <li>
      <em>Practical Reverse Engineering</em>
      by Bruce Dang and Alexandre Gazet.
    </li>

    <li>
      <em>Cryptography and Network Security: Principles and Practice</em>
      by William Stallings.
    </li>

    <li>
      <em>Cybersecurity and Cyberlaw</em>
      by Pavan Duggal.
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

            <i class="fas fa-laptop-code"></i>

            Security Testing

          </h4>

          <p class="card-text">

            Kali Linux, Burp Suite, DVWA, Python, and related security
            testing tools for controlled cybersecurity exercises.

          </p>

        </div>

      </div>

    </div>


    <div class="col-md-6 mt-3">

      <div class="card h-100 feature-card">

        <div class="card-body">

          <h4 class="card-title">

            <i class="fas fa-folder-open"></i>

            Forensic and Analysis Tools

          </h4>

          <p class="card-text">

            Autopsy, Volatility, Ghidra, Wireshark, and related tools for
            digital forensic, memory, network, and binary analysis.

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
        href="https://owasp.org/www-project-web-security-testing-guide/"
        target="_blank"
        rel="noopener noreferrer"
      >
        OWASP Web Security Testing Guide
      </a>

    </li>

    <li>

      <a
        href="https://www.kali.org/"
        target="_blank"
        rel="noopener noreferrer"
      >
        Kali Linux
      </a>

    </li>

    <li>

      <a
        href="https://portswigger.net/web-security"
        target="_blank"
        rel="noopener noreferrer"
      >
        PortSwigger Web Security Academy
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
          <td>CSE 413</td>

        </tr>

        <tr>

          <td>Course Title</td>
          <td>Cyber Security and Digital Forensic</td>

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
          <td>Summer 2026</td>

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

          <td>Class Participation</td>
          <td>5%</td>

        </tr>

        <tr>

          <td>Assignment / Presentation / Viva</td>
          <td>10%</td>

        </tr>

        <tr>

          <td>Class Test</td>
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
            Introduction to Cybersecurity and Digital Forensics
          </td>

          <td>
            Introduction to cybersecurity, the CIA triad, key security
            principles, incident management, penetration testing, digital
            evidence, evidence handling, and chain of custody.
          </td>

        </tr>

        <tr>

          <td>2</td>

          <td>
            SQL Injection and Cross-Site Scripting
          </td>

          <td>
            Study of SQL injection techniques and cross-site scripting
            vulnerabilities, including reflected, stored, and DOM-based XSS
            in controlled environments.
          </td>

        </tr>

        <tr>

          <td>3</td>

          <td>
            CSRF and Clickjacking
          </td>

          <td>
            Understanding Cross-Site Request Forgery, implicit trust in
            authenticated requests, clickjacking, UI redress attacks, and
            insecure DOM manipulation.
          </td>

        </tr>

        <tr>

          <td>4</td>

          <td>
            CORS, XXE, SSRF, and HTTP Request Smuggling
          </td>

          <td>
            Introduction to CORS misconfigurations, XML External Entity
            injection, Server-Side Request Forgery, and HTTP request
            smuggling vulnerabilities.
          </td>

        </tr>

        <tr>

          <td>5</td>

          <td>
            Command Injection, SSTI, and Access Control
          </td>

          <td>
            Study of OS command injection, Server-Side Template Injection,
            path traversal, arbitrary file access, and broken access control
            vulnerabilities.
          </td>

        </tr>

        <tr>

          <td>6</td>

          <td>
            Midterm Examination
          </td>

          <td>
            Review of the topics covered during the first half of the course
            followed by the midterm examination.
          </td>

        </tr>

        <tr>

          <td>7</td>

          <td>
            Authentication and Application Logic
          </td>

          <td>
            Study of JWT and OAuth authentication issues, token tampering,
            OAuth misconfiguration, and application logic vulnerabilities.
          </td>

        </tr>

        <tr>

          <td>8</td>

          <td>
            OSINT, Social Engineering, and Python Basics
          </td>

          <td>
            Introduction to open-source intelligence, information gathering,
            social engineering concepts, Python variables, loops, and file
            handling.
          </td>

        </tr>

        <tr>

          <td>9</td>

          <td>
            Python for Security and Reverse Engineering
          </td>

          <td>
            Application of Python for security automation, scanning, file
            analysis, and introduction to reverse engineering tools and
            assembly fundamentals.
          </td>

        </tr>

        <tr>

          <td>10</td>

          <td>
            Binary Analysis and Native Application Security
          </td>

          <td>
            Understanding compiled binaries, binary analysis, buffer
            overflow, integer vulnerabilities, and format string
            vulnerabilities.
          </td>

        </tr>

        <tr>

          <td>11</td>

          <td>
            Advanced and Network Forensics
          </td>

          <td>
            Study of data carving, memory analysis, network traffic capture,
            and analysis techniques for digital forensic investigations.
          </td>

        </tr>

        <tr>

          <td>12</td>

          <td>
            Cryptography and Hashing
          </td>

          <td>
            Introduction to cryptographic concepts, encryption techniques,
            digital security applications, and hashing algorithms.
          </td>

        </tr>

        <tr>

          <td>13</td>

          <td>
            Blockchain Security and Cybersecurity Law
          </td>

          <td>
            Introduction to ledger integrity, smart contract risks,
            cybersecurity laws, standards, compliance, and professional
            responsibilities.
          </td>

        </tr>

        <tr>

          <td>14</td>

          <td>
            Final Review and Examination
          </td>

          <td>
            Comprehensive review of cybersecurity, application security,
            authentication, digital forensics, cryptography, blockchain
            security, and cybersecurity law followed by the final examination.
          </td>

        </tr>

      </tbody>

    </table>

  </div>

</div>
--- 
---
layout: course

title: Cyber Security and Digital Forensic Laboratory

description: This laboratory course provides practical hands-on experience in cybersecurity, ethical hacking, penetration testing, and digital forensics. Students will work with Kali Linux, VMware, Burp Suite, DVWA, Ghidra, Autopsy, Volatility, and other security tools to investigate vulnerabilities, analyze attacks, and perform forensic investigations.

instructor: Md. Shakil Ahmed

year: 2026

term: Summer

importance: 2

---

<style>

/* =========================================================
   COURSE DETAIL PAGE
   WHITE / BLACK ACADEMIC STYLE
   ========================================================= */

.course-content,
.course-page {
  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  color: #111111;
}

/* =========================================================
   MAIN HEADINGS
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

/* =========================================================
   MAIN PAGE HEADING
   ========================================================= */

.course-content h1,
.course-page h1 {
  font-size: 26px;
  line-height: 1.4;
  margin-top: 0;
  margin-bottom: 20px;
}

/* =========================================================
   SECTION HEADINGS
   ========================================================= */

.course-content h2,
.course-page h2 {
  font-size: 27px;
  line-height: 1.4;
  margin-top: 34px;
  margin-bottom: 18px;
  padding-bottom: 8px;
  border-bottom: 2px solid #000000;
}

/* =========================================================
   SUBSECTION HEADINGS
   ========================================================= */

.course-content h3,
.course-page h3 {
  font-size: 22px;
  line-height: 1.45;
  margin-top: 25px;
  margin-bottom: 12px;
}

/* =========================================================
   SMALLER HEADINGS
   ========================================================= */

.course-content h4,
.course-page h4 {
  font-size: 19px;
  line-height: 1.45;
}

/* =========================================================
   PARAGRAPHS
   ========================================================= */

.course-content p,
.course-page p {
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

/* =========================================================
   STRONG / BOLD TEXT
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

.course-content li,
.course-page li {
  margin-bottom: 6px;
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
   COURSE CARDS
   ========================================================= */

.course-content .card,
.course-page .card {
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
.course-page .card:hover {
  transform: translateY(-3px);
  border-color: #999999;

  box-shadow:
    0 9px 22px rgba(0, 0, 0, 0.11);
}

/* =========================================================
   CARD BODY
   ========================================================= */

.course-content .card-body,
.course-page .card-body {
  padding: 22px;
}

/* =========================================================
   CARD TITLES
   ========================================================= */

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

/* =========================================================
   CARD TEXT
   ========================================================= */

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
   CODE / PRE
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
   HORIZONTAL DIVIDERS
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

  .course-content h1,
  .course-page h1 {
    font-size: 24px;
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
  .course-page p {
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

  .course-content h1,
  .course-page h1 {
    font-size: 21px;
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
  .course-page p {
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

  .course-content h1,
  .course-page h1 {
    font-size: 19px;
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
  .course-page p {
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

This laboratory course provides practical experience in cybersecurity, ethical hacking, penetration testing, and digital forensics. By the end of this course, students will be able to:

* Configure and use cybersecurity laboratory environments using Kali Linux, VMware, Burp Suite, and DVWA.

* Perform controlled web application security testing and identify common vulnerabilities.

* Apply Python scripting and security tools to practical cybersecurity tasks.

* Perform cryptographic, OSINT, reverse engineering, and binary analysis exercises.

* Use digital forensic tools and techniques for investigation and analysis.

* Apply ethical, legal, and safe practices when using cybersecurity tools.

## Prerequisites

* No prerequisites required.

## Textbooks

* **Primary:** *Kali Linux for Hackers: Exploring Tools, Exploits, and Vulnerabilities* by C. Campbell, Code Academy, 2024.

* **Reference:** *Cybersecurity Essentials* by Charles J. Brooks.

* **Reference:** *Guide to Computer Forensics and Investigations* by Bill Nelson.

* **Reference:** *Social Engineering: The Art of Human Hacking* by Christopher Hadnagy.

* **Reference:** *Black Hat Python: Python Programming for Hackers and Pentesters* by Justin Seitz and Tim Arnold.

* **Reference:** *Practical Reverse Engineering* by Bruce Dang and Alexandre Gazet.

* **Reference:** *Cybersecurity and Cyberlaw* by Pavan Duggal.

* **Reference:** *Cryptography and Network Security: Principles and Practice* by William Stallings.

## Grading

* **Class Participation:** 5%

* **Assignment/Presentation/Viva:** 10%

* **Class Test/Lab Performance:** 15%

* **Midterm Examination/Project Evaluation:** 30%

* **Final Examination/Project Evaluation:** 40%

**## Total: 100%**

schedule:

* week: 1

  date: Week 1

  topic: Cyber Security Laboratory Setup

  description: Introduction to the cybersecurity laboratory environment, VMware, Kali Linux installation, configuration, and basic security tools.

* week: 2

  date: Week 2

  topic: Burp Suite and DVWA

  description: Installation and configuration of Burp Suite and DVWA for practicing web application security testing in a controlled laboratory environment.

* week: 3

  date: Week 3

  topic: Web Server Attacks

  description: Practical study of web server concepts and controlled demonstrations of SQL injection, XSS, CSRF, clickjacking, and file upload vulnerabilities.

* week: 4

  date: Week 4

  topic: Python Scripting and Security Tasks

  description: Introduction to Python scripting for security tasks, port scanning, malware concepts, keylogger concepts, file upload vulnerabilities, and remote code execution in controlled laboratory environments.

* week: 5

  date: Week 5

  topic: Cryptography and Information Gathering

  description: Practical implementation of encryption and decryption algorithms, hashing algorithms, OSINT, Shodan, IP lookup, and information-gathering techniques.

* week: 6

  date: Week 6

  topic: Reverse Engineering and Binary Exploitation

  description: Introduction to reverse engineering using Ghidra and similar tools, with practical exercises on buffer overflow, stack overflow, and integer overflow vulnerabilities.

* week: 7

  date: Week 7

  topic: Cyber Law and Safe Cybersecurity Practice

  description: Understanding ethical and unethical use of cybersecurity tools and applying safe and responsible practices in cybersecurity laboratories.

* week: 8

  date: Week 8

  topic: Final Project and Practical Evaluation

  description: Practical project evaluation covering cybersecurity tools, ethical hacking techniques, security analysis, and digital forensic practices learned throughout the course.
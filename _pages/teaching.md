---
layout: page
permalink: /teaching/
title: Teaching
#description: Course materials, schedules, and resources for classes taught.
nav: true
nav_order: 4
---


<style>
  /* =========================================================
     TEACHING PAGE — WHITE / BLACK ACADEMIC STYLE
     ========================================================= */

  .teaching,
  .courses,
  .page-content {
    width: 100%;

    color: #111111;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 18px;
    line-height: 1.8;
  }

  /* =========================================================
     HEADINGS
     ========================================================= */

  .teaching h1,
  .teaching h2,
  .teaching h3,
  .courses h1,
  .courses h2,
  .courses h3,
  .course-title {
    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-weight: 700;
  }

  .teaching h1,
  .courses h1 {
    font-size: 32px;
  }

  .teaching h2,
  .courses h2 {
    font-size: 28px;
  }

  .teaching h3,
  .courses h3 {
    font-size: 22px;
  }

  /* =========================================================
     COURSE CONTAINER
     ========================================================= */

  .courses {
    max-width: 1000px;
    margin: 0 auto;
  }

  /* =========================================================
     COURSE CARDS
     ========================================================= */

  .course,
  .course-item,
  .courses .card {
    background: #ffffff !important;

    color: #111111 !important;

    border: 1px solid #d2d2d2;
    border-radius: 8px;

    padding: 24px 26px;
    margin-bottom: 20px;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.07);

    transition:
      transform 0.25s ease,
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .course:hover,
  .course-item:hover,
  .courses .card:hover {
    transform: translateY(-3px);

    border-color: #999999;

    box-shadow:
      0 10px 25px rgba(0, 0, 0, 0.13);
  }

  /* =========================================================
     COURSE TITLE
     ========================================================= */

  .course-title,
  .courses .card-title {
    margin-top: 0;
    margin-bottom: 10px;

    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-size: 21px;
    font-weight: 700;

    line-height: 1.45;
  }

  /* =========================================================
     COURSE DESCRIPTION
     ========================================================= */

  .course-subtitle,
  .course-desc,
  .course-meta,
  .courses .card-text {
    color: #222222 !important;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 16px;
    line-height: 1.75;

    text-align: justify;
    text-justify: inter-word;
  }

  /* Muted information */
  .courses .text-muted {
    color: #555555 !important;
  }

  /* =========================================================
     COURSE LINKS
     ========================================================= */

  .teaching a,
  .courses a {
    color: #000000 !important;

    text-decoration: underline;

    text-decoration-thickness: 1px;
    text-underline-offset: 3px;

    transition: opacity 0.2s ease;
  }

  .teaching a:hover,
  .courses a:hover {
    color: #000000 !important;
    opacity: 0.6;
  }

  /* =========================================================
     COURSE BUTTONS
     ========================================================= */

  .teaching .btn,
  .courses .btn {
    display: inline-flex;

    align-items: center;
    justify-content: center;

    padding: 8px 16px;

    background: #ffffff !important;
    color: #000000 !important;

    border: 1px solid #000000;
    border-radius: 5px;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 13px;
    font-weight: 600;

    text-decoration: none !important;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }

  .teaching .btn:hover,
  .courses .btn:hover {
    background: #000000 !important;
    color: #ffffff !important;

    border-color: #000000;

    transform: translateY(-2px);
  }

  /* =========================================================
     TAGS / BADGES
     ========================================================= */

  .teaching .badge,
  .courses .badge {
    display: inline-block;

    padding: 4px 9px;

    background: #f4f4f4 !important;
    color: #222222 !important;

    border: 1px solid #cccccc;
    border-radius: 4px;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 11px;
    font-weight: 600;
  }

  /* =========================================================
     CALENDAR
     ========================================================= */

  .calendar,
  #calendar {
    width: 100%;

    background: #ffffff !important;

    color: #111111 !important;

    border: 1px solid #d2d2d2;
    border-radius: 8px;

    padding: 18px;
    margin: 0 auto 30px;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.07);

    transition:
      box-shadow 0.25s ease,
      border-color 0.25s ease;
  }

  .calendar:hover,
  #calendar:hover {
    border-color: #999999;

    box-shadow:
      0 8px 22px rgba(0, 0, 0, 0.11);
  }

  /* Calendar text */
  .calendar *,
  #calendar * {
    color: #111111;
  }

  /* Calendar headings */
  .calendar h1,
  .calendar h2,
  .calendar h3,
  .calendar h4,
  #calendar h1,
  #calendar h2,
  #calendar h3,
  #calendar h4 {
    color: #000000 !important;

    font-family:
      Georgia,
      "Times New Roman",
      serif;

    font-weight: 700;
  }

  /* Calendar links */
  .calendar a,
  #calendar a {
    color: #000000 !important;
    text-decoration: underline;
  }

  /* =========================================================
     DIVIDERS
     ========================================================= */

  .teaching hr,
  .courses hr,
  hr,
  .divider {
    border: none;

    border-top: 2px solid #000000;

    margin: 30px auto;
  }

  /* =========================================================
     FOOTER
     ========================================================= */

  .site-footer {
    background: #ffffff !important;
    color: #111111 !important;

    border-top: 2px solid #000000;

    margin-top: 0;
    padding: 25px 0;
  }

  .site-footer p {
    margin: 0;

    color: #111111 !important;

    text-align: center;

    font-family: Arial, Helvetica, sans-serif;
    font-size: 14px;
    line-height: 1.5;
  }

  /* =========================================================
     TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .teaching,
    .courses {
      font-size: 17px;
    }

    .courses {
      padding-left: 20px;
      padding-right: 20px;
    }

    .course,
    .course-item,
    .courses .card {
      padding: 22px;
    }

    .course-title,
    .courses .card-title {
      font-size: 20px;
    }

    .course-subtitle,
    .course-desc,
    .course-meta,
    .courses .card-text {
      font-size: 15.5px;
    }
  }

  /* =========================================================
     MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .teaching,
    .courses {
      font-size: 17px;
      line-height: 1.75;
    }

    .courses {
      padding-left: 15px;
      padding-right: 15px;
    }

    .course,
    .course-item,
    .courses .card {
      padding: 20px;
      margin-bottom: 18px;

      border-radius: 7px;
    }

    .course-title,
    .courses .card-title {
      font-size: 19px;
    }

    .course-subtitle,
    .course-desc,
    .course-meta,
    .courses .card-text {
      font-size: 15px;
      line-height: 1.7;

      text-align: left;
    }

    .calendar,
    #calendar {
      padding: 12px;
      margin-bottom: 22px;
    }
  }

  /* =========================================================
     SMALL MOBILE
     ========================================================= */

  @media (max-width: 480px) {

    .courses {
      padding-left: 10px;
      padding-right: 10px;
    }

    .course,
    .course-item,
    .courses .card {
      padding: 17px;
      margin-bottom: 15px;
    }

    .course-title,
    .courses .card-title {
      font-size: 18px;
    }

    .course-subtitle,
    .course-desc,
    .course-meta,
    .courses .card-text {
      font-size: 14.5px;
    }

    .teaching .btn,
    .courses .btn {
      font-size: 12px;
      padding: 7px 13px;
    }

    .site-footer {
      padding: 22px 0;
    }
  }
</style>

{% include calendar.liquid calendar_id='test@gmail.com' timezone='Asia/Shanghai' %}

{% include courses.liquid %}

<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>

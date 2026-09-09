---
layout: page
title: Bangladeshi Sign Language Detection
description: A YOLOv10-based system for recognizing static Bangladeshi Sign Language gestures and translating them into text.
img: assets/img/sign_language.jpg
importance: 5
category: work
related_publications: false
---
<style>
  /* =========================================================
     PROJECT DETAIL PAGE
     WHITE / BLACK ACADEMIC STYLE
     ========================================================= */

  .project-card,
  .project-content {
    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    color: #111111;
  }

  /* =========================================================
     MAIN PROJECT HEADER CARD
     ========================================================= */

  .project-card {
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

  .project-card:hover {
    border-color: #999999;

    box-shadow:
      0 10px 26px rgba(0, 0, 0, 0.12);
  }

  /* =========================================================
     PROJECT HEADER
     ========================================================= */

  .project-header {
    display: flex;
    align-items: center;

    gap: 16px;

    margin-bottom: 18px;
  }

  .project-icon {
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

  .project-title {
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

  .project-subtitle {
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
     PROJECT DESCRIPTION
     ========================================================= */

  .project-description {
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

  .project-description strong {
    color: #000000;
    font-weight: 700;
  }

  /* =========================================================
     PROJECT TAGS
     ========================================================= */

  .project-tags {
    display: flex;
    flex-wrap: wrap;

    gap: 8px;

    margin-top: 20px;
  }

  .project-tag {
    display: inline-block;

    padding: 5px 10px;

    background: #f4f4f4;

    border: 1px solid #cccccc;
    border-radius: 4px;

    color: #222222;

    font-family: Arial, Helvetica, sans-serif;

    font-size: 12px;
    font-weight: 600;

    line-height: 1.4;
  }

  /* =========================================================
     PROJECT BUTTONS
     ========================================================= */

  .project-buttons {
    display: flex;
    flex-wrap: wrap;

    gap: 10px;

    margin-top: 22px;
  }

  .project-button {
    display: inline-flex;

    align-items: center;
    justify-content: center;

    gap: 8px;

    padding: 9px 17px;

    background: #ffffff;

    border: 1px solid #000000;
    border-radius: 5px;

    color: #000000 !important;

    font-family: Arial, Helvetica, sans-serif;

    font-size: 13px;
    font-weight: 600;

    line-height: 1.4;

    text-decoration: none !important;

    transition:
      background-color 0.2s ease,
      color 0.2s ease,
      transform 0.2s ease;
  }

  .project-button:hover {
    background: #000000;

    color: #ffffff !important;

    border-color: #000000;

    transform: translateY(-2px);

    text-decoration: none !important;
  }

  .project-button.primary,
  .project-button.secondary {
    background: #ffffff;
    color: #000000 !important;
  }

  .project-button.primary:hover,
  .project-button.secondary:hover {
    background: #000000;
    color: #ffffff !important;
  }

  /* =========================================================
     PROJECT CONTENT
     ========================================================= */

  .project-content {
    max-width: 1000px;

    margin: 0 auto;

    color: #111111;
  }

  .project-content p {
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

  .project-content strong {
    color: #000000;
    font-weight: 700;
  }

  /* =========================================================
     SECTION HEADINGS
     ========================================================= */

  .project-section-title {
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

  .project-content .card,
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

  .project-content .card:hover,
  .feature-card:hover {
    transform: translateY(-3px);

    border-color: #999999;

    box-shadow:
      0 9px 22px rgba(0, 0, 0, 0.11);
  }

  .project-content .card-body {
    padding: 22px;
  }

  /* =========================================================
     CARD TITLES
     ========================================================= */

  .project-content .card-title {
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

  .project-content .card-title i {
    margin-right: 7px;

    color: #000000;
  }

  /* =========================================================
     CARD TEXT
     ========================================================= */

  .project-content .card-text {
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

  .project-content ul {
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

  .project-content li {
    margin-bottom: 6px;
  }

  .project-content li strong {
    color: #000000;
  }

  /* =========================================================
     IMAGES
     ========================================================= */

  .project-content img {
    border: 1px solid #d2d2d2;

    box-shadow:
      0 4px 14px rgba(0, 0, 0, 0.08);

    border-radius: 6px;
  }

  .caption {
    margin-top: 10px;
    margin-bottom: 20px;

    color: #555555;

    font-family:
      "Source Serif 4",
      Georgia,
      "Times New Roman",
      serif;

    font-size: 14px;

    line-height: 1.6;

    text-align: center;

    font-style: italic;
  }

  /* =========================================================
     TABLES
     ========================================================= */

  .project-content .table {
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

  .project-content .table th {
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

  .project-content .table td {
    padding: 10px 14px;

    background: #ffffff;

    color: #222222;

    border: 1px solid #d2d2d2;

    vertical-align: top;
  }

  .project-content .table tbody tr:hover td {
    background: #f8f8f8;
  }

  /* =========================================================
     GENERAL LINKS
     ========================================================= */

  .project-content a {
    color: #000000 !important;

    text-decoration: underline;

    text-decoration-thickness: 1px;
    text-underline-offset: 3px;
  }

  .project-content a:hover {
    color: #000000 !important;
    opacity: 0.6;
  }

  /* =========================================================
     RESPONSIVE — TABLET
     ========================================================= */

  @media (max-width: 900px) {

    .project-card {
      margin-left: 20px;
      margin-right: 20px;

      padding: 25px;
    }

    .project-content {
      padding-left: 20px;
      padding-right: 20px;
    }

    .project-title {
      font-size: 24px;
    }

    .project-content p {
      font-size: 16px;
    }

    .project-section-title {
      font-size: 25px;
    }
  }

  /* =========================================================
     RESPONSIVE — MOBILE
     ========================================================= */

  @media (max-width: 768px) {

    .project-card {
      margin: 15px 15px 30px;

      padding: 21px;

      border-radius: 7px;
    }

    .project-header {
      gap: 12px;
    }

    .project-icon {
      width: 52px;
      height: 52px;

      font-size: 25px;
    }

    .project-title {
      font-size: 21px;
    }

    .project-subtitle {
      font-size: 14px;
    }

    .project-description {
      font-size: 15px;

      line-height: 1.75;

      text-align: left;
    }

    .project-content {
      padding-left: 15px;
      padding-right: 15px;
    }

    .project-content p {
      font-size: 15.5px;

      line-height: 1.75;

      text-align: left;
    }

    .project-section-title {
      margin-top: 30px;

      font-size: 23px;
    }

    .project-content .card-title {
      font-size: 18px;
    }

    .project-content .card-text {
      font-size: 15px;

      text-align: left;
    }

    .project-content ul {
      font-size: 15px;
    }

    .project-content .table {
      font-size: 14px;
    }

    .project-content .table th,
    .project-content .table td {
      padding: 9px 10px;
    }
  }

  /* =========================================================
     RESPONSIVE — SMALL MOBILE
     ========================================================= */

  @media (max-width: 576px) {

    .project-card {
      margin-left: 10px;
      margin-right: 10px;

      padding: 18px;
    }

    .project-header {
      align-items: flex-start;
    }

    .project-icon {
      width: 46px;
      height: 46px;

      font-size: 22px;
    }

    .project-title {
      font-size: 19px;
    }

    .project-subtitle {
      font-size: 13.5px;
    }

    .project-description {
      font-size: 14px;
    }

    .project-tags {
      gap: 6px;
    }

    .project-tag {
      font-size: 11px;
      padding: 5px 8px;
    }

    .project-button {
      padding: 8px 13px;

      font-size: 12px;
    }

    .project-content {
      padding-left: 10px;
      padding-right: 10px;
    }

    .project-section-title {
      font-size: 21px;
    }

    .caption {
      font-size: 13px;
    }

    .project-content .table {
      font-size: 13px;
    }
  }
</style>
<div class="project-card">

  <div class="project-header">

    <div class="project-icon">
      <i class="fas fa-hands"></i>
    </div>

    <div>
      <h1 class="project-title">
        Bangladeshi Sign Language Detection
      </h1>

      <p class="project-subtitle">
        A YOLOv10-based system for recognizing static Bangladeshi Sign Language
        gestures and translating them into text.
      </p>
    </div>

  </div>

  <div class="project-description">

    Developed a <strong>Bangladeshi Sign Language (BdSL) Detection System</strong>
    to help bridge communication barriers faced by deaf and mute individuals.
    The system recognizes static Bangladeshi Sign Language hand gestures and
    translates them into text, supporting more inclusive and accessible
    communication.

    The proposed approach leverages <strong>YOLOv10</strong>, a
    state-of-the-art object detection model, trained on a custom dataset of
    labeled BdSL gesture images. The model was designed to provide accurate
    and efficient recognition of <strong>14 unique static signs</strong>.

  </div>

  <div class="project-tags">
    <span class="project-tag">YOLOv10</span>
    <span class="project-tag">Python</span>
    <span class="project-tag">Computer Vision</span>
    <span class="project-tag">Deep Learning</span>
    <span class="project-tag">Object Detection</span>
    <span class="project-tag">Sign Language Recognition</span>
    <span class="project-tag">Bangladeshi Sign Language</span>
    <span class="project-tag">14 Static Signs</span>
    <span class="project-tag">Custom Dataset</span>
    <span class="project-tag">Text Translation</span>
  </div>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/SIGN_LANGUAGE_DETECTION"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      View Code
    </a>

  </div>

</div>

<div class="project-content">

  <h2 class="project-section-title">
    Project Overview
  </h2>

  <p>
    There is a critical need for accurate Bangladeshi Sign Language (BdSL)
    detection systems to create a more inclusive environment for people who
    are deaf and mute. Communication barriers can contribute to social
    isolation and limit access to education, services, and everyday
    interactions.
  </p>

  <p>
    This project proposes a computer vision-based system that recognizes
    Bangladeshi Sign Language hand gestures and translates them into text.
    By facilitating communication between sign language users and others,
    the system aims to reduce communication barriers and support greater
    social inclusion.
  </p>

  <p>
    The proposed method uses <strong>YOLOv10</strong>, a state-of-the-art
    object detection model, to achieve accurate and efficient BdSL gesture
    recognition. A custom dataset of <strong>1,949 labeled images</strong>
    covering <strong>14 unique static signs</strong> was used to train and
    evaluate the model.
  </p>

  <h2 class="project-section-title">
    Methodology
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-database"></i>
            Custom Dataset
          </h4>

          <p class="card-text">
            A curated dataset of 1,949 labeled images representing
            14 unique static Bangladeshi Sign Language gestures.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-brain"></i>
            YOLOv10 Model
          </h4>

          <p class="card-text">
            A custom YOLOv10 object detection model trained to identify
            and recognize static BdSL hand gestures.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-cogs"></i>
            Model Training
          </h4>

          <p class="card-text">
            The model was trained on labeled gesture images to improve
            recognition accuracy and robustness across the selected signs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-language"></i>
            Text Translation
          </h4>

          <p class="card-text">
            Recognized hand gestures are translated into text to support
            communication between sign language users and others.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    System Workflow
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-camera"></i>
            1. Input Image
          </h4>

          <p class="card-text">
            A hand gesture image is provided as input to the detection system.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-search"></i>
            2. Gesture Detection
          </h4>

          <p class="card-text">
            The trained YOLOv10 model detects the hand gesture and identifies
            the corresponding sign class.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-check-circle"></i>
            3. Sign Recognition
          </h4>

          <p class="card-text">
            The detected gesture is classified into one of the 14 supported
            Bangladeshi Sign Language signs.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-comment-alt"></i>
            4. Text Output
          </h4>

          <p class="card-text">
            The recognized sign is converted into text to facilitate
            communication.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    Dataset and Model Details
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
          <td>Project Type</td>
          <td>Computer Vision and Sign Language Recognition</td>
        </tr>

        <tr>
          <td>Model</td>
          <td>YOLOv10</td>
        </tr>

        <tr>
          <td>Dataset</td>
          <td>Custom labeled Bangladeshi Sign Language dataset</td>
        </tr>

        <tr>
          <td>Total Images</td>
          <td>1,949</td>
        </tr>

        <tr>
          <td>Number of Signs</td>
          <td>14 unique static signs</td>
        </tr>

        <tr>
          <td>Recognition Type</td>
          <td>Static hand gesture detection</td>
        </tr>

        <tr>
          <td>Output</td>
          <td>Recognized sign translated into text</td>
        </tr>

        <tr>
          <td>Primary Objective</td>
          <td>Bridging communication barriers through BdSL recognition</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Performance Results
  </h2>

  <p>
    The proposed method was evaluated on the custom dataset containing
    1,949 images of 14 unique signs. The model achieved the following
    performance across all classes.
  </p>

  <div class="table-responsive">

    <table class="table table-bordered">

      <thead>
        <tr>
          <th>Metric</th>
          <th>Performance</th>
        </tr>
      </thead>

      <tbody>

        <tr>
          <td>F1-Confidence Rate</td>
          <td>86%</td>
        </tr>

        <tr>
          <td>Recall-Confidence Rate</td>
          <td>98%</td>
        </tr>

        <tr>
          <td>Precision-Confidence Rate</td>
          <td>100%</td>
        </tr>

        <tr>
          <td>Precision-Recall Rate</td>
          <td>90.3%</td>
        </tr>

        <tr>
          <td>Overall Average Accuracy</td>
          <td>90.67%</td>
        </tr>

      </tbody>

    </table>

  </div>

  <h2 class="project-section-title">
    Key Contributions
  </h2>

  <ul>

    <li>
      <strong>Inclusive Communication:</strong>
      Develops a system intended to reduce communication barriers faced by
      deaf and mute individuals.
    </li>

    <li>
      <strong>YOLOv10-Based Detection:</strong>
      Applies a state-of-the-art object detection model to Bangladeshi
      Sign Language recognition.
    </li>

    <li>
      <strong>Custom Dataset:</strong>
      Uses a curated dataset of 1,949 labeled images covering 14 unique
      static signs.
    </li>

    <li>
      <strong>Accurate Recognition:</strong>
      Achieves an overall average accuracy of 90.67% across the supported
      signs.
    </li>

    <li>
      <strong>Practical Application:</strong>
      Provides a foundation for developing accessible sign language
      communication tools.
    </li>

  </ul>

  <h2 class="project-section-title">
    Social Impact
  </h2>

  <p>
    This project aims to contribute to a more inclusive society by
    addressing communication barriers faced by people who rely on
    Bangladeshi Sign Language. By translating hand gestures into text,
    the system has the potential to improve everyday communication,
    reduce social isolation, and support greater participation in
    education, employment, and community activities.
  </p>

  <p>
    The research also contributes to the development of sign language
    recognition technology and provides a foundation for future systems
    capable of supporting a wider range of gestures and real-time
    communication scenarios.
  </p>

  <h2 class="project-section-title">
    Future Improvements
  </h2>

  <div class="row">

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-video"></i>
            Real-Time Recognition
          </h4>

          <p class="card-text">
            Extend the system to support real-time gesture recognition
            through video input and live camera streams.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-expand-arrows-alt"></i>
            Expanded Sign Vocabulary
          </h4>

          <p class="card-text">
            Increase the number of supported signs to improve the coverage
            of Bangladeshi Sign Language.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-language"></i>
            Sentence-Level Translation
          </h4>

          <p class="card-text">
            Extend the system from individual static signs to continuous
            gesture sequences and sentence-level translation.
          </p>

        </div>
      </div>
    </div>

    <div class="col-md-6 mt-3">
      <div class="card h-100 feature-card">
        <div class="card-body">

          <h4 class="card-title">
            <i class="fas fa-mobile-alt"></i>
            Mobile Accessibility
          </h4>

          <p class="card-text">
            Develop a mobile-friendly application to make the recognition
            system more accessible for everyday use.
          </p>

        </div>
      </div>
    </div>

  </div>

  <h2 class="project-section-title">
    Project Highlights
  </h2>

  <p>
    This project demonstrates practical experience in
    <strong>deep learning, computer vision, object detection, custom dataset
    development, YOLOv10 model training, and sign language recognition</strong>.
    It combines technical innovation with a socially meaningful objective:
    improving communication accessibility for people who rely on
    Bangladeshi Sign Language.
  </p>

  <h2 class="project-section-title">
    GitHub Repository
  </h2>

  <p>
    The complete source code of the project is available in the GitHub
    repository.
  </p>

  <div class="project-buttons">

    <a
      href="https://github.com/shakil2022/SIGN_LANGUAGE_DETECTION"
      class="project-button primary"
      target="_blank"
      rel="noopener noreferrer"
    >
      <i class="fab fa-github"></i>
      GitHub Repository
    </a>

  </div>

</div>
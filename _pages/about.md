---
layout: about
title: About
permalink: /
subtitle: >
  <a href="https://bubt.edu.bd/department/department-of-computer-science-engineering/faculty/profile/MDSHA">
  Lecturer</a>, Department of Computer Science and Engineering,
  Bangladesh University of Business and Technology

profile:
  align: left
  image: prof_pic.jpg
  image_circular: false
  more_info: >

social: true 

announcements:
  enabled: false # includes a list of news items
  scrollable: false # adds a vertical scroll bar if there are more than 3 news items
  limit: 0 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: false # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 0 # leave blank to include all the blog posts
---
<style>

/* =========================================================
   GLOBAL DESIGN
   Clean academic portfolio:
   White background + black typography only
   ========================================================= */

:root {
  --page-bg: #ffffff;
  --text-main: #111111;
  --text-secondary: #333333;
  --text-muted: #555555;
  --border-color: #d9d9d9;
  --card-bg: #ffffff;
}


/* =========================================================
   GLOBAL RESET
   ========================================================= */

* {
  box-sizing: border-box;
}

html,
body {
  margin: 0;
  padding: 0;
}


/* =========================================================
   PAGE TYPOGRAPHY
   ========================================================= */

body {
  background: #ffffff !important;
  color: #111111 !important;

  /*
    Professional academic typography.
    Georgia provides a natural and readable appearance
    for long-form academic content.
  */
  font-family:
    "Source Serif 4",
    Georgia,
    "Times New Roman",
    serif;

  font-size: 18px;
  line-height: 1.85;
  font-weight: 400;
}


/* =========================================================
   MAIN CONTENT
   ========================================================= */

.post,
.post-content,
.about,
.container {
  color: #111111;
}


/*
  Introductory biography paragraphs
*/

.post p,
.post-content p,
.about p {
  font-size: 18px;
  line-height: 1.85;
  color: #111111;

  text-align: justify;
  text-justify: inter-word;

  margin-bottom: 22px;
}


/* =========================================================
   HEADINGS
   Keep heading size unchanged / professional
   ========================================================= */

h1,
h2,
h3,
h4,
h5,
h6 {
  color: #000000 !important;

  font-family:
    Georgia,
    "Times New Roman",
    serif;

  font-weight: 700;
}


/*
  Section headings
*/

.education-section h2,
.section-block h2 {
  text-align: center;

  font-family:
    Georgia,
    "Times New Roman",
    serif;

  font-weight: 700;
  font-size: 32px;

  color: #000000;

  margin: 0 0 42px;
}


/* =========================================================
   LINKS
   Black only
   ========================================================= */

a {
  color: #000000 !important;

  text-decoration: underline;

  text-decoration-thickness: 1px;
  text-underline-offset: 3px;

  transition: opacity 0.2s ease;
}

a:hover {
  color: #000000 !important;
  opacity: 0.65;
}


/* =========================================================
   STRONG AND EMPHASIS
   ========================================================= */

strong {
  color: #000000;
  font-weight: 700;
}

em {
  color: #111111;
}


/* =========================================================
   HORIZONTAL DIVIDERS
   ========================================================= */

.divider-line {
  width: 100%;
  max-width: 900px;

  margin: 60px auto;

  border: none;
  border-top: 1px solid #cccccc;
}


/* =========================================================
   RESEARCH INTERESTS
   ========================================================= */

.research-interests {
  max-width: 900px;

  margin: 0 auto;

  padding: 50px 24px;

  text-align: center;
}


.research-interests h2 {
  font-family:
    Georgia,
    "Times New Roman",
    serif;

  font-size: 32px;

  font-weight: 700;

  color: #000000;

  margin: 0 0 28px;
}


/*
  Research interest tags
*/

.interest-tags {
  display: flex;

  flex-wrap: wrap;

  justify-content: center;

  gap: 12px;
}


.interest-tag {
  display: inline-flex;

  align-items: center;

  justify-content: center;

  padding: 8px 16px;

  border: 1px solid #000000;

  border-radius: 4px;

  background: #ffffff;

  color: #000000;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 14px;

  font-weight: 500;

  line-height: 1.4;

  white-space: nowrap;

  transition: all 0.2s ease;
}


.interest-tag:hover {
  background: #f5f5f5;

  color: #000000;
}


/* =========================================================
   EDUCATION SECTION
   ========================================================= */

.education-section {
  background: #ffffff;

  padding: 56px 24px 70px;
}


.timeline {
  max-width: 900px;

  margin: 0 auto;

  display: flex;

  flex-direction: column;

  gap: 20px;
}


/*
  Education cards
*/

.edu-card {
  background: #ffffff;

  border: 1px solid #d0d0d0;

  border-radius: 0;

  padding: 24px 28px;

  display: flex;

  justify-content: space-between;

  align-items: flex-start;

  gap: 30px;

  flex-wrap: wrap;
}


.edu-main {
  flex: 1;

  min-width: 240px;

  text-align: left;
}


/*
  University / institution
*/

.edu-school {
  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 18px;

  font-weight: 700;

  color: #000000;

  margin: 0 0 6px;
}


/*
  Degree
*/

.edu-degree {
  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 16px;

  font-weight: 500;

  color: #111111;

  margin: 0;
}


/*
  Thesis
*/

.edu-note {
  font-size: 16px;

  line-height: 1.7;

  color: #333333;

  margin: 12px 0 0;

  font-style: italic;

  text-align: justify;
}


/*
  Location and date
*/

.edu-side {
  text-align: right;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 15px;

  color: #222222;

  flex: none;
}


.edu-loc {
  font-weight: 600;

  color: #000000;
}


.edu-date {
  margin-top: 5px;
}


/*
  School grouping
*/

.edu-school-group {
  margin-bottom: 4px;
}


.edu-sub {
  margin: 14px 0 0;

  padding-top: 14px;

  border-top: 1px solid #dddddd;
}


.edu-sub:first-of-type {
  margin-top: 10px;

  padding-top: 0;

  border-top: none;
}


/* =========================================================
   GENERAL SECTIONS
   ========================================================= */

.section-block {
  max-width: 100%;

  padding: 56px 24px;

  background: #ffffff;
}


.cert-list {
  max-width: 900px;

  margin: 0 auto;

  display: flex;

  flex-direction: column;

  gap: 26px;
}


/* =========================================================
   HONORS / CERTIFICATIONS / ACTIVITIES
   ========================================================= */

.cert-item {
  display: flex;

  justify-content: space-between;

  align-items: flex-start;

  gap: 30px;

  flex-wrap: wrap;

  padding-bottom: 24px;

  border-bottom: 1px solid #dddddd;
}


.cert-item:last-child {
  border-bottom: none;
}


.cert-main {
  flex: 1;

  min-width: 240px;

  text-align: left;
}


/*
  Item title
*/

.cert-name {
  margin: 0 0 8px;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 18px;

  font-weight: 700;

  color: #000000;
}


.cert-name a {
  color: #000000 !important;
}


/*
  Description
*/

.cert-desc {
  margin: 0;

  font-size: 17px;

  line-height: 1.8;

  color: #222222;

  text-align: justify;
}


/*
  Date
*/

.cert-date {
  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 15px;

  font-weight: 500;

  color: #222222;

  flex: none;

  white-space: nowrap;

  text-align: right;
}


/* =========================================================
   TECHNICAL SKILLS
   ========================================================= */

.skills-list {
  max-width: 900px;

  margin: 0 auto;

  display: grid;

  grid-template-columns: repeat(2, 1fr);

  gap: 22px;
}


/*
  Skill cards
*/

.skill-item {
  background: #ffffff;

  border: 1px solid #cccccc;

  border-radius: 0;

  padding: 26px;

  transition:
    transform 0.2s ease,
    box-shadow 0.2s ease;
}


.skill-item:hover {
  transform: translateY(-3px);

  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.08);
}


/*
  Skill category
*/

.skill-name {
  margin: 0 0 12px;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  color: #000000;

  font-weight: 700;

  font-size: 18px;
}


/*
  Skill description
*/

.skill-desc {
  margin: 0;

  font-size: 16px;

  line-height: 1.8;

  color: #222222;

  text-align: justify;
}


/* =========================================================
   FOOTER
   ========================================================= */

.site-footer {
  background: #ffffff !important;

  color: #111111 !important;

  border-top: 1px solid #cccccc;

  margin-top: 50px;

  padding: 28px 0;
}


.site-footer p {
  margin: 0;

  color: #111111 !important;

  text-align: center;

  font-family:
    Arial,
    Helvetica,
    sans-serif;

  font-size: 14px;
}


/* =========================================================
   MOBILE RESPONSIVE DESIGN
   ========================================================= */

@media (max-width: 768px) {

  body {
    font-size: 17px;
  }


  .post p,
  .post-content p,
  .about p {
    font-size: 17px;

    line-height: 1.8;

    text-align: left;
  }


  .education-section h2,
  .section-block h2,
  .research-interests h2 {
    font-size: 28px;
  }


  .edu-card {
    flex-direction: column;

    gap: 16px;

    padding: 22px;
  }


  .edu-side {
    text-align: left;
  }


  .cert-item {
    flex-direction: column;

    gap: 10px;
  }


  .cert-date {
    text-align: left;
  }


  .skills-list {
    grid-template-columns: 1fr;
  }


  .skill-item {
    padding: 22px;
  }


  .interest-tag {
    font-size: 13px;

    padding: 7px 13px;
  }
}


@media (max-width: 480px) {

  .section-block,
  .education-section,
  .research-interests {
    padding-left: 18px;

    padding-right: 18px;
  }


  .education-section h2,
  .section-block h2,
  .research-interests h2 {
    font-size: 25px;
  }


  .post p,
  .post-content p,
  .about p {
    font-size: 16px;
  }

}

</style>

<p>
I am a machine learning researcher and
<a href="https://bubt.edu.bd/department/department-of-computer-science-engineering/faculty/profile/MDSHA">
Lecturer
</a>
in the Department of Computer Science and Engineering at the
<a href="https://bubt.edu.bd/">
Bangladesh University of Business and Technology (BUBT)
</a>.
I have completed my M.Sc. and B.Sc. degree in Information and Communication Technology at the
<a href="https://iitju.edu.bd/">
Institute of Information Technology, Jahangirnagar University
</a>.
My research interests lie at the intersection of
<strong>Federated Learning, Cyber Security, Artificial Intelligence, Machine Learning, Image Processing, and Computer Vision</strong>.
</p>

<p>
My current research focuses on developing
<strong>privacy-preserving, data-efficient, and reliable machine learning systems</strong>,
particularly for healthcare applications. As part of my M.Sc. research, I worked on federated semi-supervised learning for Parkinson's disease classification, with an emphasis on learning effectively from limited labeled data while preserving data privacy.
This research was supported by the
<a href="https://ims.ictd.gov.bd/">
ICT Division Fellowship 2025–2026
</a>,
with the project titled
<em>FEP-SSL: A Privacy-Preserving Semi-Supervised Learning Framework for Parkinson's Disease Classification</em>.
</p>

<p>
My research journey began with
<strong>computer vision and deep learning</strong>,
including work on real-time Bangla Sign Language detection and recognition using YOLOv10 and medical image analysis.
Under the supervision and guidance of
<a href="https://juniv.edu/teachers/mskaiser">
<strong>Professor Dr. M. Shamim Kaiser</strong>
</a>
at the Institute of Information Technology, Jahangirnagar University, I expanded my research toward
<strong>privacy-preserving, explainable, and data-efficient machine learning</strong>,
with a particular focus on federated learning and healthcare AI.
</p>

<p>
My research includes Cleanlab-guided uncertainty-based active learning for Parkinson's disease classification and privacy-preserving federated semi-supervised learning, addressing challenges related to limited labeled data and privacy-sensitive healthcare applications.
</p>

<p>
Alongside research, I am passionate about
<strong>teaching and mentoring students in computer science and engineering</strong>.
I have worked as a Lecturer at the
<a href="https://bubt.edu.bd/">
Bangladesh University of Business and Technology (BUBT)
</a>,
<a href="https://www.cub.edu.bd/">
Canadian University of Bangladesh (CUB)
</a>,
and
<a href="https://daffodilvarsity.edu.bd/">
Daffodil International University (DIU)
</a>.
I previously served as a Teaching Assistant and Research Assistant at
<a href="https://juniv.edu/">
Jahangirnagar University
</a>.
These experiences have allowed me to combine academic teaching with hands-on research and contribute to the development of students in areas related to computing and artificial intelligence.
</p>


<hr class="divider-line">
<!-- ==================== RESEARCH INTERESTS ==================== -->

<section class="research-interests">

  <h2>Research Interests</h2>

  <div class="interest-tags">

    <span class="interest-tag">
      Federated Learning
    </span>

    <span class="interest-tag">
      Cyber Security
    </span>

    <span class="interest-tag">
      Privacy Privacy
    </span>

    <span class="interest-tag">
      Artificial Intelligence
    </span>

    <span class="interest-tag">
      Semi-supervised Learning
    </span>

    <span class="interest-tag">
      Machine Learning
    </span>

    <span class="interest-tag">
      Image Processing
    </span>

    <span class="interest-tag">
      Computer Vision
    </span>


  </div>

</section>


<hr class="divider-line">
<section class="education-section">
  <h2>Education</h2>

  <div class="timeline">

    <!-- M.Sc. -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">
          Institute of Information Technology, Jahangirnagar University
        </p>

        <a href="https://drive.google.com/file/d/16aIfdCM5Bt0XjIWH47rDqLdmt9idpkE6/view?usp=drive_link"
           target="_blank"
           rel="noopener noreferrer">
          <p class="edu-degree">
            M.Sc. in ICT; CGPA: 3.75/4.0
          </p>
        </a>

        <p class="edu-note">
          Thesis (M.Sc.): FEP-SSL: A Privacy-Preserving Semi-Supervised
          Learning Framework for Parkinson's Disease Classification
        </p>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Oct 2024 – Sep 2026</div>
      </div>
    </div>


    <!-- B.Sc. -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school">
          Institute of Information Technology, Jahangirnagar University
        </p>

        <a href="https://drive.google.com/file/d/1NFqiSCK6Hg0eh4tgNG9K6_tdsR3Nj4PQ/view?usp=sharing"
           target="_blank"
           rel="noopener noreferrer">
          <p class="edu-degree">
            B.Sc. in ICT; CGPA: 3.86/4.0 (4th position)
          </p>
        </a>

        <p class="edu-note">
          Thesis (B.Sc.): Real-Time Bangla Sign Language Detection and
          Recognition Using YOLOv10
        </p>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dhaka, Bangladesh</div>
        <div class="edu-date">Feb 2019 – Sep 2024</div>
      </div>
    </div>


    <!-- HSC -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school edu-school-group">
          Dinajpur Govt. College
        </p>

        <div class="edu-sub">
          <a href="https://drive.google.com/file/d/1T-4sbylCgV18rKrN6SyuCOFDP0s2rs72/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            <p class="edu-degree">
              Higher Secondary Certificate (HSC); Science; GPA: 5.0/5.0
            </p>
          </a>
        </div>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dinajpur, Bangladesh</div>
        <div class="edu-date">2016 – 2018</div>
      </div>
    </div>


    <!-- SSC -->
    <div class="edu-card">
      <div class="edu-main">
        <p class="edu-school edu-school-group">
          Panchkur B\L High School
        </p>

        <div class="edu-sub">
          <a href="https://drive.google.com/file/d/1osWGSHjY9RAbxn_ifhFAzW8Vd_ujt1VT/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            <p class="edu-degree">
              Secondary School Certificate (SSC); Science; GPA: 5.0/5.0
            </p>
          </a>
        </div>
      </div>

      <div class="edu-side">
        <div class="edu-loc">Dinajpur, Bangladesh</div>
        <div class="edu-date">2014 – 2016</div>
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">

<!-- ==================== HONORS AND AWARDS ==================== -->

<section class="section-block">
  <h2>Honors and Awards</h2>

  <div class="cert-list">

    <!-- ICT Division Fellowship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1lCtDA3zSwH3vj1NPrKfoYh6sfrPSHMLz/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Information and Communication Technology (ICT) Division Fellowship
          </a>
        </p>

        <p class="cert-desc">
          Awarded the ICT Division Fellowship for the 2025–2026 academic
          session for research on
          <em>“FEP-SSL: A Privacy-Preserving Semi-Supervised Learning
          Framework for Parkinson’s Disease Classification.”</em>
        </p>
      </div>

      <div class="cert-date">
        2025 – 2026
      </div>
    </div>


    <!-- NST Fellowship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1ukv5D60qS6wI1gxfXyz6FpkMQ_HyA47a/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            National Science and Technology (NST) Fellowship
          </a>
        </p>

        <p class="cert-desc">
          Awarded the National Science and Technology (NST) Fellowship
          for the 2025–2026 academic session for research on
          <em>“Privacy-Preserving Federated Semi-Supervised Learning
          Model for Healthcare Applications.”</em>
        </p>
      </div>

      <div class="cert-date">
        2025 – 2026
      </div>
    </div>


    <!-- University Merit Scholarship -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://juniv.edu/"
             target="_blank"
             rel="noopener noreferrer">
            University Merit Scholarship
          </a>
        </p>

        <p class="cert-desc">
          Awarded a university merit scholarship for outstanding
          academic performance in the B.Sc. (Hons.) in ICT program,
          covering academic results from Part I to Part VIII at the
          Institute of Information Technology, Jahangirnagar University.
        </p>
      </div>

      <div class="cert-date">
        2019 – 2024
      </div>
    </div>


    <!-- IEEEXtreme -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_IEEEXTREME_LINK"
             target="_blank"
             rel="noopener noreferrer">
            IEEEXtreme 14.0 Programming Contest
          </a>
        </p>

        <p class="cert-desc">
          Participated in the IEEEXtreme 14.0 programming contest
          organized by IEEE in 2021. My team,
          <em>“JUinception,”</em> ranked
          <strong>498th out of 2,155 teams worldwide</strong> and secured
          <strong>11th position in Bangladesh</strong>.
        </p>
      </div>

      <div class="cert-date">
        2021
      </div>
    </div>


    <!-- Dementia Workshop -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DEMENTIA_WORKSHOP_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Workshop on Early Detection and Management of Dementia
            using Explainable Artificial Intelligence
          </a>
        </p>

        <p class="cert-desc">
          Participating member in the workshop
          <em>“Early Detection and Management of Dementia using
          Explainable Artificial Intelligence,”</em> awarded by
          Nottingham Trent University, England.
        </p>
      </div>
    </div>


    <!-- Debate Finalist -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DEBATE_FINALIST_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Debate Finalist
          </a>
        </p>

        <p class="cert-desc">
          Achieved finalist status in a debate competition organized
          by the Dinajpur Debating Society.
        </p>
      </div>
    </div>

  </div>
</section>

<hr class="divider-line">

<!-- ==================== CERTIFICATIONS ==================== -->

<section class="section-block">
  <h2>Certifications</h2>

  <div class="cert-list">




    <!-- Cyber Security -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/18KFyvAjJjQBL97XDjT1hrtb7TMxXRUox/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Cyber Security
          </a>
        </p>

        <p class="cert-desc">
          Enhancing Digital Government and Economy (EDGE)
        </p>
      </div>

      <div class="cert-date">
        Sep 2024 – Dec 2024
      </div>
    </div>


    <!-- Software Testing -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/11vjOE41rv4mdr7RnSify30t_IFvAoasW/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Software Testing
          </a>
        </p>

        <p class="cert-desc">
          Enhancing Digital Government and Economy (EDGE)
        </p>
      </div>

      <div class="cert-date">
        Mar 2024 – May 2024
      </div>
    </div>


    <!-- Graphics Design -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1rtKzPKqB0tIe2WjNwa8EPyC13nkH3i6l/view?usp=drive_link"
             target="_blank"
             rel="noopener noreferrer">
            Graphics Design
          </a>
        </p>

        <p class="cert-desc">
          Learning &amp; Earning Development Project (LEDP)
        </p>
      </div>

      <div class="cert-date">
        Jan 2020 – Jun 2020
      </div>
    </div>


    <!-- Youth Social Leadership -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="https://drive.google.com/file/d/1Ae6YWbL-Wy5OZon2pUjOYipNHDjWJpxl/view"
             target="_blank"
             rel="noopener noreferrer">
            Youth Social Leadership
          </a>
        </p>

        <p class="cert-desc">
          Bangladesh Youth Leadership Training
        </p>
      </div>

      <div class="cert-date">
        Feb 2020 – Mar 2020
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">

<!-- ==================== CO-CURRICULAR ACTIVITIES ==================== -->

<section class="section-block">
  <h2>Co-Curricular Activities and Services</h2>

  <div class="cert-list">

    <!-- Admission Helpline -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_ADMISSION_HELPLINE_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Admission Helpline Assistant
          </a>
        </p>

        <p class="cert-desc">
          Assisted students and applicants through the
          Jahangirnagar University Admission Helpline.
        </p>
      </div>

      <div class="cert-date">
        2023 – 2024
      </div>
    </div>


    <!-- General Secretary -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_DINAJPUR_STUDENTS_ASSOCIATION_LINK"
             target="_blank"
             rel="noopener noreferrer">
            General Secretary
          </a>
        </p>

        <p class="cert-desc">
          Dinajpur Students Association of Jahangirnagar University.
          Served as General Secretary and contributed to organizational,
          student-support, and social activities.
        </p>
      </div>

      <div class="cert-date">
        2022 – 2025
      </div>
    </div>


    <!-- Science Club -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_JU_SCIENCE_CLUB_LINK"
             target="_blank"
             rel="noopener noreferrer">
            General Member
          </a>
        </p>

        <p class="cert-desc">
          Jahangirnagar University Science Club.
        </p>
      </div>

      <div class="cert-date">
        2019 – 2022
      </div>
    </div>


    <!-- Savar Half Marathon -->
    <div class="cert-item">
      <div class="cert-main">
        <p class="cert-name">
          <a href="YOUR_SAVAR_HALF_MARATHON_LINK"
             target="_blank"
             rel="noopener noreferrer">
            Volunteer
          </a>
        </p>

        <p class="cert-desc">
          Volunteer at the Savar Half Marathon, contributing to
          event organization and participant support.
        </p>
      </div>

      <div class="cert-date">
        2022
      </div>
    </div>

  </div>
</section>


<hr class="divider-line">
<!-- ========================================================= -->
<!-- TECHNICAL SKILLS -->
<!-- ========================================================= -->

<section class="section-block">

<h2>Technical Skills</h2>

<div class="skills-list">


<div class="skill-item">

<p class="skill-name">
Languages
</p>

<p class="skill-desc">
C, C++, Java, Python, PHP, LaTeX, HTML, CSS, JavaScript, MySQL
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Machine Learning
</p>

<p class="skill-desc">
PyTorch, Keras, OpenCV, TensorFlow, NLTK, Pandas, NumPy, Matplotlib
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Developer Tools
</p>

<p class="skill-desc">
Visual Studio Code, Code::Blocks, LaTeX, PyCharm,
Jupyter Notebook, Eclipse
</p>

</div>


<div class="skill-item">

<p class="skill-name">
Illustration Tools
</p>

<p class="skill-desc">
Adobe Illustrator, Adobe Photoshop, Canva,
Adobe Animate, Adobe Premiere Pro
</p>

</div>


</div>

</section>

<hr class="divider-line">
<footer class="site-footer">
  <div class="container text-center">
    <p class="mb-0">
      © 2026 Md. Shakil Ahmed. All rights reserved.
    </p>
  </div>
</footer>
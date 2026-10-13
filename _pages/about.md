---
layout: about
title: About
permalink: /

selected_papers: true
social: true

announcements:
  enabled: false
  scrollable: true
  limit: 5

latest_posts:
  enabled: false
  scrollable: true
  limit: 3
---

<style>

/* =========================================================
   GLOBAL ABOUT PAGE
   ========================================================= */

.about-page {
  max-width: 1100px;
  margin: 0 auto;
}


/* =========================================================
   NAME
   ========================================================= */

.about-name {
  margin: 10px 0 35px;
}

.about-name h1 {
  font-size: 3.2rem;
  font-weight: 400;
  letter-spacing: -1px;
  margin: 0;
}


/* =========================================================
   PROFILE ROW
   Photo + Current Position
   ========================================================= */

.profile-row {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 35px;
  align-items: stretch;
  margin-bottom: 55px;
}


/* =========================================================
   PHOTO
   ========================================================= */

.profile-photo {
  display: flex;
  justify-content: center;
  align-items: center;

  padding: 30px;

  border: 1px solid var(--global-divider-color);
  border-radius: 12px;

  min-height: 300px;
}

.profile-photo img {
  width: 250px;
  height: 250px;

  object-fit: cover;
  border-radius: 50%;

  box-shadow: 0 8px 30px rgba(0,0,0,0.12);
}


/* =========================================================
   CURRENT POSITION
   ========================================================= */

.position-panel {
  display: flex;
  flex-direction: column;
  justify-content: center;

  padding: 40px;

  border: 1px solid var(--global-divider-color);
  border-radius: 12px;

  min-height: 300px;
}

.position-title {
  font-size: 1.55rem;
  font-weight: 600;
  line-height: 1.4;

  margin-bottom: 18px;
}

.position-details {
  font-size: 1.05rem;
  line-height: 1.8;
}


/* =========================================================
   ABOUT DESCRIPTION BLOCK
   ========================================================= */

.about-section {
  margin-top: -20px;
  margin-bottom: 55px;

  padding: 32px 40px;

  border: 1px solid var(--global-divider-color);
  border-radius: 12px;
}

.about-section h2 {
  font-size: 1.7rem;
  font-weight: 500;

  margin-top: 0;
  margin-bottom: 20px;
}

.about-text {
  font-size: 1.05rem;
  line-height: 1.8;

  max-width: none;
}

.about-text p {
  margin-bottom: 20px;
}

.about-text p:last-child {
  margin-bottom: 0;
}


/* =========================================================
   RESEARCH
   ========================================================= */

.research-section {
  padding: 5px 0;
}

.research-section h2,
.journey-section h2 {
  font-size: 2rem;
  font-weight: 400;

  margin-bottom: 28px;
}

.research-intro {
  max-width: 850px;

  font-size: 1.05rem;
  line-height: 1.75;

  margin-bottom: 30px;
}

.research-grid {
  display: grid;

  grid-template-columns: repeat(3, 1fr);

  gap: 14px;
}

.research-item {
  padding: 22px 24px;

  border: 1px solid var(--global-divider-color);
  border-radius: 10px;

  font-size: 1rem;
  line-height: 1.5;

  transition: all 0.2s ease;
}

.research-item:hover {
  transform: translateY(-3px);

  box-shadow: 0 6px 20px rgba(0,0,0,0.07);
}


/* =========================================================
   CURRENT APPOINTMENTS
   ========================================================= */

.journey-section {
  padding: 50px 0 70px;
}

.journey {
  position: relative;

  margin-top: 35px;
  padding-left: 10px;
}

.journey-line {
  position: absolute;

  left: 9px;
  top: 8px;
  bottom: 8px;

  width: 1px;

  background: var(--global-divider-color);
}

.journey-item {
  position: relative;

  display: grid;

  grid-template-columns: 120px 1fr;

  gap: 25px;

  margin-bottom: 38px;
}

.journey-dot {
  position: absolute;

  left: 3px;
  top: 5px;

  width: 13px;
  height: 13px;

  border-radius: 50%;

  background: var(--global-theme-color);

  border: 3px solid var(--global-bg-color);
}

.journey-year {
  padding-left: 35px;

  font-size: 0.9rem;

  opacity: 0.65;
}

.journey-role {
  font-size: 1.1rem;

  font-weight: 600;

  margin-bottom: 5px;
}

.journey-place {
  line-height: 1.6;
}


/* =========================================================
   RESPONSIVE
   ========================================================= */

@media (max-width: 800px) {

  .profile-row {
    grid-template-columns: 1fr;
  }

  .profile-photo {
    min-height: auto;
  }

  .position-panel {
    min-height: auto;
  }

  .research-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}


@media (max-width: 550px) {

  .about-name h1 {
    font-size: 2.5rem;
  }

  .profile-photo img {
    width: 200px;
    height: 200px;
  }

  .research-grid {
    grid-template-columns: 1fr;
  }

  .journey-item {
    grid-template-columns: 1fr;

    gap: 5px;
  }

  .journey-year {
    padding-left: 35px;
  }

  .about-section {
    padding: 28px 24px;
  }

}

</style>


<div class="about-page">


<!-- =====================================================
     NAME
     ===================================================== -->


<!-- =====================================================
     PHOTO + CURRENT POSITION
     ===================================================== -->

<div class="profile-row">


  <!-- PHOTO -->

  <div class="profile-photo">

    <img
      src="{{ '/assets/img/dipanjyoti-paul.PNG' | relative_url }}"
      alt="Dipanjyoti Paul"
    >

  </div>


  <!-- CURRENT POSITION -->

  <div class="position-panel">

    <div class="position-title">
      Assistant Professor
    </div>

    <div class="position-details">

      Department of Artificial Intelligence<br>

      IIT Kharagpur<br><br>

      CRR Building<br>

      Kharagpur-721302

    </div>

    <div style="text-align: center; margin-top: 25px;">

      <a href="{{ '/Contact/' | relative_url }}"
        style="display: inline-block;
               padding: 10px 35px;
               border-radius: 30px;
               background: var(--global-theme-color);
               color: white !important;
               text-decoration: none !important;
               font-weight: 500;">

        Contact Me

      </a>

    </div>

  </div>


</div>


<!-- =====================================================
     ABOUT DESCRIPTION
     ===================================================== -->

<div class="about-section">

  <h2>About</h2>

  <div class="about-text"> 

    <p>
      Dr. Dipanjyoti Paul is an Assistant Professor in the Department of <a href="https://www.iitkgp.ac.in/">Artificial 
      Intelligence</a>   at the
      <a href="https://ai.iitkgp.ac.in/">Indian Institute of Technology Kharagpur</a>.
      He is a member of the Center for Artificial Intelligence Research (C-AIR) at the
      <a href="https://air.tsukuba.ac.jp/en/"> University of Tsukuba</a>, Japan and the Imageomics Institute at
      <a href="https://www.osu.edu/">The Ohio State University</a>, USA.
    </p>

    <p>
      Prior to joining IIT Kharagpur, he served as an Assistant Professor at the <a href="https://www.iiests.ac.in/en"> Indian Institute of Engineering Science & Technology (IIEST), Shibpur</a>, India, and the <a href="https://air.tsukuba.ac.jp/en/"> University of Tsukuba</a>, Japan. He also worked as a postdoctoral fellow in the Department of Computer Science and Engineering at <a href="https://www.osu.edu/">The Ohio State University</a>, USA.
    </p>

    <p>
      His research interests lie at the intersection of machine learning and biology, particularly in computer vision and acoustic signal processing for ecology and biodiversity, explainable AI, and medical imaging.
    </p>

  </div>

</div>


<!-- =====================================================
     RESEARCH
     ===================================================== -->

<div class="research-section">

  <h2>Research Interests</h2>

  <div class="research-intro">
  </div>

  <div class="research-grid">

    <div class="research-item">
      AI for Ecology and Bio-DIversity
    </div>

    <div class="research-item">
      Explainable and Interpretable AI 
    </div>

    <div class="research-item">
      Medical Imaging
    </div>

    <div class="research-item">
      Acoustic Signal Processing
    </div>

    <div class="research-item">
      Computer Vision
    </div>

    <div class="research-item">
      Natural Language Processing
    </div>

  </div>

</div>


<!-- =====================================================
     CURRENT APPOINTMENTS
     ===================================================== -->

<div class="journey-section">

  <h2>Current Appointments</h2>

  <div class="journey">

    <div class="journey-line"></div>


    <div class="journey-item">

      <div class="journey-dot"></div>

      <div class="journey-year">
        October 2026–Present
      </div>

      <div>

        <div class="journey-role">
          Assistant Professor
        </div>

        <div class="journey-place">
          IIT Kharagpur
        </div>

      </div>

    </div>


    <div class="journey-item">

      <div class="journey-dot"></div>

      <div class="journey-year">
        October 2025–Present
      </div>

      <div>

        <div class="journey-role">
          Visiting Scientist
        </div>

        <div class="journey-place">
          C-AIR, University of Tsukuba, Japan
        </div>

      </div>

    </div>


    <div class="journey-item">

      <div class="journey-dot"></div>

      <div class="journey-year">
        January 2024–Present
      </div>

      <div>

        <div class="journey-role">
          Visiting Researcher
        </div>

        <div class="journey-place">
          Imageomics Institute, The Ohio State University, USA
        </div>

      </div>

    </div>

  </div>

</div>


</div>
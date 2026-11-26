---
layout: single
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

<style>
.cv-timeline {
  margin: 35px 0;
}

.cv-timeline-item {
  display: grid;
  grid-template-columns: 135px 1fr;
  position: relative;
}

.cv-timeline-date {
  padding: 0 20px 30px 0;
  font-size: 0.8em;
  font-weight: 600;
  color: #64748b;
  text-align: right;
}

.cv-timeline-content {
  position: relative;
  border-left: 2px solid #b8c5d1;
  padding: 0 0 35px 25px;
}

.cv-timeline-content::before {
  content: "";
  position: absolute;
  left: -7px;
  top: 5px;
  width: 12px;
  height: 12px;
  background: #527b96;
  border-radius: 50%;
}

.cv-timeline-item:last-child .cv-timeline-content {
  border-left-color: transparent;
  padding-bottom: 0;
}

.cv-timeline-header {
  display: flex;
  align-items: center;
  gap: 15px;
  margin-bottom: 8px;
}

.cv-timeline-logo {
  width: 55px;
  height: 55px;
  object-fit: contain;
  flex-shrink: 0;
}

.cv-timeline-school {
  font-size: 1em;
  font-weight: 700;
}

.cv-timeline-position {
  font-size: 0.9em;
  margin-bottom: 4px;
}

.cv-timeline-location {
  color: #777;
  font-size: 0.8em;
}

@media (max-width: 600px) {
  .cv-timeline-item {
    grid-template-columns: 85px 1fr;
  }

  .cv-timeline-date {
    padding-right: 12px;
    font-size: 0.7em;
  }

  .cv-timeline-content {
    padding-left: 18px;
  }

  .cv-timeline-logo {
    width: 40px;
    height: 40px;
  }

  .cv-timeline-header {
    gap: 10px;
  }
}
</style>

<p>
  <a href="{{ site.baseurl }}/files/CV.pdf" target="_blank" rel="noopener noreferrer">
    <i class="fas fa-file-pdf"></i>
    Download Curriculum Vitae (PDF)
  </a>
</p>

<h2>Academic &amp; Research Journey</h2>

<div class="cv-timeline">

  <!-- Washington State University -->

  <div class="cv-timeline-item">

    <div class="cv-timeline-date">
      Aug 2025 – Present
    </div>

    <div class="cv-timeline-content">

      <div class="cv-timeline-header">
        <img
          src="{{ site.baseurl }}/images/wsu.png"
          class="cv-timeline-logo"
          alt="Washington State University">

        <div class="cv-timeline-school">
          Washington State University
        </div>
      </div>

      <div class="cv-timeline-position">
        M.S. in Food Science
      </div>

      <div class="cv-timeline-position">
        Graduate Research Assistant
      </div>

      <div class="cv-timeline-location">
        Pullman, Washington, USA
      </div>

    </div>
  </div>


  <!-- National Changhua University of Education -->

  <div class="cv-timeline-item">

    <div class="cv-timeline-date">
      Apr – Sep 2024
    </div>

    <div class="cv-timeline-content">

      <div class="cv-timeline-header">
        <img
          src="{{ site.baseurl }}/images/ncue.png"
          class="cv-timeline-logo"
          alt="National Changhua University of Education">

        <div class="cv-timeline-school">
          National Changhua University of Education
        </div>
      </div>

      <div class="cv-timeline-position">
        Research Intern
      </div>

      <div class="cv-timeline-location">
        Changhua, Taiwan
      </div>

    </div>
  </div>


  <!-- Ho Chi Minh City University of Technology -->

  <div class="cv-timeline-item">

    <div class="cv-timeline-date">
      Sep 2022 – Jan 2025
    </div>

    <div class="cv-timeline-content">

      <div class="cv-timeline-header">
        <img
          src="{{ site.baseurl }}/images/hcmut.png"
          class="cv-timeline-logo"
          alt="Ho Chi Minh City University of Technology">

        <div class="cv-timeline-school">
          Ho Chi Minh City University of Technology
        </div>
      </div>

      <div class="cv-timeline-position">
        Research Assistant
      </div>

      <div class="cv-timeline-location">
        Ho Chi Minh City, Vietnam
      </div>

    </div>
  </div>


  <!-- International University -->

  <div class="cv-timeline-item">

    <div class="cv-timeline-date">
      Sep 2024
    </div>

    <div class="cv-timeline-content">

      <div class="cv-timeline-header">
        <img
          src="{{ site.baseurl }}/images/iu.png"
          class="cv-timeline-logo"
          alt="International University VNU-HCM">

        <div class="cv-timeline-school">
          International University – VNU-HCM
        </div>
      </div>

      <div class="cv-timeline-position">
        B.Eng. in Food Technology
      </div>

      <div class="cv-timeline-location">
        Ho Chi Minh City, Vietnam
      </div>

    </div>
  </div>

</div>

</ul>

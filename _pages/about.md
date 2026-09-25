---
layout: home
permalink: /
title: "Shailesh J. Divey"
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <div class="home-hero__inner">
    <aside class="home-profile">
      {% if site.author.avatar %}
        <img class="home-avatar" src="{{ '/images/' | append: site.author.avatar | relative_url }}" alt="Shailesh J. Divey">
      {% else %}
        <div class="home-avatar home-avatar--placeholder" aria-label="Profile photo placeholder">SD</div>
      {% endif %}

      <h1>Shailesh J. Divey</h1>
      <p class="home-profile__role">Postdoctoral Researcher</p>
      <p class="home-profile__org">Max M. Fisher College of Business<br>The Ohio State University</p>

      <div class="home-socials" aria-label="Profile links">
        <a href="mailto:{{ site.author.email }}" aria-label="Email"><i class="fas fa-envelope"></i></a>
        <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
        <a href="https://github.com/{{ site.author.github }}" aria-label="GitHub"><i class="fab fa-github"></i></a>
        {% if site.author.orcid %}<a href="{{ site.author.orcid }}" aria-label="ORCID"><i class="ai ai-orcid"></i></a>{% endif %}
        {% if site.author.googlescholar %}<a href="{{ site.author.googlescholar }}" aria-label="Google Scholar"><i class="ai ai-google-scholar"></i></a>{% endif %}
      </div>
    </aside>

    <div class="home-about">
      <h2>About Me</h2>
      <p>
        I am a Postdoctoral Researcher in the Fisher College of Business at The Ohio State University, where I am fortunate to be supervised by <a href="https://fisher.osu.edu/people/gray.402" target="_blank" rel="noopener noreferrer">Dr. John Gray</a>. My research leverages mathematical, econometric, and predictive modeling techniques for studying decision-making across three problem domains: (1) supply chain risk management; (2) healthcare operations; and (3) humanitarian operations. My current work includes studying pharmaceutical manufacturing quality, supply chain risk management and coordination, and AI &amp; analytics for social good.<br>
      </p>
      <p>
        Before joining Ohio State, I was a Postdoctoral Associate at the MIT Center for Transportation &amp; Logistics and held academic appointments at the University of Oregon and the University of Alabama. I completed my Ph.D. in Operations Management (Decision Sciences Track, Econometrics Minor) from Rensselaer Polytechnic Institute, where I was advised by <a href="https://faculty.rpi.edu/m-hakan-hekimoglu" target="_blank" rel="noopener noreferrer">Dr. Mert Hekimoğlu</a> and <a href="https://faculty.rpi.edu/ravi-ravichandran" target="_blank" rel="noopener noreferrer">Dr. T. Ravichandran</a>.
      </p>

      <div class="job-market-note">

  <p>
    I am on the <span class="job-market-year"><strong>2026–27</strong></span> Academic Job Market.
  </p>

  <p>
    I will be presenting my job-market paper,
    <strong><em>Learning to Comply or Learning to Improve? Organizational Learning and Geography in Pharmaceutical Manufacturing</em></strong>,
    at:
  </p>

  <ul class="job-market-talks">
    <li>
      <strong>INFORMS 2026</strong> — November 1, 2026, 2:45 PM, Session: <em>Responsible Operations, Supply Chains, and Social Impact,</em> Moscone South, Room 207, Level 2
    </li>

    <li>
      <strong>DSI 2026</strong> — November 22, 2026, 4:30 PM, Session: <em>Healthcare and Life-Science Supply Chain Risk,</em> SF Marriott Marquis, 5th Floor, Sierra D
    </li>
  </ul>

</div>

      <a class="home-cv-button" href="{{ '/files/CV_Shailesh_Divey.pdf' | relative_url }}">
        <i class="fas fa-download" aria-hidden="true"></i> View / Download CV
      </a>

      <div class="home-details-grid">
        <section>
          <h2>Research Interests</h2>
          <ul>
            <li>Supply Chain Risk Management</li>
            <li>Pharmaceutical Manufacturing &amp; Quality</li>
            <li>Information Design</li>
            <li>AI &amp; Analytics for Social Good</li>
          </ul>
        </section>

        <section>
          <h2>Education</h2>
          <div class="home-education-item">
            <i class="fas fa-graduation-cap" aria-hidden="true"></i>
            <div><strong>Ph.D., Operations Management</strong><br><span>Rensselaer Polytechnic Institute, 2022</span></div>
          </div>
          <div class="home-education-item">
            <i class="fas fa-graduation-cap" aria-hidden="true"></i>
            <div><strong>M.Eng., Mechanical Engineering</strong><br><span>University of Texas, 2015</span></div>
          </div>
          <div class="home-education-item">
            <i class="fas fa-graduation-cap" aria-hidden="true"></i>
            <div><strong>M.S., Materials Science &amp; Engineering</strong><br><span>University of Texas, 2011</span></div>
          </div>
          <div class="home-education-item">
            <i class="fas fa-graduation-cap" aria-hidden="true"></i>
            <div><strong>B.S., Metallurgical &amp; Materials Engineering</strong><br><span>National Institute of Technology-Rourkela, India, 2008</span></div>
          </div>
        </section>
      </div>
    </div>
  </div>
</section>

---
layout: single
permalink: /
author_profile: false
classes: wide portfolio-home
---

<section class="portfolio-intro">
  <p class="eyebrow">FINANCE · RESEARCH · ANALYTICS</p>
  <h1>Utsav Bhatt</h1>
  <p class="intro-lede">I work on financial questions by combining business understanding, quantitative analysis and technology.</p>
  <p class="intro-copy">I’m an MBA Finance student with a Computer Science background. My current work focuses on fixed income, corporate credit, currency derivatives and financial modelling. I’m interested in how markets, companies and capital structures behave under changing economic conditions.</p>
  <div class="intro-links">
    <a class="text-link" href="{{ '/projects/' | relative_url }}">Explore selected work <span aria-hidden="true">↗</span></a>
    <a class="text-link" href="{{ '/about/' | relative_url }}">About me <span aria-hidden="true">↗</span></a>
    <a class="text-link" href="https://www.linkedin.com/in/utsav-bhatt1/" target="_blank" rel="noopener">LinkedIn <span aria-hidden="true">↗</span></a>
  </div>
</section>

<section class="portfolio-section" id="selected-work">
  <div class="section-heading">
    <div><p class="eyebrow">01 / SELECTED WORK</p><h2>Research and applied projects</h2></div>
    <a class="text-link" href="{{ '/projects/' | relative_url }}">All projects ↗</a>
  </div>
  <div class="project-list">
    {% assign featured_projects = site.data.projects | where: "featured", true %}
    {% for project in featured_projects %}
      {% include project-card.html project=project %}
    {% endfor %}
  </div>
</section>

<section class="portfolio-section portfolio-two-col">
  <div>
    <p class="eyebrow">02 / HOW I WORK</p>
    <h2>Analysis that can be inspected.</h2>
  </div>
  <div>
    <p>I prefer work that makes its reasoning visible: the question being answered, the data and assumptions used, the analytical method, and the limitations of the result. Where possible, I publish the underlying report, notebook, dataset or spreadsheet alongside the conclusions.</p>
    <a class="text-link" href="{{ '/projects/' | relative_url }}">Browse reports, data and models ↗</a>
  </div>
</section>

<section class="portfolio-section communication-section" id="communication">
  <p class="eyebrow">03 / COMMUNICATION</p>
  <h2>Research is only useful when it can be explained.</h2>
  <p>Alongside analytical work, I take part in public speaking, hosting and conversations around business and ideas. This section brings those activities into the same portfolio as my research and models; recordings and event features will be linked here as they are published.</p>
  <a class="text-link" href="{{ '/about/' | relative_url }}#communication">More about my communication work ↗</a>
</section>

<section class="portfolio-contact">
  <p class="eyebrow">IN TOUCH</p>
  <h2>For research, finance and analytical roles.</h2>
  <p>For opportunities or a discussion about any of the work published here.</p>
  <a class="text-link" href="mailto:utsavbhattt@gmail.com">utsavbhattt@gmail.com ↗</a>
</section>

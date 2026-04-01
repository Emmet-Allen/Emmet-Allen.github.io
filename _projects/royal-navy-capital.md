---
layout: default
title: Royal Navy Capital
project_url: https://royal-navy-capital.netlify.app
---

<article class="post">
  <h1>{{ page.title }}</h1>
  <a href="{{ page.project_url }}" class="read-more">View Project</a>

  <div class="entry">
The general theme for this project was to get re-acquinted with Web Development, specifically Front End Development. React was used for its ease of modularity through the use of conternization via components using the Flux Paradigm to ensure maximum code maintainability and unidirectional data flow. React Stylized Components was used for out-of-the-box intergration with React, further improving on Reacts' modularity by including styling that can be containerized to specific components and further reinforcing the Flux Paradigm. SCSS was used for its pre-processing styling power, enabling the use of global variables and import to be used within a master-style sheet, creating reinforced style containerization for general Web Components when necesscary. React Router was also used to minimize server calls within the page itself by manipulating the DOM of single-page applications, useful for controlling progressive resolution views between pages.
  </div>
</article>

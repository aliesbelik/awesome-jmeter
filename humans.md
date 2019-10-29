
---
layout: humans
permalink: '/humans.txt'
---

/* TEAM */
    {% for contributor in site.github.contributors %}
    Name: {{ contributor.login }}
    Site: {{ contributor.html_url }}
    {% endfor %}

/* THANKS */
    Awesome project: Sindre Sorhus (https://github.com/sindresorhus/awesome)
    Minimal theme: Steve Smith (https://github.com/pages-themes/minimal)

/* SITE */
    Last update: {{ site.time }}
    Revision: {{ site.github.build_revision }}
    Language: English
    Standards: HTML5, CSS3
    Components: Jekyll
    Software: Sublime Text

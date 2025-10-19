---
layout: default
title: "{{ site.title }}"
---

# {{ site.name }}

**Cybersecurity Student, Hocking College**  
Class of 2026

![Avatar]({{ site.avatar_url }})

---

## About Me

{{ site.bio }}

---

## Courses

<div class="course-grid">
  {% for course in site.data.courses %}
    {% include course-card.html course=course %}
  {% endfor %}
</div>

---

## Projects

<div class="project-grid">
  {% for project in site.data.projects %}
    {% include project-card.html project=project %}
  {% endfor %}
</div>

---

## Certifications

- CompTIA Security+ (Expected 2026)
- CompTIA Network+ (2025)

---

## Contact

- [Email](mailto:your.email@hocking.edu) <!-- Update this! -->
- [LinkedIn](https://linkedin.com/in/yourprofile) <!-- Update this! -->
- [GitHub](https://github.com/yourusername) <!-- Update this! -->
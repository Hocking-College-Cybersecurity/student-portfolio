---
layout: default
title: "Jane Doe — Cybersecurity Portfolio"
---

# Jane Doe

**Cybersecurity Student, Hocking College**  
Class of 2026

![Avatar](https://avatars.githubusercontent.com/u/000000?v=4)

---

## About Me

_A brief bio here._

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

- [Email](mailto:your.email@hocking.edu)
- [LinkedIn](https://linkedin.com/in/yourprofile)
- [GitHub](https://github.com/yourusername)
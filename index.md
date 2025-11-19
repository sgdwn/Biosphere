---
layout: home
header:
  overlay_image: /assets/images/IMG_2941.webp
  overlay_filter: 0.5
  caption: "Photo credit: **Biosphere**"
feature_row:
  - image_path: /assets/images/Logo.png
    alt: "Internships and Employment"
    title: "Internships and Employment"
    excerpt: "Find opportunities to gain experience and kickstart your career."
    url: "Employability/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/FirthHall.jpg
    alt: "Study Support"
    title: "Study Support"
    excerpt: "Get help with your studies and access resources to succeed."
    url: "study_support/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  - image_path: /assets/images/IMG_2941.webp
    alt: "Events"
    title: "Events"
    excerpt: "Join us for social and academic events throughout the year."
    url: "events/"
    btn_label: "Read More"
    btn_class: "btn--primary"
---

Created by a small group of students, Biosphere is the university's first student-led platform that brings together students and ideas from all across the biosciences.

Our aim is to create a supportive community where you can explore academic interests, develop new ideas, and access opportunities to actively engage with industry beyond the classroom.

<div class="notice--info">
  <h4>Meet the committee</h4>
  
  <div class="committee-avatar-row">
    {% for member in site.committee %}
      {% if member.avatar %}
        <img src="{{ member.avatar | relative_url }}" alt="Photo of {{ member.title }}" class="committee-avatar-thumbnail">
      {% endif %}
    {% endfor %}
  </div>
  
  <p>
    <a href="{{ '/committee/' | relative_url }}" class="btn btn--primary">
      Go <i class="fas fa-arrow-right" aria-hidden="true"></i>
    </a>
  </p>
</div>

{% include feature_row %}

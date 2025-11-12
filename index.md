---
layout: home
---

# Biosphere  
![The quad in Firth Court, Sheffield.](assets/images/IMG_2941.webp)
Created by a small group of students, Biosphere is the university's first student-led platform that brings together students and ideas from all across the biosciences.   
​
Our aim is to create a supportive community where you can explore academic interests, delevop new ideas, and accesses opportunities to actively engage with industry beyond the classroom.  

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

- (Internships and Employment)[/employability]
- (Study Support)[/study-support]
- (Events)[/events]


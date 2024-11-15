---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home

# groups of columns of {roles: list, width: num, image: bool}
role-tables:
- - roles: [faculty, grad, masters, ugrad]
    width: 4
    image: true
- - roles: [collab, alum, ugrad-alum]
    width: 5
    image: false
---
<!-- <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.2.1/dist/css/bootstrap.min.css" integrity="sha384-GJzZqFGwb1QTTN6wy59ffF1BuGJpLSa9DkKMp0DgiMDm4iYMj70gZWKYbI706tWS" crossorigin="anonymous"> -->
<style type="text/css" media="screen">



  /* ul {
    margin: 0;
  } */
  
  /* body {
      font-family: 
  } */
</style>

<link rel="icon" href="{{ site.url }}/favicon.ico" type="image/x-icon">

<div class="mission">
We envision a future where anyone can use technology and data effectively to learn and make informed decisions that advance society.
Our mission is to understand real-world users, design usable abstractions, and develop interactive reasoning approaches that empower people to make data-informed decisions.
</div>
<br>
<div class="news">
    We are looking for postdocs, PhD students, Master's students, and undergraduates to join our group!
    <br>
    What we're looking for: 
     <ul>
        <li style="font-weight:bold">Postdocs</li> Expertise and interest in causal inference, Bayesian modeling, end-user programming, data visualization, and data science education ➡ <a href="https://docs.google.com/document/d/12J8GMA8MFmMvgR96Y-xfYTJl-DycgnHlzyE0PjP8fL0/">Submit your application.</a>
        <li style="font-weight:bold">PhD, Master's</li> Interest in HCI, data science, or programming languages research ➡ <a href="https://grad.ucla.edu/admissions/admission-application-for-graduate-admission/">Apply to UCLA CS.</a> 
        <li style="font-weight:bold">UCLA Undergraduates</li> Interest in exploring HCI research, CS + X, data science ➡ <a href="https://forms.gle/K1bGJx1DScpt3cy88">Complete this interest form.</a>
    </ul> 
</div>

<br>

## People

<!-- <p>{{site.data.people}}</p> -->
<!-- {% for role-table in page.role-tables %}
  <p>{{role-table}}</p>
  {% for role in role-table.roles %}
    <p>{{role}}</p>
    <p>{{role-table.roles}}</p>
  {% endfor %}
{% endfor %} -->
<div class="container-fluid">
<div class="photo-row">
  {% for item in site.data.people %}
      {%assign person = item[1] %}
      <div class="photo-item" stlye="height:200px; width:200px; overflow: hidden;">
        <img src="{{person.image}}"/>
        <div class="photo-info">
          <a class="photo-name" href="{{person.website}}">{{person.display_name}}</a>
          <p class="photo-title">{{person.title}}</p>
          <!-- <p class="photo-title">{{person.interests}}</p> -->
        </div>
      </div>
  {% endfor %}
</div>
</div>

## Courses
<a href="https://docs.google.com/document/d/11U6mRCJ223FE_ajKWiLYuXw5qHYmw4_5WZINPUmrSRk/edit?tab=t.0#heading=h.uvv6b2s0nzj">CS 239 (Grad) Introduction to Human-Computer Interaction (Winter 2025)</a>
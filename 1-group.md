---
layout: page
title: Group
permalink: /group/
---

<link rel="icon" href="{{ site.url }}/favicon.ico" type="image/x-icon">

## Join us!
<div class="news">
    We are looking for postdocs, PhD students, Master's students, and undergraduates to join our group!
    <br>
    What we're looking for: 
     <ul>
        <li style="font-weight:bold">Postdocs</li> Expertise and interest in causal inference, Bayesian modeling, end-user programming, data visualization, and data science education ➡ <a href="https://docs.google.com/document/d/12J8GMA8MFmMvgR96Y-xfYTJl-DycgnHlzyE0PjP8fL0/">Submit your application.</a>
        <li style="font-weight:bold">PhD,Master's</li> Interest in HCI, data science, or programming languages research ➡ <a href="https://grad.ucla.edu/admissions/admission-application-for-graduate-admission/">Apply to UCLA CS.</a> 
        <li style="font-weight:bold">UCLA Undergraduates</li> Interest in exploring HCI research, CS + X, data science ➡ <a href="https://forms.gle/K1bGJx1DScpt3cy88">Complete this interest form.</a>
        <!-- * <span style="font-style:italic"> I'm especially interested in students who are majoring in {CS, Statistics} + Something Else to apply.</span> -->
    </ul> 
</div>

<br>

## Members
<div class="container-fluid">
<div class="photo-row">
  {% for item in site.data.people %}
      {%assign person = item[1] %}
      <div class="photo-item" stlye="height:200px; width:200px; overflow: hidden;">
        <img src="{{site.url}}/{{person.image}}"/>
        <div class="photo-info">
          <a class="photo-name" href="{{person.website}}">{{person.display_name}}</a>
          <p class="photo-title">{{person.title}}</p>
          <p class="photo-title">{{person.interests}}</p>
        </div>
      </div>
  {% endfor %}
</div>
</div>

## Values

<span style="font-weight:bold">We strive for purposeful excellence.</span> 

Excellence is engaging in the following process:
- We reflect on our intentions and articulate a purpose. 
- We develop actions and habits aligned with this purpose and practice them consistently. 
- We explore beyond our comfort zone. 
- This leads to growth, learning, and discovery of “truth.”
- We refine our purpose based on these.

<span style="font-weight:bold">We build mutually beneficial relationships and collaborations.</span>

- We start from a place of believing in the best intentions of others. 
- This opens us up to seeking diverse perspectives, understanding each other, and collaborating creatively and productively.
- In turn, these experiences increase trust in a positive feedback loop.

<span style="font-weight:bold">We orient towards joy.</span> 
- We learn from failures and look for takeaways in negative experiences. 
- We use joy as a compass to guide our actions (informs our purpose) and a key form of feedback. 
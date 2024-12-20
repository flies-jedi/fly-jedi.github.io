---
layout: page
title: JEDI meeting 2025
description: first post COVID19 meeting
img: assets/img/JEDImeeting2025/chateaudufey.jpg
importance: 1
category: future
related_publications: true
---

You will be able to register here starting mid-december https://flyjedi.sciencesconf.org/ 

We decided to organize that first post COVID IRL JEDI meeting at the <a href = "https://chateaudufey.com/">Château du Feÿ</a> from 

To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JEDImeeting2025/chateaudufey.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JEDImeeting2025/chateaudufey_garden.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/JEDImeeting2025/prelim_program2025.png" title="preliminary program" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Preliminary program of the JEDI meeting 2025 - to be refined.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/JEDImeeting2025/chateaudufey_wide.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/JEDImeeting2025/chateaudufey_livingroom.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

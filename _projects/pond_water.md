---
layout: page
title: pond water analysis
description: 3D-printed phone microscope and AI movement detection (Governor's Honors Program in 2023)
img: assets/img/pond1image.jpg
importance: 1
category: academic
---

**Developed Technical Skills:**
- **CAD and Rapid Prototyping**: Designed multiple 3D-printed components, addressing stability/usability obstacles.
- **Optics and Microscopy**: Explored different glass bead sizes/compound lenses for optimal magnification.
- **Machine Learning and Image Processing**: Integrated a TensorFlow model with OpenCV to automate organism detection.
- **Collaborative Problem-Solving**: Led a cross-disciplinary team, coordinating different elements of engineering.

During the summer of my junior year, I participated in the Georgia Governor's Honors Program as a Mechanical Design major. With a limited budget of around $100 and a short timeline, I led a project to design a portable microscope attachment that would convert a smartphone into a functional microscope. 

After frequently visiting a natural pond near our classrooms, I was inspired to create a device to analyze the water and found two team members with backgrounds in computer science and mechanical/electrical engineering to develop the project.

The core of the project was a glass bead that, when placed over a phone camera, could magnify close-up subjects. However, achieving stability for consistent magnification was challenging. To address this, I designed and iterated on several 3D-printed clips using AutoCAD before opting for a custom phone case, which provided greater stability and usability..

<div class="row">
  <div class="col-sm mt-3 mt-md-0">
    {% include video.liquid 
       path="assets/videos/pondvideo.MP4" 
       class="img-fluid rounded z-depth-1" 
       controls="true" 
       caption="A video taken of the pond water using the microscope." %}
  </div>
</div>


After validating our design by examining pond samples and confirming the microscope’s effectiveness, we decided to enhance its functionality with machine learning. Using TensorFlow and OpenCV in Python, we integrated a model capable of detecting moving amoebas in the water, drawing bounding boxes around them to simplify the identification of living organisms. 

This phase of the project allowed me to apply programming skills in a real-world context, via reinforcing my experience with Python and machine learning.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pondwaterposter.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pondwaterpresentation.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our project booth, and our poster, along with the team.
</div>

Our project culminated in a presentation at the program showcase, where we demonstrated the device’s practical applications and potential for educational and consumer use. This experience honed my skills in engineering design, teamwork, and innovation, and reinforced the value of adaptability when working under constraints.

The poster can be found below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pondwaterslide.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our presentation poster, showcasing our design iterations and process.
</div>
---
layout: page
title: pond water analysis
description: 3D-printed phone microscope and AI movement detection (Governor's Honors Program in 2023)
img: assets/img/pondimage.jpg
importance: 1
category: academic
---

During the summer of my junior year, I participated in the Georgia Governor's Honors Program as a Mechanical Design major. With a limited budget of around $100 and a short timeline, I led a project to design a portable microscope attachment that would transform a smartphone into a functional microscope. Inspired by a natural pond near our classrooms, I envisioned this device as a tool to analyze pond water samples and enlisted two team members with backgrounds in computer science and mechanical/electrical engineering to bring the idea to life.

The core of the project was a glass bead that, when placed over a phone camera, could magnify close-up subjects. However, achieving stability for consistent magnification was challenging. To address this, we designed and iterated on several 3D-printed clips before opting for a custom phone case, which provided greater stability and usability. This process strengthened my rapid prototyping and CAD skills, as I worked through various design solutions and adapted quickly to feedback.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pondimage.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    An image of one of the pictures taken of the pond water
</div>

After validating our design by examining pond samples and confirming the microscope’s effectiveness, we decided to enhance its functionality with machine learning. Using TensorFlow and OpenCV in Python, we integrated a model capable of detecting moving amoebas in the water, drawing bounding boxes around them to simplify the identification of living organisms. This feature, implemented using iFun Webcam to access the phone camera, added a new layer of interactivity and scientific application to the project. This phase of the project allowed me to apply my programming skills in a real-world context, reinforcing my experience with Python and machine learning integration.

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

**Technical Skills Developed:**
- **CAD and Rapid Prototyping**: Designed and iterated multiple 3D-printed components, from horizontal and vertical clips to a custom phone case, addressing stability and usability challenges.
- **Optics and Microscopy**: Explored different glass bead sizes and compound lenses to achieve optimal magnification, deepening my understanding of optical physics and microscope design.
- **Machine Learning and Image Processing**: Integrated a TensorFlow model with OpenCV to detect amoebas and impurities in real time, automating organism detection and enhancing usability.
- **Collaborative Problem-Solving**: Led a cross-disciplinary team, coordinating mechanical design with computer science and electrical engineering elements to create a cohesive product.

**Outcomes**
Our project culminated in a presentation at the program showcase, where we demonstrated the device’s practical applications and potential for educational and consumer use. This experience honed my skills in engineering design, teamwork, and innovation, and reinforced the value of adaptability when working under constraints.

The poster can be found below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/pondwaterslide.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Our presentation poster, showcasing our design iterations and process.
</div>

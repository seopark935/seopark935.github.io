---
layout: page
title: haptic feedback prototyping
description: Haptic Feedback for the Visually Impaired, designed to help the blind in understanding their surroundings (2021 Gwinnett School of Mathematics, Science, and Technology Science and Engineering Fair)
img: assets/img/hapticfront.png
importance: 2
category: competitions
---

During my sophomore year, I started a project to develop a cost-effective assistive device using distance sensors and vibration motors to help visually impaired individuals navigate their surroundings. Ideally, the user would wear a vest or belt containing motors at different radial directions that would increase or decrease in intensity depending on how close they were to surfaces.

This project was my first hands-on experience with Arduino, soldering, and electronics, providing me with foundational skills in hardware and software development.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticproof.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticsoldering.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticinfrared.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From left to right: The initial Arduino connection to an ultrasonic distance sensor, soldering the vibration motor, and testing the distance capability.
</div>

Because the device had to be affordable and simple to implement, I rapidly prototyped the device in a single day, using household items such as cardboard from cereal boxes, an old phone-slot VR headset, and backpack straps. This early version allowed me to test core functionality quickly and laid the groundwork for the final design.

The finalized prototype utilized four ultrasonic sensors mounted on a headset to detect obstacles within a 3-meter range, translating this information into haptic feedback through vibration motors. Through comparative testing, I selected ultrasonic sensors over infrared due to their superior accuracy at close range, confirmed by statistical analysis using ANOVA testing. An Arduino controlled the sensor data processing and vibration output, allowing real-time feedback to the user.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticconstruction.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticback.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/hapticfront.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The prototype hardware and wiring.
</div>

**Key Technical Skills:**
- **Hardware and Sensor Integration**: Developed skills in sensor evaluation, soldering, and microcontroller programming to assemble a functional device.
- **Rapid Prototyping and Resourcefulness**: Created a proof-of-concept model using readily available materials, highlighting my adaptability and problem-solving under constraints.
- **Data Analysis and Statistical Testing**: Conducted comparative tests between infrared and ultrasonic sensors, validating the ultrasonic sensor’s effectiveness for close-range detection using statistical methods.
- **Embedded Software Development**: Programmed an Arduino to manage real-time data processing and haptic feedback, ensuring responsive and intuitive interaction.
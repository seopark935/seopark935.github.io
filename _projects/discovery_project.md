---
layout: page
title: discovery project
description: Working with Raspberry PI, headless setup, and transparent OLED displays.
img: assets/img/discovery.jpg
importance: 1
category: academic
---

**Developed Technical Skills:**
- **Embedded Systems and Hardware Integration**: Configured a Raspberry Pi Zero W to operate a transparent OLED display.
- **Networking and SSH Access**: Established a headless setup for the Raspberry Pi, troubleshooting SSH access issues.
- **Linux OS and Python**: Installed Raspbian OS, used Python for display control, and handled image rendering.

After seeing recent advancements in VR and AR technology, like [Meta's new Orion glasses](https://about.fb.com/news/2024/09/introducing-orion-our-first-true-augmented-reality-glasses/), I was inspired to create my own heads-up display using a transparent OLED screen and a Raspberry Pi. Ideally, it would display navigation directions while on my bike, alongside weather and time data.

While exploring the documentation, I realized that building a fully-featured set of glasses—complete with cameras, voice recognition, and a rechargeable battery—would be too time-consuming. So, I decided to simplify the project to focus on displaying bitmap images on the transparent screen as a first step toward a more advanced prototype.

Even this scaled-back version presented challenges. First, I was using a Raspberry Pi Zero W, which lacks some of the ports found on larger microcontrollers, like full HDMI and USB ports. Additionally, I wanted a fully headless setup, meaning I needed to connect via SSH instead of using HDMI and a keyboard, which complicated the setup.

Georgia Tech’s internal WiFi network, eduroam, posed connectivity issues with the Pi. When I tried using a friend’s apartment WiFi, I ran into similar problems. After multiple attempts with different microSD card images, I resorted to directly connecting the Raspberry Pi via micro USB.

This, too, was challenging. Many Raspberry Pi setup guides were either outdated or didn’t match my specific Pi version, so I had to experiment to find the right setup image. Once the Pi booted, my computer didn’t recognize the USB COM device as a network output, blocking my SSH access. I also discovered that the password in the `userconf.txt` file needed encoding for the Pi to recognize it.

After a few days, I was finally able to SSH into the Raspberry Pi. But a new problem arose: how to get the screen running. The screen packaging lacked instructions or a link to download software. I searched for tutorials for similar transparent screens, hoping they might work, but nothing did. Finally, I realized I could search for the manufacturer’s name online. This led me to the correct software, and after downloading and running the provided Python code, I successfully displayed a bitmap image on the screen. You can see the result below.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/raspberrypi.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Triumph, finally! - Modified the manufacturer-provided Python code to keep the bitmap on the screen even after the program terminated.
</div>

This project is still in the early stages. I plan to try connecting the display to an iPhone to mirror notifications, though documentation on phone mirroring is somewhat limited. Another option is to 3D-print a case and use the display more simply—as a regular screen for showing time, music data, or other information, which may be more straightforward.

Overall, I enjoyed working with the Raspberry Pi and experimenting with practical hardware, even if troubleshooting the SSH connection and re-imaging various Raspbian OS versions on a microSD card was a challenge!
---
description: Spring 2024
---

# DES5002 Designing Robots for Social Good

## Course Description

{% include ".gitbook/includes/one-page-course-description.md" %}

## Learning Outcomes

At the end of this course, students will be able to:

1. Conduct analysis of robotic systems in terms of technical and ethical aspects.
2. Adopt advanced technologies in designing robotic systems.
3. Demonstrate ability to align technical and ethical guidelines in designing robots for social good.

## Content Summary

{% include ".gitbook/includes/one-page-content-summary.md" %}

## Course Instructor & Teaching Team

{% include ".gitbook/includes/one-page-teaching-team.md" %}

## Grading Policy

{% include ".gitbook/includes/one-page-grading-policy.md" %}

## Academic Integrity

{% include ".gitbook/includes/one-page-academic-integrity.md" %}

## University Calendar

{% include ".gitbook/includes/one-page-university-calendar.md" %}

## Recommended Textbook(s)

{% include ".gitbook/includes/one-page-textbooks.md" %}

## Teaching Schedule

{% include ".gitbook/includes/one-page-teaching-schedule.md" %}

## Important Deadlines

{% include ".gitbook/includes/one-page-important-deadlines.md" %}

## Project Reachy Fusion for DES5002 <a href="#block-00bae408-07a1-4273-8907-57d88899cc8c" id="block-00bae408-07a1-4273-8907-57d88899cc8c"></a>

n this project, we aim to adopt [Reachy by Pollen Robotics](https://www.pollen-robotics.com/) as the subject to practice basic concepts in mechanical design using Autodesk Fusion 360. The overall goal is to conduct a design analysis of Reachy to evaluate its engineering characteristics against its performance, use Fusion 360 as the tool for design analysis, formulate a user manual with details instructions and conclude with design recommendations for future iterations.

\[All images and videos below are reproduced from Reachy main website for educational purposes only. We hope to talk with Reachy about properly using this media content. Please contact [wanf@sustech.edu.cn](mailto:wanf@sustech.edu.cn) for more.]

![](.gitbook/assets/image-1024x515.webp)

### About Reachy by Pollen Robotics <a href="#block-e06076a0-dca0-47a9-bbfc-0af2bfe8c53e" id="block-e06076a0-dca0-47a9-bbfc-0af2bfe8c53e"></a>

Reachy is an expressive open-source humanoid platform programmable with Python and ROS. He is particularly good at interacting with people and manipulating objects.

<table data-view="cards"><thead><tr><th></th><th data-hidden data-card-cover data-type="image">Cover image</th></tr></thead><tbody><tr><td><p><a href="https://cad.onshape.com/documents/5a9e7c88f6e1068df540bf7a/">Head</a></p><p>This is a relatively simple design compared to the rest of Reachy, with only two servo motors moving the antenna. It also has two vision sensors with two lenses of the same specs but different shapes from the outlook.</p></td><td><a href=".gitbook/assets/onshape_head_module.webp">onshape_head_module.webp</a></td></tr><tr><td><p><a href="https://cad.onshape.com/documents/5ca7f684d33fbcace89ad4d3/">Neck/Orbita Joint</a></p><p>This is a relatively complex design compared to the rest of Reachy, where a patented parallel mechanism is driven by three brushless motors designed in a compact form factor. It looks a bit strange but functions in a “magical” way, powered by kinematics.</p></td><td><a href=".gitbook/assets/onshape_orbita.webp">onshape_orbita.webp</a></td></tr><tr><td><p><a href="https://cad.onshape.com/documents/0306aa0a644dba7cf10899a8/">Trunk</a></p><p>This is the largest part of Reachy with no moving parts, but all movable parts will be connected. It houses most electronics and needs sufficient engineering rigidity, where structural analysis would be required.</p></td><td><a href=".gitbook/assets/onshape_trunk_module.webp">onshape_trunk_module.webp</a></td></tr><tr><td><p>Left <a href="https://cad.onshape.com/documents/2cd541150588bd17e3473399/">Arm</a></p><p>This is the most dexterous part of Reachy with the most degree of freedom, providing planning for physical interaction with the external environment. It houses most of the servo motors of Reachy with a large range of motion that needs to be carefully characterized and designed.</p></td><td><a href=".gitbook/assets/onshape_arm_module.webp">onshape_arm_module.webp</a></td></tr><tr><td><p>Left <a href="https://cad.onshape.com/documents/4456e4d7aa9833296dc141b2/">Gripper</a></p><p>This is the part where the dream (or simulation) comes true to affect the actual interaction with the physical environment. The challenge is to involve the least number of servo motors for maximum dexterity while dealing with the objects of various designs.</p></td><td><a href=".gitbook/assets/onshape_gripper_module.webp">onshape_gripper_module.webp</a></td></tr><tr><td><p>Right <a href="https://cad.onshape.com/documents/2cd541150588bd17e3473399/">Arm</a></p><p>In this project, your team will use an Arm prototype developed by Sun Haoran (SUSTech Mechanical Class 2016, currently a SUSTech-HKU Joint Ph.D. student at SUSTech Design and Learning Lab). We will provide a working prototype, and your task will involve providing further design optimization so that it may fit Reachy in a better way. Talk to the course instructor for further details.</p></td><td><a href=".gitbook/assets/Screen-Shot-2022-08-30-at-11.35.11-1024x786.webp">Screen-Shot-2022-08-30-at-11.35.11-1024x786.webp</a></td></tr><tr><td><p>Right <a href="https://cad.onshape.com/documents/4456e4d7aa9833296dc141b2/">Gripper</a></p><p>In this project, your team will use a Gripper prototype developed by Sun Haoran (SUSTech Mechanical Class 2016, currently a SUSTech-HKU Joint Ph.D. student at SUSTech Design and Learning Lab). We will provide a working prototype, and your task will involve providing further design optimization so that it may fit Reachy in a better way. Talk to the course instructor for further details.</p></td><td><a href=".gitbook/assets/Screen-Shot-2022-08-30-at-11.35.47-1024x786.webp">Screen-Shot-2022-08-30-at-11.35.47-1024x786.webp</a></td></tr><tr><td>Starting this year, we adopt Reachy in our teaching and learning for students at SUSTech Design and Learning Lab, with pilot projects through ME303 Mechanical Design, DES5002 Designing Robots for Social Good, and hopefully more. The shared idea is to implement Reachy as the subject of learning the various mechanical and robot design features. Both courses will share a similar structure to rebuild the Reachy with a touch of Fusion 360, as the original project was implemented using OnShape.</td><td><a href=".gitbook/assets/reachy-arm-kit.webp">reachy-arm-kit.webp</a></td></tr></tbody></table>

For [DES5002](https://des5002.ancorasir.com/), as a selective course for graduate students, the aim is to practice the use of modern CAD systems (Fusion 360 in our case) to get yourself familiar with some of the key concepts behind the design of various standard and non-standard parts as well as the whole assembly process, using the Generative Design tool to recreate new designs by defining the engineering constraints, 3D print and assemble a new design of Reachy assembled for potential applications in Social Good.

### Notes <a href="#block-ea1eaaf1-1a85-400c-98bd-91d50ea28209" id="block-ea1eaaf1-1a85-400c-98bd-91d50ea28209"></a>

* Tips on poster preparation
  * [Harvard](https://it.hms.harvard.edu/our-services/research-computing/services/research-imaging-solutions/ris-seminar-handouts)
  * [MIT](https://mitcommlab.mit.edu/nse/commkit/poster/)
  * [NYU](https://guides.nyu.edu/posters)

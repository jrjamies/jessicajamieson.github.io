---
layout: post
title: OpengGL Aquarium
excerpt: "An interactive OpenGL and C++ aquarium created as the final project for a Computer Graphics course."
modified: 2015-03-27
tags: [software, opengl, graphics, aquarium]
comments: false
share: false
projectImage:
  feature: graphics.jpg
category: projects
---
<!--
This project respresents my pride and joy of Fall 2014. After a large number of hardworking and sleepless hours, I present to you my aquarium:
-->

<!-- ![Graphics Aquarium]({{ site.url }}/images/graphics.jpg) -->

<p><video controls>
  <source src="{{ site.url }}/images/fish.webm" type="video/webm">
Your browser does not support the video tag.
</video></p>

This interactive OpenGL and C++ project was the final assignment for a Computer Graphics course at the University of Waterloo. We were required to design and implement 10 objectives based on new course material, while also considering everything we'd learned prior in the course. A few highlights for me were shader programming, bump mapping, particle systems, fractal terrain, and motion path animation.

Shader programming was enjoyable because I got to indulge my artsy side, and play around with aesthetics. I implemented toon shading (pictured below), and added fog effects to the reflection in the glass for added realism. Particle systems were also fun because, well, <a href="http://media.giphy.com/media/LmY8STYyvCtiM/giphy.gif" target="_blank">bubbles</a>! 

<img src="{{ site.url }}/images/graphics_fractals.gif" alt="Terrain" style="float:left; width: 200px; padding-right:15px;">
I also enjoyed experimenting with computer generated fractals. The mountains pictured are dynamically generated fractal terrain, and the plant is an few iterations of an L-system fractal. I've always been fascinated by fractals in nature, and have studied a more mathematical approach, so I was interested in programatically emulating the visual complexity.


I was recognized as the 3rd place winner in my class for this project. We were evaluated not only on the completion of our objectives, but also our code quality, documentation, creativity and overall aesthetic. For more information check out the <a href="http://www.bulletin.uwaterloo.ca/2015/jan/09fr.html" target="_blank">Waterloo Daily Bulletin</a> feature on the course.

![Graphics Aquarium]({{ site.url }}/images/graphics_toon.jpg)
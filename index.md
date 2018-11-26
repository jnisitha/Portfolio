---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Nisitha Jayatilleka"
layout: splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /uploads/dumb.jpg
  cta_label: "About me"
  cta_url: "/about/"
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Hi! I am a software engineer and this is my portfolio. Please enjoy your stay here and don't hesitate to contact me if you see something interesting."
intro: 
  - excerpt: 'After getting a BASc from university of Toronto, I am now exploring the fields listed below. Click on one to discover more' # Centered with `type="center"`'

feature_row: 
  - image_path: /uploads/Bikesite.jpg
    alt: "Printer"
    title: "Wheelsntrails Blog site"
    excerpt: "A site for blogging about bike routes." 
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary" 
  #3D Printer
  - image_path: /uploads/printer2.jpg
    alt: "Printer"
    title: "Designing a 3D printer"
    excerpt: "Designed a 3D printer"    
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary" 
  - image_path: /uploads/capstone.jpg
    alt: "Capstone Design"
    title: "Capstone Design U of T"
    excerpt: "Worked with bombardier to design a universal calibration block"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"    #CAD Engine
  - image_path: /uploads/engine2.jpg
    title: "CAD modeled an Engine"
    excerpt: "CAD modelled an engine using solidworks"
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary" 
#feature_row2: #MIsjAM
  - image_path: /uploads/MisJam1.jpg
    alt: "Misjam"
    title: "MisJam 2018"
    excerpt: "Game made by 3 developers at the 2018 Mississauga game jam.  It's filled with tension. An act of balancing defying gravity and invisible wind forces."
    url: "https://en-jay.itch.io/misjam-2018"
    btn_label: "Play Game" #Maybe remove the button
    btn_class: "btn--primary"
#feature_row3:
  - image_path: /uploads/LevelDesign3.jpg
    alt: "LevelDesign"
    title: "Experimental Game"
    excerpt: 'Experimental sandbox area. good for a calming, relaxing, meditative walkaround in the rain.'
    url: "https://en-jay.itch.io/level-design"
    btn_label: "Play Game"
    btn_class: "btn--primary"
#feature_row4:
  - image_path: /uploads/thesis.jpg
    alt: "Thesis"
    title: "Control of Micro-Bots via Magnetic Field Manipulation using a Vision Feedback Control System."
    excerpt: 'Developed a theoretical model of the movement of the micro-bot. Designed a visual feedback control system and implemented it using an Arduino Mega 2560.'
    url: "#test-link"
    btn_label: "Read More"
    btn_class: "btn--primary"
author_profile: true

---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="right" %}
{% include feature_row id="feature_row4" type="center" %}
---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

title: "Nisitha Jayatilleka"
layout: splash
date: 2016-03-23T11:48:41-04:00
header:
  overlay_color: "#000"
  overlay_filter: "0.5"
  overlay_image: /uploads/snowy1.jpg
  cta_label: "About me"
  cta_url: "/about/"
  #caption: "Photo credit: [**Unsplash**](https://unsplash.com)"
excerpt: "Hi! I am a software engineer and this is my portfolio. Please enjoy your stay here and don't hesitate to contact me if you see something interesting."
intro: 
  - excerpt: 'After getting a BASc from university of Toronto, I am now exploring the fields listed below. Click on one to discover more' # Centered with `type="center"`'

feature_row: 
  #BikeSite
  - image_path: /uploads/Bikesite.jpg
    alt: "bikesite"
    title: "Wheelsntrails Blog site"
    excerpt: "A site for blogging about bike routes. Built from ground up on MEAN. Ongoing project. Hosted on AWS using Docker" 
    url: "/bikesite/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  #MisJam
  - image_path: /uploads/MisJam1.jpg
    alt: "Misjam"
    title: "MisJam 2018"
    excerpt: "Game made by 3 developers at the 2018 Mississauga game jam.  It's filled with tension. An act of balancing defying gravity and invisible wind forces."
    url: "/misjam/" #https://en-jay.itch.io/misjam-2018
    btn_label: "Read More" #Maybe remove the button
    btn_class: "btn--primary"
  #Level Design
  - image_path: /uploads/LevelDesign3.jpg
    alt: "LevelDesign"
    title: "Experimental Game"
    excerpt: 'Experimental sandbox area. good for a calming, relaxing, meditative walkaround in the rain.'
    url: "/leveldesign/" #https://en-jay.itch.io/level-design
    btn_label: "Read More"
    btn_class: "btn--primary"
  #Thesis
  - image_path: /uploads/thesis.jpg
    alt: "Thesis"
    title: "Control of Micro-Bots using a Vision Feedback Control System."
    excerpt: 'Fourth year thesis.'
    url: "/thesis/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  #Submarine
  - image_path: /uploads/robosub2.jpg
    alt: "Submarine"
    title: "U of T MDA"
    excerpt: "Mechanical Team Lead of U of T MDA."    
    url: "/submarine/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  #Capstone
  - image_path: /uploads/capstone.jpg
    alt: "Capstone Design"
    title: "Capstone Design U of T"
    excerpt: "Worked with bombardier to design a universal calibration block"
    url: "/capstone/"
    btn_label: "Read More"
    btn_class: "btn--primary"  
  #Printer
  - image_path: /uploads/printer2.jpg
    alt: "Printer"
    title: "Designing a 3D printer"
    excerpt: "Designed a 3D printer"    
    url: "/printer/"
    btn_label: "Read More"
    btn_class: "btn--primary"
  #CAD Engine
  - image_path: /uploads/engine2.jpg
    title: "CAD modeled an Engine"
    excerpt: "CAD modelled an engine using solidworks"
    url: "/engine/"
    btn_label: "Read More"
    btn_class: "btn--primary"  
  #ColorGame
  - image_path: /uploads/WebColorGame.jpg
    title: "Simple Color Game"
    excerpt: "A simple browser game built for coursework."
    url: "/simplegame/"
    btn_label: "Read More"
    btn_class: "btn--primary"  
author_profile: false

---

{% include feature_row id="intro" type="center" %}
{% include feature_row %}
{% include feature_row id="feature_row2" type="left" %}
{% include feature_row id="feature_row3" type="right" %}
{% include feature_row id="feature_row4" type="center" %}
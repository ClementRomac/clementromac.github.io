---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

You can download my complete CV <a href="{{ site.url }}/files/CV_ROMAC_Clement.pdf" download>here <i class="fa fa-download"></i></a>.

## Education
* MSc in Computer Science (Algorithms and Models specialisation), University of Bordeaux, Current
* MSc in Computer Science (with a Data Science specialisation), Ynov Informatique Ingésup Bordeaux, 2019
  * Linear Algebra MOOC from EPFL, edX, 2018 - [Certificate Part 1](https://courses.edx.org/certificates/72bfb71967104d6abc0b98ab45375375) - [Certificate Part 2](https://courses.edx.org/certificates/00fd06dc31a04486b88f8d60d0ae6ff1) - [Certificate Part 3](https://courses.edx.org/certificates/35bd9e3295cd472ebfcc4c789d5e584c)
  * Machine Learning MOOC from Stanford,  Coursera, 2016 - [Certificate](https://www.coursera.org/account/accomplishments/verify/THPBUVAWZ88P)
* High School Diploma with honours, High School Les Iris Lormont, 2014

## Work experience
* March 2020 - Current : Research Intern - Inria
  * Working on an experimental platform for Curriculum Learning applied to Deep Reinforcement Learning algorithms
  
* October 2017 - February 2020 : Part time Data Scientist - Weenove
  * In charge of the Machine Learning R&D
    * Implemented an Automated Machine Learning service
    * Made this service available (Beta) in a Business Intelligence Software (Biwee)
    * Lead the Machine Learning R&D projects
    * Data Science projects
  * Work environment
    * Azure ML Services
    * Docker
    * Python : Pandas, Scikit-Learn, Keras, Jupyter
    * C#

* Summer 2017 : Intern Data Scientist - Scalian
  * Data Science projects
    * Time Series Anomaly Detection
    * Barcode localization on drone pictures with Deep Learning
    * Data Exploration project
  * Work environment
    * Python : Pandas, Scikit-Learn, Flask, Tensorflow, Jupyter
    * C++ : Qt Creator

* June 2016 - May 2017 : Part time Intern Data Scientist - Weenove
  * Machine Learning R&D
    * Implemented an Automated Machine Learning service
    * Made this service available (Beta) in a Business Intelligence Software (Biwee)
  * Work environment
    * Azure ML Studio
    * Python : Pandas, Scikit-Learn
    * R
    * C#

* Summer 2015: Intern Developer - Weenove
  * C# development of a Business Intelligence Software (Biwee)
  * Microsoft environment : Azure, Visual Studio, WCF, TFS
  * Analysis of Open Data
  
## Skills
* Machine Learning
* Deep Learning
* Reinforcement Learning
* Development
  * Python (Tensorflow, Keras, Scikit-Learn, Numpy)
  * C#
  * C++
  * JavaScript
* Others
  * DataBases (SQL, NoSQL)
  * Linux
  * Docker

## Languages
* French : Native Speaker
* English : Advanced
  * TOEIC : 980/990

## Publications
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
## Talks
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
## Teaching
  <ul>{% for post in site.teaching reversed %}
    <!-- {% include archive-single-cv.html %} -->
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
## Service and leadership
* Co-founded and directing the AI working group of Ingésup Bordeaux
* Co-founded and animating the [meetup "Les nuits des réseaux de neurones"](https://www.meetup.com/fr-FR/Les-nuits-des-reseaux-de-neurones/)
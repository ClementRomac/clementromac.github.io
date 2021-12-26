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
* PhD in Computer Science, Hugging Face & Inria, University of Bordeaux, 2022 - Current
* MSc. in Computer Science (Algorithms and Models specialisation), University of Bordeaux, 2020
* Degree in Computer Science engineering (with a Data Science specialisation), Ynov Informatique Ingésup Bordeaux, 2019
  * Linear Algebra MOOC from EPFL, edX, 2018 - [C1](https://courses.edx.org/certificates/72bfb71967104d6abc0b98ab45375375) - [C2](https://courses.edx.org/certificates/00fd06dc31a04486b88f8d60d0ae6ff1) - [C3](https://courses.edx.org/certificates/35bd9e3295cd472ebfcc4c789d5e584c)
  * Machine Learning MOOC from Stanford,  Coursera, 2016 - [Certificate](https://www.coursera.org/account/accomplishments/verify/THPBUVAWZ88P)
* High School Diploma with honours, High School Les Iris Lormont, 2014

## Work experience
* January 2022 - Current: PhD student - Hugging Face and Inria (FLOWERS team)
  * Studying how autonomous Deep RL agents can leverage large Language Models

* September 2020 - December 2021: Research Engineer - Inria (FLOWERS team)
  * Working on an experimental platform to apply curiosity-driven algorithms to automatic scientific discovery in complex systems (e.g. self-organizing)

* March 2020 - August 2020: Research Intern - Inria (FLOWERS team)
  * Worked on [TeachMyAgent](https://arxiv.org/abs/2103.09815), a benchmark platform for Automatic Curriculum Learning applied to Deep Reinforcement Learning algorithms
    * Created procedurally generated Box2D environments and embodiments
    * Implemented state-of-the-art Automatic Curriculum Learning methods
    * Built a benchmark setup and benchmarked the methods
    * *Paper accepted at ICML 21'*
  
* October 2017 - February 2020 : Part time Data Scientist - Weenove
  * In charge of the Machine Learning R&D
    * Implemented an Automated Machine Learning service
    * Made this service available (Beta) in a Business Intelligence Software (Biwee)
    * Lead the Machine Learning R&D projects
    * Data Science projects

* Summer 2017 : Intern Data Scientist - Scalian
  * Data Science projects
    * Time Series Anomaly Detection
    * Barcode localization on drone pictures with Deep Learning
    * Data Exploration project

* June 2016 - May 2017 : Part time Intern Data Scientist - Weenove
  * Machine Learning R&D
    * Implemented an Automated Machine Learning service
    * Made this service available (Beta) in a Business Intelligence Software (Biwee)

* Summer 2015: Intern Developer - Weenove
  * C# development of a Business Intelligence Software (Biwee)
  * Analysis of Open Data
  
## Skills
* Machine Learning, Deep Learning, Reinforcement Learning
* Development
  * Python (Tensorflow, Scikit-Learn, Numpy)
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
* Co-founded and directed (until 2019) the AI working group of Ingésup Bordeaux
* Co-founded and animated (until 2019) the [meetup "Les nuits des réseaux de neurones"](https://www.meetup.com/fr-FR/Les-nuits-des-reseaux-de-neurones/)
* Co-organizer of the ["Bordeaux Machine Learning Meetup"](https://www.meetup.com/fr-FR/Bordeaux-Machine-Learning-Meetup/)
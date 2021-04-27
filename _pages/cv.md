---
layout: archive
title: "CURRICULUM VITAE"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

The detailed PDF verison of my CV can be found here - [CV](\files\NikithaRao_CV.pdf){: .btn .btn--inverse}

Research Interests
------
I seek to build systems using data-driven techniques.

* Domains - Data Science, Machine Learning, Data Analysis and Machine Learning for Software Engineering, Information Retrival, Data Mining, Web Search Log Analysis


[Publications](https://raonikitha.github.io/publications/){:target="_blank"}
------

  <ul>{% for post in site.publications reversed %}
      {% if post.venue != '' %}
          {% include archive-single-cv.html %}
      {% endif %}
  {% endfor %}</ul>

[Preprints](https://raonikitha.github.io/publications/){:target="_blank"}
------
  <ul>{% for post in site.publications reversed %}
      {% if post.venue == '' %}
          {% include archive-single-cv.html %}
      {% endif %}
  {% endfor %}</ul>


Patents
------
* <i>'Identification of Content Gaps based on Relative User-Selection Rates between Multiple Discrete Content Sources'</i> filed with the USPTO (October 16, 2020). <br>
  * Co-inventors: Chetan Bansal, Junia George, Casey Gossard, Dung Nguyen, Dave Ludwig, Curtis Anderson.
* <i>'ExtraQuery Context-Aided Search Intent Detection'</i> filed with the USPTO (October 9, 2020). <br>
  * Co-inventors: Chetan Bansal, Joe Guan, Mark Wilson-Thomas, Nachiappan Nagappan, Thomas Zimmermann.
* <i>'Automatic Recognition of Entities Related to Cloud Incidents'</i> filed with the USPTO (June 19, 2020). <br>
  * Co-inventors: Manish Shetty, Chetan Bansal, Sumit Kumar, Nachiappan Nagappan, Thomas Zimmermann.


Education
------
* Bachelor's in Technology (B.Tech) from [PES University](https://cs.pes.edu/) (previously known as PES Institute of Technology or PESIT)<br>
  * Major - Computer Science and Engineering
  * Specialization - Data Science



Work Experience
------

* July 2019 - Present: [Research Fellow](https://www.microsoft.com/en-us/research/academic-program/research-fellows-program-at-microsoft-research-india/)
  * [Microsoft Research Lab - India](https://www.microsoft.com/en-us/research/lab/microsoft-research-india/)
  * Mentor - Chetan Bansal
  * Project Domains - Search Insights, AI for DevOps [(Project Sankie)](https://www.microsoft.com/en-us/research/project/sankie/)

* January 2019 - June 2019: Research Intern
  * [Microsoft Research Lab - India](https://www.microsoft.com/en-us/research/lab/microsoft-research-india/)
  * Advisor - Dr. Sreangsu Acharyya
  * Problem Statement - Designed an algorithm to learn rankings under extreme class imbalance by maximizing the partial area under ROC curve.

* Summer 2018: Research Intern
  * [Carnegie Mellon University, Pittsburgh](https://www.cmu.edu/)
  * Advisor - [Dr. Shawn Blanton](https://cylab.cmu.edu/directory/bios/blanton-shawn.html)
  * [Problem Statement](https://raonikitha.github.io/projects/2018-07-25-HardwareObfuscation) - Analysis of various patterns in the input-output sequences of various obfuscated circuits to define a metric to quantify the level of obfuscation in a circuit using machine learning techniques.  

* Summer School Program 2017
  * Was among the youngest students selected for the 5th Summer School Program conducted by the Computer Science and Automation (CSA) Department at the Indian Institute of Science, India. (July '17)  

* Summer 2017: Summer Research Intern
  * [Microsoft Innovation Lab](https://clubs.pes.edu/microsoft-innovation-lab){:target="_blank"}
  * Worked in the domain of Virtual Reality and Machine Learning.
  * Problem Statement - Designed a system to track progress in children having cerebral palsy by gamifying the physiotherapy process.

* Core member in organizing a course on analysis and thinking - 2017 that was a week-long program in which I delivered a workshop on logical thinking. (July '17) 

  


[Projects](https://raonikitha.github.io/projects/){:target="_blank"}
------

  <ul>{% for post in site.projects reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Achievements
------
* Won the Best Student Award in the Computer Science Department for the graduating class of 2019 at PES University.  

* Five time recipient of the CNR Rao scholarship for demonstrating academic excellence in Computer Science Department, PES University, India. 

* Winner at Datathon a data analytics based-hackathon at PES University, India. (2018) 

* Runner up at the TechQuiz in the Summer School Program at Computer Science and Automation department, Indian Institute of Science, Bangalore, India. (July 2017) 


<!-- Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
 -->
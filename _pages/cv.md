---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Academic Details</title>
    <style>
    body {
            font-family: Arial, sans-serif;
            background-color: #f8f8f8;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #7252AA !important;
            margin-bottom: 30px;
        }
        .service {
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            margin-top: 20px;
        }
        .service-item {
            width: calc(33.33% - 20px);
            margin-bottom: 20px;
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: all 0.3s ease;
            font-size: 0.8em !important;
        }
        .service-item:hover {
            transform: translateY(-5px);
        }
        .service-item img {
            width: 50%;
            height: auto;
            border-radius: 50%;
        }
        .service-content {
            padding: 20px;
        }
        .service-title {
            font-size: 20px;
            font-weight: bold;
            margin-bottom: 10px;
            color: #7252AA !important;
        }
        .service-description {
            color: #666;
        }
    </style>
</head>
<body>

<div class="container">
    <h1>Academic Details</h1>
    <div class="service">
        <div class="service-item">
           <center>
            <img src="https://drive.google.com/thumbnail?id=1tJYQ0ITs7M69LJ7YM9eoW_zoL7Nw4h_p" alt="Student 1" /></center>
            <div class="service-content">
                <div class="service-title">PhD</div>
                <div class="service-description">Major:  Machine Learning, Deep Learning.</div>
                <p>Supervisors:Prof: Wu Zhang   .</p>
                <p>Dates: 2014 - 2019 .</p>
                <p>Shanghai University, China .</p>
            </div>
        </div>
        <div class="service-item">
            <center><img src="https://drive.google.com/thumbnail?id=16RrUgu5xAcZXSHcZG0yIlwPzRjxHUtH_" alt="Student 2" /></center>
            <div class="service-content">
                <div class="service-title">MSIT</div>
                <div class="service-description">Major:Computer Wireless Network</div>
                <p>Supervisors: Dr Fazal Haidi.</p>
                <p>Dates: 2007-2010.</p>
                <p>Agriculture University Peshawar</p>
            </div>
        </div>
        <div class="service-item">
            <center><img src="https://drive.google.com/thumbnail?id=1WeD-cEoCLD4bPMt1-BU09O8TmdwLLPVe" alt="Student 3"/></center>
            <div class="service-content">
                <div class="service-title">MIT</div>
                <div class="service-description">Major:Information Technology .</div>
                <p>Supervisors: Mr Jawad.</p>
                <p>Dates: 2004-2007.</p>
                <p>Kohat University of Science and Technology.</p>
            </div>
        </div>
        <div class="service-item">
            <center> <img src="https://drive.google.com/thumbnail?id=1uWJLerp01EGQAw4--UeD1VrsLSUr6QMi" alt="Student 3"/></center>
            <div class="service-content">
                <div class="service-title">Bsc </div>
                <div class="service-description">Major:Math and Computer Science.</div>
                <p>Forward Degree College Hayatabad, Peshawar, Pakistan</p>
                <p>Dates:2000-2004.</p>
            </div>
        </div>
        <div class="service-item">
            <center><img src="https://drive.google.com/thumbnail?id=1kEjQCqY4eNAvjopialqoj-fWpkgTnJ1L" alt="Student 3"/></center>
            <div class="service-content">
                <div class="service-title">Fsc</div>
                <div class="service-description">Major:Pre-Engineering </div>
                <p>Parachinar Degree College,Pakistan.</p>
                <p>Dates: 1998-2001</p>
            </div>
        </div>
        <div class="service-item">
            <center> <img src="https://drive.google.com/thumbnail?id=11Yo77RPMIwfhapYrEiEQV0ykQj_ub07y" alt="Student 3"/></center>
            <div class="service-content">
                <div class="service-title">Metrics</div>
                <div class="service-description">Major:Science</div>
                <p>Kirman High School Parachinar,Pakistan</p>
                <p>Dates:1998-Annual</p>
            </div>
        </div>
    </div>
</div>

</body>
</html>


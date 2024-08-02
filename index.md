---
layout: default
title: Home
order: 0
---
![image](thinh.jpg){: style="float: left; margin-right: 20px; margin-bottom: 10px" : width="140"}
## [Thinh Hoang Dinh, Ph.D. (Jensen Hoang)](about.md) 
I am a postdoctoral researcher at the French Civil Aviation University (ENAC) Optimization Laboratory. This website hosts my personal blog, where I share my research, projects, and thoughts on various topics. It also serves a [Graph RAG](https://microsoft.github.io/graphrag/) powered by GPT 4o mini.

[See more](about.md).

<div style="margin-top: 40px;"></div>

# Contact
- Email: [thinh.hoangdinh@enac.fr](mailto:thinh.hoangdinh@enac.fr).

{% comment %}
<span style="color: red">I'm available for a Postdoctoral Researcher position, preferably in the United States or in France. My complete CV is [here](cv.pdf).</span>
{% endcomment %}

{% comment %}
<span style="color: blue">**I'm available for a Postdoctoral Researcher position from October '23, preferably in the United States, United Kingdom and Australia. My complete CV is [here](cv.pdf).**</span>
{% endcomment %}

# Research Interests
My doctoral dissertation focused on function approximations and signal processing, specifically applied to vehicle trajectory data. I've also explored sparse optimization, large language models, and theoretical reinforcement learning.

For the moment, I'm current working on the [SESAR's DeepFlow Project](https://www.sesarju.eu/news/eur-26-million-investment-sesar-ju-unveils-new-projects-smarter-air-traffic-management) under guidance of Pr. Daniel DELAHAYE. Our aim is to develop a transparent and interpretable machine learning method to enhance air traffic management.

<div style="margin-top: 40px;"></div>

# Highlight Work

![image](energyfield.jpg){: style="float: left; margin-right: 10px" : width="90%"}
{: .left-50}

## Helmholtz Model
{: .right-50}
The project attempts to leverage the sparse activation patterns of optimization constraints in order to simplify a large optimization problem into many smaller subproblems. This creates an alternative approach to solving the Hamilton-Jacobi-Bellman equation in reinforcement learning. As a result, the Helmholtz model can be used to align the model without the cost of generating a large amount of synthetic data.

<div style="height: 100px"></div>
{: .right-50}

{: style="clear: both"}
{: style="clear: both"}

![image](stratoeye.jpg){: style="float: left; margin-right: 10px; margin-bottom: 130px" : width="90%"}
{: .left-50}

## StratoEye (Montéllama Codex + Web Platforms)

This project aims to leverage the power of large language models in air traffic commands comprehension and bridge the gap between Language Understanding (LU) and Trajectory Signal Processing (TSP).

This work is realized under guidance of Pr. Daniel Delahaye (ENAC), Pr. Pierre Maréchal (IMT), Laurent Lapasset (ENAC) and in collaboration with Huijuan Yang (Civil Aviation Flight University of China).

[Long demonstration video](https://youtu.be/5iVBMxKoQzo?si=0W9BcUABG7KrwigL)

[Short demonstration video](https://www.youtube.com/watch?v=SjR---olr7k)

[Project Description](StratoEyeSite.pdf)

<div style="height: 20px"></div>
{: .right-50}

{: style="clear: both"}
{: style="clear: both"}

![image](scodec.jpg){: style="float: left; margin-right: 10px" : width="90%"}
{: .left-50}

## Spherical Codec
The codec reduces the Channel Busy Ratio (CBR) for CAM messages exchange by up to 2.5 times.
A European Patent has been filed since October '22.
{: .right-50}


{: style="clear: both"}

![image](nonoisellh.png){: style="float: left; margin-right: 10px" : width="90%"}
{:.left-50}

## Real-time Anomaly Detection
{: .right-50}
Perform real-time estimation of the "probability of anomaly" for early warning of dangerous scenarios in Air Traffic Control.
{: .right-50}

<div style="height: 80px"></div>
{: .right-50}


{: style="clear: both"}

![image](paymehardware.jpg){: style="float: left; margin-right: 10px" : width="90%"}
{:.left-50}

## Leisure Project: A Productivity Tool
{: .right-50}
Using React Native, React and Firebase, I designed a small Raspberry Pi-powered smart display that shows me the to-do list with Pomodoro functions. By keeping track of the time until the next calendar event, I am also prevented from forgetting to attend meetings. By doing so, I am able to increase my productivity and stay on top of dozens of hundred tasks throughout the day.
{: .right-50}
Give it a spin: [Ordoscope Beta](https://ordoscope.paymemobile.fr)
{: .right-50}
{: style="clear: both"}

# Recent Posts
{: style="clear: both"}
{% for post in site.posts limit:5 %}  
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}  
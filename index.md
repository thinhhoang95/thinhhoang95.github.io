---
layout: default
title: Home
order: 0
---
![image](thinh.jpg){: style="float: left; margin-right: 20px; margin-bottom: 30px" : width="150"}
## Thinh Hoang Dinh
I am a PhD student at the French Civil Aviation University (ENAC) Optimization Laboratory, affiliated with the Artificial and Natural Intelligence Toulouse Institute (ANITI) and NXP Semiconductors Toulouse, France. Currently, I am conducting research in the field of **vehicular communications, signal processing and machine learning in Intelligent Transportation Systems** under supervision of Pr. Daniel Delahaye (ENAC) and Pr. Pierre Maréchal (Toulouse Institute of Mathematics).

## Contact
- Office: Z133, École Nationale de l'Aviation Civile, 7 avenue Édouard Belin, 31055 Toulouse, France.
- Email: [thinh.hoang-dinh@univ-toulouse.fr](mailto:thinh.hoang-dinh@univ-toulouse.fr).

<!-- <span style="color: blue">**I'm available for a Postdoctoral Researcher position from November 2023, preferably in Europe or the United States. My complete CV is [here](cv.pdf).**</span> -->

## Interests
My research focuses on **Probabilistic Graph Models (PGM) of Bayesian Statistics, Signal Modeling using Stochastic Processes and Large Language Models in Time Series Processing**. I also work on ITS-G5 V2X.

# Highlight Work

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


{: style="clear: both"}

![image](paymehardware.jpg){: style="float: left; margin-right: 10px" : width="90%"}
{:.left-50}

## Leisure Project: A Productivity Tool
{: .right-50}
Using React Native, React and Firebase, I designed a small Raspberry Pi-powered smart display that shows me the to-do list with Pomodoro functions. By keeping track of the time until the next calendar event, I am also prevented from forgetting to attend meetings. By doing so, I am able to increase my productivity and stay on top of dozens of hundred tasks throughout the day.
{: .right-50}

{: style="clear: both"}

# Recent Posts
{: style="clear: both"}
{% for post in site.posts limit:5 %}  
  <li><a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>  
{% endfor %}  
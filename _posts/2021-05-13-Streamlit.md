---
layout: page
title: "I ❤️ Streamlit"
subtitle: ""
date:   2021-05-13 21:21:21 +0530
categories: data
---

I was a little late to the party, but I have finally abandoned front-end web-development tools like Flask, JS, and HTML 
for the clean look and responsive features of Streamlit.  I couldn't be more satisfied with my decision. If you're unfamiliar,
Streamlit is a phenomenal open-source app framework for Data Analysis and Machine Learning. It's accessed through a Python Library 
that's simple to learn because of the great documentation and a growing pool of community-created applications with linked code bases. 
The company has a banner announcing Series B funding from Sequoia,
so the team unsurprisingly the Streamlit devs and competent and help on their discussion forums.

I first started using Streamlit in fall 2020 when someone in my cohort mentioned it in a Slack channel. When checking it out
I was knocked over by how so little code was required to create a kickass app. Once installed you can run their demo from the 
command line that lets the user analyze NYC Uber Ridesharing data. If you can believe it, this took less than 120 lines of code to deploy.

```ps
pip install --upgrade streamlit
streamlit run https://raw.githubusercontent.com/streamlit/demo-uber-nyc-pickups/master/streamlit_app.py
```
  
\
![Final App Animation](https://github.com/streamlit/streamlit/raw/develop/docs/_static/img/uber_horiz.gif "Final App Animation")
\
You can run the app locally, but you have several options to launch on the web if required. I initially tried hosting on Heroku, but 
the much easier route is to use the Streamlit Sharing platform. It's currently in the Beta phase; my access request took only a few weeks to grant.
As mentioned above, they recently raised their Series B, so they are well-capitalized to deliver Sharing sooner rather than later. It's simple, you
connect the platform to a GitHub repo that has your python file and data. 

The first project I shared was an NHL Team wager application for exploring scenario-based betting analytics based on selected criteria. It updates 
daily and requires some data processing between selections, but the app is responsive and dynamic as you can cache data. The web design is a little tricky, but the library includes enough tools for
essential features and aesthetics. What's awesome is that they allow you to go outside of their standard designs to nest HTML and CSS into one of the subclasses.
Having brushed up on my HTML recently, I am was able to add a few customizations without much fuss.  Feel free to check it out, I have dropped a sample
screen capture below. However, it does go to sleep if it goes unused for a week and the off-season is approaching.


\
![Screen Grab](https://jfm-data.github.io/assets/img/nhl_wager_team.png "My First project")

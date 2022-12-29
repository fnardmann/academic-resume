---
title: Progress Tracker for Interval Running
summary: Generate a plot to monitor your progress running intervals. This creates a boxplot for each interval session and shows them side-by-side to oversee your progress over time.
tags:
- Other
date: "2022-12-28T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Example plot showing boxplots from 5 interval sessions
  focal_point: Smart

links:
- icon: github
  icon_pack: fab
  name: Project
  url: https://github.com/fnardmann/run-stats
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

---

Technologies used: **Python** | **Matplotlib** | **Numpy** | **Fitparse**

This is a little script to track and visualize your progress while doing interval training. The neccessary `.fit` files can be exported via services like [Garmin-Connect](https://connect.garmin.com/modern/). Just collect and download all your interval workouts over a specific time period and get started by running the `.fit` script.

To visualize several intervals of a single session equally a boxplot is used. The red line in the middle of the boxplots corresponds to the median of all given interval paces. The upper and lower bound of the pink boxes correspond to the upper (75th) and lower (25th) quartile oft the given data. For an effictive interval workout your paces for each interval should be somehow equal, in this case the boxes would be relative small indicating a smaller variance.

To get comparable results the workouts should have similiar properties (e.g. interval length, route, warmup, length). Of course there are some other factors like fatigue or just daily fitness which can influence the tempo of your intervals, but all in all you should be abled to track if you are improving over time or not. The example contains 5 sessions with 6x400m interval session. All these session were run on the same route so the results would be comparable. Of course it would be even better if you could run your interval sessions on a track to eliminate even more external factors.
# 911 Emergency Call Analysis

This project analyzes a dataset of 911 emergency calls using Python to uncover patterns in call types, call volumes, locations, and time-based trends.

# Project Overview

The goal of this project is to explore:
- The most common reasons for emergency calls (EMS, Fire, Traffic)
- When calls are most frequent (hour, day, month)
- Geographic hotspots by ZIP code and township
- Trends that can inform emergency response strategies

# Key Features

- Grouped analysis by call reason, time, and location
- Time series plots showing call volumes over time
- Heatmaps and countplots visualizing patterns
- Cleaned and processed timestamp and location data

# Tools Used

Python
  - Pandas
  - Matplotlib
  - Seaborn
  - Jupyter Notebook

# Dataset Overview

The dataset includes 911 call records with fields such as:
- timeStamp
- title (reason for call)
- zip, twp (location details)
- lat, lng (coordinates)

# Insights

- EMS-related calls were the most frequent across most ZIP codes
- Call volumes peak during late afternoons and weekdays
- Some townships report disproportionately higher emergency activity

This project demonstrates how Python can be used for real-world emergency data analysis to support smarter decisions in public safety.

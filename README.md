# Fitness Tracker Insights Dashboard

This is a dashboard in which contains a sample of 120 users in 28 days.

**Live dashboard:** https://gbordjuerpriscilla.github.io/fitness-tracker-dashboard/

## What I found
In those 28 days, average daily steps fell by 1.7%, but the trend is stable. 8 of the users which is 6.7% dropped to approximately 30% of their normal steps for 5 days in a row.

## What's in the dashboard
- Weekly trend charts for steps, sleep and calories
- Top 10 most active users
- A flag for users whose steps stayed below 50% of their own normal for 3+ days in a row

## How I built it
- Python (pandas) in Google Colab for the data and the flag logic. The notebook is in this repo.
- HTML, CSS and Chart.js for the dashboard, hosted on GitHub Pages.

## What was hard
Cleaning the data set and producing the charts was a bit hard for me.
Also creating the dashboard was a bit confusing and difficult.

## Note
The data is simulated (120 users, 28 days). It is not real user data.

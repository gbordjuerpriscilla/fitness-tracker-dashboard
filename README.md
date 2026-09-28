# fitness-tracker-dashboard
# Fitness Tracker Insights Dashboard

An interactive dashboard analysing daily steps, sleep and calories for 120 users over 4 weeks.

Live dashboard: https://gbordjuerpriscilla.github.io/fitness-tracker-dashboard/

## Top insight
Average daily steps fell only 1.7% from week 1 to week 4, so the overall trend looks stable. But 8 users (6.7%) dropped to about 30% of their normal steps for 5 days in a row. The average can hide users who are slipping, so the team should follow up with them early.

## What the dashboard shows
1. Weekly trend charts for steps, sleep and calories
2. "Most Active Users" leaderboard (top 10 by average daily steps)
3. Flag for users whose steps stayed below 50% of their own normal for 3+ days in a row

## How it was built
Python (pandas, NumPy, matplotlib): It was made in Google Colab which generated the dataset, computed weekly averages, built the leaderboard and the flag logic.
**HTML, CSS and Chart.js** for the dashboard page.It was hosted on GitHub Pages

## Note on the data
The dataset is simulated sample data (120 users, 28 days, 8 users given a drop-off on purpose so the flag has something to catch). It is not real user data.

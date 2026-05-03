# No Show Analysis

## What I looked at
I wanted to see what makes patients miss their appointments
and if SMS reminders actually help.

## Data
Used a dataset from Kaggle with about 110,000 appointments.
File: KaggleV2-May-2016.csv

## How to run it
pip install pandas matplotlib seaborn in terminal then just run the notebook

## What I found
About 28% of patients missed their appointment
Younger people (19-35) had the highest no show rate at 34.2%
Older patients (65+) were the most reliable at 20.9%
SMS reminders help a little but not a ton (29.4% vs 27.6%)
Gender didn't really matter much

## Conclusions
Younger patients are the biggest challenge for clinic scheduling.
Reminder efforts should be focused on that age group rather than
sending SMS to everyone equally. Older patients tend to show up
reliably without much intervention.

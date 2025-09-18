# Project-1-ITCS-4122
## Introduction
Flight delays are more than an inconvenience, they affect passenger satisfaction, airline reputation, and even the economy. For airlines, frequent delays can cause damages in the company's credibility, operational costs, etc.

Air travel remains the safest and fastest way to get around the world, and with millions of people depending on it daily, there is little room for error. Many people utilize air travel in many different ways whether it's for a business trip, vacation, visiting loved ones, and many more reasons. Using a 10-year dataset of airline delays, we explore:

* Which airlines and airports face the most challenges
* What Causes delays
* The ratio between delays and cancellations
  
By uncovering these patterns, we aim to shed light on the operational challenges airlines face and the broader implications for passengers and the aviation system as a whole.
## Introducing the Data
The dataset for this project was obtained from Kaggle. Over the course of 10 years from Aug 2013-Aug 2023, the dataset focuses on travel arrivals and delays. Furthermore, it provides different metrics to help such as carriers, weather, security, and late arrivals. With over 15k rows and 21 columns in the total dataset, this provides the public with a better understanding of the overall airline industry.

## Pre-Processing
Before narrowing down the dataset, I ensured that there were not missing or inconsistent data that could have been possibly overlooked. I accomplished this by checking for null values in all the rows. Upon inspection, I noticed that there were some null values in the rows, so I proceeded to remove them. Next, I decided to check for any duplicate rows to ensure the dataset had all unique values. Next, I decided to run the dataset again to make sure I didn't miss any null values. After checking, I discovered no null or duplicate values, indicating the dataset was clean and ready for analyzing. Next, I started to narrow down my dataset. To focus on my questions pertaining to delays, I decided to narrow down the data which originally had 21 columns. I decided to remove [carrier,nas_ct,airport_name ] from the columns. Finally, I double checked the dataset to ensure that the correct columns were removed, and there were still no missing values. This ensures my dataset is clean and ready to address the questions being asked.

## Visualization
I decided to go with those design choices because I felt like they were the easiest to display while trying to get my point across. The stacked bar charts helped visualize which factors affected the most airlines, but also the airports as well. Furthermore, I decided the pie chart was the best at explaining overall delay, because although it is a smaller stat, I felt like it was important to display for those interested.

## Reflection
Overall I think I did a good job for my first project. One this I would like to change, however, would be providing more visuals. The visuals I have right now gets the point across, however, I felt like I could've done a better job doing so. Other than that, I might expand on this project even more and make a dashboard of my findings in my free time.

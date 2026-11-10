# A1 — Working with Open Data

**Dataset:** Burke-Gilman Trail counter north of NE 70th St  
**Source:** https://data.seattle.gov/d/2z5v-ecg8  
**Date accessed:** October 13, 2026  
**Data analyzed:** 2019  
**License/terms of use:** Public Domain. The dataset is provided by the City of Seattle and is publicly available for use and analysis. Source attribution is included above.

## Project Overview

This project analyzes bicycle and pedestrian traffic on Seattle's Burke-Gilman Trail using publicly available hourly counter data from 2019. The goal is to understand how people use the trail throughout the day and whether their behavior suggests commuting, recreation, or both.

## Questions I Asked

1. When is the trail busiest and quietest?
2. Do cyclists and pedestrians use the trail at different times of day?
3. Is there evidence that people use the trail for commuting rather than only recreation?
4. How does cycling direction change between morning and evening?

## How to Re-run

1. Open `A1.ipynb` in Jupyter Notebook or JupyterHub.
2. Make sure Python has `requests`, `pandas`, and `matplotlib` installed.
3. Run all cells in order.
4. The notebook retrieves data from Seattle's Open Data API, processes hourly traffic counts, and generates visualizations.

## Data Limitations

The main limitation of this dataset is that the counter records how many people pass through the trail and in which direction, but it does not explain why they are traveling. This directly affects my interpretation of the weekday and weekend cycling patterns. For example, weekday traffic peaks around 8 AM and 5 PM, which I interpreted as evidence of possible commuting. However, some cyclists might be exercising before or after work rather than commuting. Similarly, the weekend peak around 1 PM could reflect recreational cycling, but it might also include people traveling to work or running errands.

The directional data presents a similar limitation. More cyclists travel north in the morning and south in the evening, but the counter cannot establish whether these are the same individuals making return trips. Therefore, the patterns suggest that the Burke-Gilman Trail supports both transportation and recreation, but they do not prove the purpose of individual trips. To investigate this further, I would need additional information, such as surveys asking cyclists about their destinations and reasons for using the trail.

## AI Assistance

I used ChatGPT to help generate and understand Python code, work with pandas, create visualizations, and organize my analysis. I also used it to help revise written interpretations, particularly the explanations of weekday versus weekend cycling patterns and changes in cycling direction.

I ran the code in JupyterHub and reviewed the resulting tables and graphs. During revision, I expanded my discussion of what the traffic patterns might suggest about people's behavior and clarified the limitations of concluding commuting from counter data alone.

The `A1.ipynb` notebook includes additional documentation of my AI use, including an excerpt of my original prompt, an explanation of how I used the assistance, and a description of the changes made. The documented prompt is an excerpt rather than a complete transcript.
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

The dataset only represents one location on the Burke-Gilman Trail, so its results may not reflect usage across the entire trail. Additionally, the counter records traffic volume and direction but cannot identify whether individual users are commuting or exercising. Missing observations or sensor errors may also affect the accuracy of the results.

## AI Assistance

ChatGPT was used to assist with Python code for data grouping, visualization, and interpretation. The generated code was executed and its results reviewed in JupyterHub. The notebook includes additional documentation of AI assistance.

# Data Visualization Project

## Data

The data I propose to visualize for my project is [Climate change and Agriculture Dataset from Kaggle](https://www.kaggle.com/datasets/waqi786/climate-change-impact-on-agriculture).


## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:
- Analyze Climate Trends Over Time
- Explore how variations in climate variables affect agricultural productivity
- Compare Agricultural Productivity Across Regions
- Investigate how specific climate factors (temperature vs. rainfall, ...) impact different crop types
- Discover how crop diversity in a region affects resilience to climate changes

## Sketches

![sketch1](images/cs573_5-1.jpg)
![sketch2](images/cs573_5-2.jpg)
![sketch3](images/cs573_5-3.jpg)

##### 1. Climate & Crop Yield Over Time
- Task: Analyze Climate Trends Over Time
- This visualization focuses on long-term trends in climate factors like temperature and precipitation, along with crop yields, allowing users to examine changes and correlations over the years.
##### 2. Pesticide & Fertilizer vs. Soil Health & Crop Yields
 - Task: Explore how variations in climate variables affect agricultural productivity
 - By visualizing pesticide use, fertilizer application, soil health, and crop yields, this chart helps users investigate how these factors impact agricultural productivity, highlighting potential effects on soil quality and yield outcomes.
##### 3. Crop Yields & Extreme Weather by Region
 - Task: Compare Agricultural Productivity Across Regions
 - This heatmap shows crop yields and extreme weather events by region over time, allowing users to compare productivity across different areas and understand how regional variations in extreme weather affect yields.


## Prototypes

I’ve created a proof of concept visualization of this data. It's a multi-line chart and it shows trends in crop yield, temperature, and precipitation over time from the year 2000 to 2005. Each line represents a different variable, allowing for an analysis of how these factors change over time and potentially relate to one another.

[![image](images/pseudo_viz.png)](https://vizhub.com/wyy-47/pseudovizforclimatedata)

## Open Questions

- Combining climate and crop data with different units and scales may require complex normalization for meaningful comparisons.
- Implementing dynamic filters and region selectors could be technically challenging, potentially affecting performance with larger datasets.

## Milestones

**Week 1:** Collect, clean, and normalize all required datasets, including climate, crop yield, and regional shapes.

**Week 2:** Build basic versions of each chart without interactivity, ensuring data alignment and accuracy.

**Week 3:** Add filters, region selection, and hover details to enhance exploration and usability.

**Week 4:** Refine visualizations, conduct user testing, and finalize adjustments for a polished, user-ready system.
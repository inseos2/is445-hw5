---
title: UFO Visualization
---

# UFO Visualization

## Plot 1

<iframe src="plot1.html" width="900" height="500"></iframe>

### Description

Plot 1 is a scatter plot that visualizes UFO sightings by longitude and latitude. I used position encodings for location and color encoding for duration_seconds to show differences in duration. I chose the viridis color scheme because it clearly shows variation in quantitative values. I parsed the date column when reading the dataset so it would be in a proper datetime format instead of a string. This makes it easier to work with time-based data if needed. I also added a brush selection so users can interact with the plot and explore patterns in specific regions.

---

## Plot 2

<iframe src="plot2.html" width="900" height="500"></iframe>

### Description

Plot 2 is a histogram showing the distribution of UFO sighting duration in seconds. I used binning to group duration values and count the number of observations in each range. This makes it easier to see that most sightings are short while some extreme values act as outliers. I did not use a color encoding because the goal of this plot is to focus on the distribution of a single variable. I did not apply additional transformations beyond reading the data and using binning.

---

## Interactivity

The interactivity in Plot 1 lets users drag over the chart to select points. This makes it easier to focus on a smaller area and notice patterns in that part of the data. This makes the visualization more clear and interactive compared to a static plot.

---

## Links

- [Data](https://raw.githubusercontent.com/UIUC-iSchool-DataViz/is445_data/main/ufo-subset-spring2023.csv)
- [Notebook](https://github.com/inseos2/is445-hw5/blob/main/HW%205.1.ipynb)

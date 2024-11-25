---
layout: post
title: "Data Visualization Homework"
date: 2024-11-24
categories: assignments
---

## Visualizations

### Visualization 1: Interactive Map
This map shows the distribution of buildings across different cities in Illinois. The map is interactive, allowing users to filter by building status or usage description. We used circle size to encode square footage and color to represent building status. The map provides insights into urban density and building types.

**Design Choices**:
- **Encodings**: Circle size for square footage, color for building status.
- **Interactivity**: Filters for `Usage Description` and `Bldg Status`.

**Data Transformations**:
We cleaned the data by removing null values in "City" and aggregated square footage by city.

**[The Data](https://github.com/yvonneyangyan/yvonneyangyan.github.io/main/building_inventory.csv)**  
**[The Analysis](https://github.com/yvonneyangyan/yvonneyangyan.github.io/blob/main/building_visualizations.ipynb)**

### Visualization 2: Bar Chart
This bar chart compares total square footage across different building statuses. The interactivity includes a dropdown to switch metrics and a slider to filter by acquisition year.

**Design Choices**:
- **Encodings**: Bar height for total square footage, categorical axis for building status.
- **Interactivity**: Dropdown for metrics, slider for year filtering.

**Data Transformations**:
We grouped the data by "Bldg Status" and calculated the sum of square footage. Missing values in "Year Acquired" were imputed using the median.

**[The Data](https://github.com/yvonneyangyan/yvonneyangyan.github.io/main/building_inventory.csv)**  
**[The Analysis](https://github.com/yvonneyangyan/yvonneyangyan.github.io/blob/main/building_visualizations.ipynb)**

## Publishing
To view the visualizations, check out the live demo on [GitHub Pages](https://yvonneyangyan.github.io/).

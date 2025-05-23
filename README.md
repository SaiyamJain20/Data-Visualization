# Ultramarathon Performance Analytics Dashboard
## Overview
This data visualization project provides an interactive dashboard to explore ultramarathon race data, showcasing performance metrics, demographic information, and trends over time. The dashboard includes multiple visualizations to help understand patterns in long-distance running events.

## Features
- Home Dashboard: Overview of ultramarathon statistics including completion rates, average finish times, and demographic distributions
- Finishers Data: Interactive line charts showing the number of finishers over years by distance category and gender with age distribution analysis
- Speed vs. Age Analysis: Animated visualization comparing running speeds across different age groups for both male and female athletes
- Performance Analysis: Global choropleth map displaying performance metrics by country with supporting demographic breakdowns
## Data
The project analyzes ultramarathon race data including:

- Participant demographics (age, gender, nationality)
- Race distances (50km to 1000+km)
- Performance metrics (finish times, completion rates)
- Historical trends over time

## Technology Stack
- D3.js (v6): Primary visualization library for creating interactive charts
- HTML/CSS: Frontend structure and styling
- JavaScript: Data processing and interaction handling

## How to Run
### Using Visual Studio Code Live Server
- Clone or download this repository
- Open the project folder in Visual Studio Code
- Install the "Live Server" extension if you haven't already
- Right-click on index.html and select "Open with Live Server"
- The dashboard will open in your default web browser

## Project Structure

```
Code/
├── d3.v6.min.js       # D3.js library
├── Datasets/          # CSV and GeoJSON data files
│   ├── split_part_1.csv
│   ├── split_part_2.csv
│   ├── split_part_3.csv
│   ├── split_part_4.csv
│   └── world.geojson  # World map data
├── Pictures/          # Images used in the visualizations
├── q1.html            # Speed vs. Age Analysis
├── q2.html            # Performance Analysis Map
└── q3.html            # Finishers Over Time
index.html             # Main dashboard
README.md
```

## Visualizations
1. Speed vs. Age Analysis
Explores the relationship between runner age and average speed, with interactive filters to compare male and female performance. Features animated transitions and tooltips for detailed information.

2. Performance Map
Interactive choropleth world map showing ultramarathon performance by country with filters for different distance ranges. Includes supplementary pie charts for demographic breakdowns.

3. Finishers Over Time
Line charts tracking the number of finishers over years across different distance categories with interactive toggles between male and female participants. Includes age distribution analysis via a dynamic donut chart.

## Demo Video
A video demonstration of the project can be found at: https://www.youtube.com/watch?v=QrH_sIewXjI

## Hosted Site
A hosted site is available on: https://dv-project-2.vercel.app/index.html

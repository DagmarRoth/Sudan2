# Mapping Six Months of Internal Displacement in Sudan

### An interactive visualization of conflict-driven movement across Sudan (2024–2025)

This project transforms raw conflict and displacement data into an interactive map that illustrates how violence has reshaped population movements across Sudan. By merging geolocated conflict events with displacement indicators, the visualization highlights both the scale and timing of internal displacement over a six-month window.

---

## Project Overview

The goal of this project was to:

- Build an interactive Folium map accessible through a web browser  
- Show where and when displacement occurred using heatmaps, markers, and time layers  
- Make complex conflict data understandable for a general audience  
- Present a standalone, publication-ready HTML map hosted on GitHub Pages  

The result is a data-driven visualization suitable for journalistic or research use.

---

## Data Sources and Collection

### Primary Sources
- **ACLED – Armed Conflict Location & Event Data Project**  
  https://acleddata.com  
  Provides geolocated conflict events, actors, and timelines.

- **IOM Displacement Tracking Matrix (DTM)**  
  https://dtm.iom.int  
  Provides displacement figures and humanitarian movement data.

==
### Data Preparation Process

1. Downloaded raw CSV data on conflict and displacement  
2. Cleaned geographic fields and removed missing coordinates  
3. Standardized timestamps and converted numeric displacement fields  
4. Filtered the dataset to the relevant six-month period  
5. Built cumulative and time-based heatmaps in Folium  
6. Exported the final visualization as `index.html` for GitHub Pages  

---

## Skills and Approaches Developed

This project involved several new technical and analytical steps:

### Mapping and Visualization
- Constructing interactive geospatial maps with Folium  
- Layering heatmaps, time-enabled visualizations, and custom markers  
- Using HTML popups to present structured information  

### Data Wrangling
- Cleaning and normalizing event-level conflict data in Pandas  
- Merging displacement datasets with conflict timelines  
- Preparing geospatial data for web-based mapping  

### Web Deployment
- Configuring a GitHub Pages site for a standalone HTML map  
- Troubleshooting build failures and repository structure  
- Managing files and metadata required for proper deployment  

### Story-Driven Analysis
- Designing the project to support journalistic storytelling  
- Integrating narrative text with interactive visual components  

---

## Future Improvements

There were several features planned but not yet implemented due to time constraints:

- A more advanced time slider showing month-by-month displacement  
- Filter controls for event type, actor, or region  
- Additional contextual tooltips for key cities and conflict zones  
- A more polished landing page layout on GitHub Pages  






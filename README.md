# Sudan

Mapping Six Months of ID Through Conflict in Sudan

This project visualizes six months of internal displacement (ID) across Sudan as conflict intensified throughout 2024–2025. The goal was to turn raw, event-level conflict data into a clear, interactive map that helps readers understand how violence has reshaped mobility, safety, and humanitarian needs across the country. The project aims to give viewers both a geographical and temporal sense of how the crisis has unfolded.

Data Sources & Collection Process

This map is based on publicly available conflict-event and displacement-indicator data pulled from:

ACLED – Armed Conflict Location & Event Data Project
https://acleddata.com

Used for geolocated violence/event data, actor information, and timestamps.

IOM Displacement Tracking Matrix (DTM)
https://dtm.iom.int

Used for internal displacement figures and movement patterns.

Additional background sources such as UN OCHA situation reports and humanitarian briefings.

Data processing workflow:

Downloaded raw CSV event data and cleaned missing or malformed coordinate fields.

Converted displacement and conflict categories into numeric variables suitable for mapping.

Sorted events chronologically to create a six-month window.

Built a Folium map with cumulative heat layers and dynamic markers.

Exported the final interactive visualization into an index.html file for GitHub Pages.

New Skills, Tools & Approaches Used

This project pushed me into several new technical areas:

Interactive mapping with Folium
Learned how to build choropleths, tile layers, cluster maps, and cumulative heatmaps, and export them cleanly into HTML.

Data cleaning & transformation with Pandas
Dealt with missing values, type conversions, sorting events by month, and merging DTM & ACLED indicators.

Debugging GitHub Pages deployments
Learned how .gitattributes, .nojekyll, and repository structure affect hosting interactive maps.

Embedding narrative text into HTML maps
Experimented with ways to integrate explanatory paragraphs below a full-screen visualization.

Overall, the project improved both my data-wrangling fluency and my ability to publish interactive journalism-style graphics on the web.

What I Wanted To Do But Ran Out of Time

There were several features and enhancements I attempted or planned, but wasn’t able to complete:

Animated timeline slider
I wanted the map to show how displacement changed month-to-month, using a dynamic time-slider layer, but implementing Folium’s TimestampedGeoJson requires more restructuring of the dataset.

Add filters for conflict actors or event types
Ideally, users could toggle RSF vs SAF events or filter by severity.

Hoverable tooltips with narrative context
I experimented with integrating short text blurbs for key cities (El Fasher, Nyala, Wad Madani), but didn’t fully resolve styling conflicts.

Better front-end design
With more time, I would refine the map’s surrounding layout so the explanatory text flows more like a news article.

These are all achievable next steps as my technical skills grow.

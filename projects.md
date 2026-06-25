---
title: Maps
nav_order: 3
---

# Maps

Here are my best maps that I have created using ArcGIS:

1.
These maps document a site suitability analysis designed to identify the optimal location for a new healthy food store within Philadelphia. The spatial narrative centers on locating candidate areas within Philadelphia Empowerment Zones that are highly accessible by public transit stations, while strictly avoiding established farmers markets and healthy corner stores. To execute this analysis, 2,000-foot proximity buffers were generated around transit resources, and 1,200-foot buffers were built around existing food venues. These data layers were then processed using Union and Intersect tools to map out inclusive criteria, followed by an Erase operation to remove the restricted buffer zones. Finally, a multipart-to-singlepart tool was applied to split the shapes, allowing for an area geometry calculation to identify individual candidate sites. This workflow successfully isolates the best development opportunities, leading to a specific land recommendation measuring roughly 9.5 million square feet.
<img width="100%" height="auto" alt="Layout" src="https://github.com/user-attachments/assets/eaed1c55-0952-497a-b99a-8a79e7089a9d" />
<img width="100%" height="auto" alt="Layout2" src="https://github.com/user-attachments/assets/3527fbbe-cd4a-44a3-a9bf-83eebba95f70" />

2.
This map chronicles a foundational spatial analysis focused on identifying highly populated educational infrastructure connected to Philadelphia’s active transit network. The narrative highlights the intersection of student populations and bikeable infrastructure, specifically isolating large schools with student enrollments exceeding 1,200 individuals that sit within a strict 0.1-mile proximity of the city's bike corridors. To pull this off, the workflow utilizes pure selection-based operations rather than generating new vector shapes. An initial Select By Attributes query was applied to the Philadelphia schools dataset to isolate the high-enrollment campuses. From there, a Select By Location spatial query was executed to find which of those large schools intersected the 0.1-mile spatial threshold of the bike network layer. A final location selection was leveraged against the neighborhood boundaries to identify the 8 distinct community zones containing these connected hubs. This query successfully flags 9 critical student centers to help plan infrastructure investments.
<img width="100%" height="auto" alt="Layout1" src="https://github.com/user-attachments/assets/24f0b840-a061-4a67-b3e9-131f23951350" />

3.
These maps break down the 2010 U.S. Census data to show where Hispanic populations live across the country. The core theme highlights how mapping raw numbers versus percentages tells completely different stories. For example, a state like New York has a massive total number of Hispanic residents, but because its overall population is so large, it actually ranks much lower on a percentage map.To show this contrast, the project skips geometric geoprocessing and focuses entirely on advanced symbology techniques. First, a Dot Density map was built to display absolute totals, with each individual dot anchoring a threshold of 5,000 residents. Alongside it, a Graduated Colors choropleth map was calculated using a normalized ratio to sort states into five distinct percentage brackets. The final step involved custom layout edits to clean up the legend, stripping away messy decimal points so the intervals are simple and easy to read.
<img width="100%" height="auto" alt="Layout" src="https://github.com/user-attachments/assets/022e618a-9481-4bad-b041-2dbab1bd3a8d" />
<img width="100%" height="auto" alt="Layout1" src="https://github.com/user-attachments/assets/85c0f742-ec41-40c7-90f9-826c9cf4d575" />


# K-Means-Implementation
# Classification on Urban spatial order data

Based on the research paper ['Urban spatial order:street network orientation, configuration, and entropy'](https://appliednetsci.springeropen.com/articles/10.1007/s41109-019-0189-1) published by Geoff Boeing

## 1. Introduction

The paper "Urban Spatial Order: Street Network Orientation, Configuration, and Entropy" by Geoff Boeing examines street network patterns across 100 global cities. It utilizes OpenStreetMap data and OSMnx software to analyze street orientations and configurations. The study focuses on the entropy of street bearings and other metrics like average street segment length, circuity, node degree, and proportions of intersections and dead-ends. It also introduces a new measure, orientation-order, to quantify a city's grid-like structure. Statistical relationships between street orientation-order and other spatial order indicators are explored, revealing distinctive patterns in different regions, particularly between U.S./Canadian and other cities. The research provides insights into urban design and planning, highlighting the complexity and patterns of urban transportation systems worldwide.


By using the parameters explored in this paper, we aim to cluster the cities in this project. Apart from the indicators mentioned in this paper, we also introduce other features that might play a role in the development of the city, like city age, population, GDP per capita. The analysis on these indicators will direct us towards the crucial features that are to be looked into when it comes to planning and development of such cities in the future. The data for these features are collected from publically available sources.

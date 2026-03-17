# Public Transportion Accessiblity in Seattle

GEOG 458 Group 18

## AI Disclosure 
AI was used to help with certain code clarity within INDEX and ABOUT Page. 

## Project URL

- Project Github: https://github.com/milaboj/publicTransitDashboard/tree/main
- Dashboard: https://milaboj.github.io/publicTransitDashboard/index.html

## Team Members

- Naod Alemu: nalemu13@uw.edu
- Daniel Villasenor: dvilla4@uw.edu
- Mila Bojanic: milabo@uw.edu
- Billy Le: billyle@uw.edu

## Project Description
This project is an interactive web-based dashboard designed to explore public transit accessiblity across the greater Seattle area. 
Using spatial data and mapping tools, the dashboard allows users to analyze transit stops, light rail connectivity, 
and accessbility features that impact mobility. 

The goal of this project is to higlight how accessible public transit is for different users. 
In particular, general riders, cyclists, people with disabilities, policymakers, and everyday people 
who want a better understanding how transportation infastructure shapes everyday movement in Seattle. 

## Screenshots

The following screenshots show the current dashboard that is included in this repository. 

insert screenshots here

## Project Goal
The Seattle Public Transit Accessibility Dashboard explores how accessible public transportation is across Seattle neighborhoods. 
Using datasets from Seattle City GIS and King County Metro, the dashboard visualizes bus stops and light rail stations to help users understand how close different communities are to reliable transit. 
Interactive layers, buffer zones, and charts allow users to explore walkable access to transit and compare accessibility between areas. 
Our goal is to highlight patterns of transit connectivity and encourage conversations about mobility, equity, and urban planning.

## Main Features

- Interactive map of Seattle transit infrastucture
- Toggleable layers: Transit Routes, Neighborhoods, Light Rail Stops, Walking Distance (in miles)
- Accessiblity scoring system for each stop (0-4 scale)

## About: Accessiblity Scoring System 
Each transit stop is assigned a score from 0 to 4 based on the availability of key accessibility features:

0 = No accessibility features available

1 = Limited accessibility (few features available)

2 = Moderate accessibility (some features available)

3 = Good accessibility (most features available)

4 = Highly accessible (all key features present)

## Data Sources:

- King County Bus Network:

1. https://gis-kingcounty.opendata.arcgis.com/datasets/4af32639372044f0b3256c8d0e0f40a7_0/explore 
2. https://gis-kingcounty.opendata.arcgis.com/datasets/ec3ec9492c0846e8a5e93d056a8cdc4f/explore?location=47.665832%2C-122.307712%2C15
3. https://data-seattlecitygis.opendata.arcgis.com/datasets/159745030bdc4276b0e9f1b20b23b46b_0/explore?location=47.619346%2C-122.326310%2C11

- Neighborhoods:

1. https://data-seattlecitygis.opendata.arcgis.com/datasets/b4a142f592e94d39a3bf787f3c112c1d_0/explore?location=47.614610%2C-122.336918%2C11

- Light Rail Stops and Info:

1. https://data-seattlecitygis.opendata.arcgis.com/datasets/light-rail-stations-1/about

## Applied Libraries and Web Services

- **GitHub** and **GitHub Pages** for code hosting and project publishing.
- **MapLibre GL JS** for interactive web mapping.
- **Turf.js** for spatial analysis such as point-in-polygon tests, area calculation, and bounding boxes.

## Acknowledgement

- GEOG 458 course materials and inspiration from LAB 6 DASHBOARD mapping workflow was used to further help with the visualization of this project.
- King County Metro, King COunty GIS Opendata was used for the transit and neighborhood datasets. 




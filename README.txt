Hiking in Australia

An interactive data visualisation exploring hiking participation across Australia and walking opportunities within New South Wales.

Created for FIT3179 Data Visualisation 2, Monash University — Semester 2, 2026.

Live Visualisation

View the visualisation:
https://kohjialer.github.io/walking-australia-dv2/

About

The visualisation tells a story about hiking from four perspectives:

Hiking participation in Australia
How popular Bush walking is, who participates and how participation changed from 2024 to 2025.

Where hiking is most popular
How participation rates and estimated participant numbers differ across Australian states and territories.

Where people can hike in New South Wales
The geographic distribution, classes and lengths of formal walking-track infrastructure.

Hiking in the context of New South Wales national parks
Historical park visitation and reported walking duration.

Terminology: The Australian Sports Commission's AusPlay dataset reports hiking under the activity category “Bush walking”. The source terminology is retained where relevant in the visualisation.

Visualisations

The webpage contains 11 Vega-Lite visualisations, including:

ranked bar chart

dumbbell chart

slope chart

choropleth map

proportional-symbol map

point-distribution map

box plot

dot plot

horizontal bar chart

heatmap

waffle chart

Three different map idioms are used to represent participation rates, participant numbers and the distribution of walking-track infrastructure.

Data Sources

Australian Sports Commission — AusPlay

Used for Charts 01–05.

https://www.ausport.gov.au/clearinghouse/research/ausplay/results/data-tables

NSW Spatial Services — Asset Infrastructure: Track Section

Used for Charts 06–09.

https://www.data.nsw.gov.au/data/dataset/asset-infrastructure-track-section8bfcf

NSW National Parks and Wildlife Service — Parks Visitation Survey FY24–25

Used for Charts 10–11.

https://www.environment.nsw.gov.au/topics/parks-reserves-and-protected-areas/park-management/npws-park-management/park-visitor-survey

Technology

HTML

CSS

JavaScript

Vega

Vega-Lite

Vega-Embed

Repository Structure

.
├── index.html
├── data/
│   ├── maps/
│   └── ...
├── js/
│   └── specs/
│       ├── chart1_activity_ranking.json
│       ├── chart2_dumbbell.json
│       └── ...
├── README.md
└── ...

Author

Koh Jia Ler
FIT3179 Data Visualisation 2
Monash University
October 2026
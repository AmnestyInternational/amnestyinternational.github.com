---
layout: post
title: Amnesty International Digital at Random Hacks of Kindness Ottawa
---

Wherein we start building VISOR, a protest-data tool

-----

## Project VISOR at RHOK Ottawa Spring 2014

VISOR is a data platform for collecting, measuring, and distributing information from protest-type events. VISOR was born at Random Hacks of Kindness Ottawa 2014.

### The Need

Increased visibility of protest style events. Shortening information delays between events on the ground and analysis.

### Uses
- Tracking events in real time
- Documenting tear gas use
- Documenting kettling and mass arrests

### Data sources
- Twitter
- Instagram
- Firechat
- Anything with geotaging (Flickr, Weibo, SMS, wearable devices?)

### Data quality needs
- Correlating people based on their followers and followers relationship, creating social graph.
- Filtering data by geographic proximity
- Representing aggregated data
- Robust solution which can resist attack (Google docs + [tabletop.js](https://github.com/jsoma/tabletop) + [flatware](https://github.com/jsoma/flatware), github, etc.)
- Output in easily-digestable format, like JSON

### Possible end-uses 
- Easy and clean data feeds (JSON!) for data journalists and human rights monitors
- Simple charts, graphs and maps made with googledocs and [sheetsee.js](https://jlord.github.io/sheetsee.js/) 
- Complex charts, graphs and maps made with [mapbox](https://www.mapbox.com/) or [D3.js](http://d3js.org/) or [leaflet.js](http://leafletjs.com/)
- Data-analysis, with [R](http://www.r-project.org/) or similar
- Web applications for protest watchers
- Mobile apps for protesters

<iframe src="//slides.com/jacksoncouse/rhok14intro/embed" width="576" height="420" scrolling="no" frameborder="0" webkitallowfullscreen mozallowfullscreen allowfullscreen></iframe>
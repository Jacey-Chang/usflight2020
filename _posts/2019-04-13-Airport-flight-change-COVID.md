---
title: "Airport flight change during COVID"
date: 2019-04-13
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "Embedding interactive charts on static pages using Jekyll."
altair-loader:
  altair-chart-1: "charts/measlesAltair.json"
hv-loader:
  hv-chart-1: ["charts/airport_change.html", "700"] # second argument is the height
  hv-chart-2: ["charts/airport_percent_change.html", "700"]
toc: true
toc_sticky: true
---

## Altair Example

Below is a chart of the incidence of measles since 1928 for the 50 US states.

<div id="altair-chart-1"></div>

This was produced using Altair and embedded in this static web page. Note that you can also display Python code on this page:


### Quantity Change
<div id="hv-chart-1"></div>

### Percent Change
<div id="hv-chart-2"></div>
## Notes




**Important: When embedding charts, you will likely need to adjust the width/height of the charts before embedding them in the page so they fit nicely when embedded.**

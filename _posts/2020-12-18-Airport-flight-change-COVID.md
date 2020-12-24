---
title: "Airport flight change during COVID"
date: 2020-12-18
published: true
tags: [flights,covid]
excerpt: "flight change by airport"

hv-loader:
  hv-chart-1: ["charts/airport_change.html", "500"] # second argument is the height
  hv-chart-2: ["charts/airport_percent_change.html", "500"]
  hv-chart-3: ["charts/percent_change_quant.html", "330"]
  hv-chart-4: ["charts/airport_covid.html", "500"]
toc: true
toc_sticky: true
---

The flight decline in April and May was sharp, but the flight quantity was slowly going up in the following months.

Use mouse wheel to zoom in and out.

### Quantity Change
<div id="hv-chart-1"></div>

### Percent Change
<div id="hv-chart-3"></div>
<div id="hv-chart-2"></div>
### Is flight change related with COVID cases?
<div id="hv-chart-4"></div>
Based on the COVID cases by week in counties where the airports located, there doesn't seem to be a clear relationship between COVID cases and flight change.

Flight quantity and change are more closely related with airport features.

Graphics are made with Python hvplot package.

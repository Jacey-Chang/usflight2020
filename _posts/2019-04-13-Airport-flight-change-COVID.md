---
title: "Airport flight change during COVID"
date: 2019-04-13
published: true
tags: [dataviz, altair, hvplot, holoviews]
excerpt: "flight change by airport"

hv-loader:
  hv-chart-1: ["charts/airport_change.html", "500"] # second argument is the height
  hv-chart-2: ["charts/airport_percent_change.html", "500"]
  hv-chart-3: ["charts/percent_change_quant.html", "500"]
  hv-chart-4: ["charts/airport_covid.html", "500"]
toc: true
toc_sticky: true
---

The flight decline in April and May was sharp, but the flight quantity was slowly going up in the following months.

Graphics are made with Python hvplot package.

### Quantity Change
<div id="hv-chart-1"></div>

### Percent Change
<div id="hv-chart-2"></div>

<div id="hv-chart-3"></div>

### Is flight change related with COVID cases?
Below is the COVID cases by week in counties where the airports located.

As shown in the figures, there doesn't seem to be a clear relationship between COVID cases and flight change.
<div id="hv-chart-4"></div>

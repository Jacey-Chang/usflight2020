---
title: "Are passengers filling the seats?"
date: 2020-12-20
published: true
tags: [flights, covid]
excerpt: "load factor (passengers/seats) of routes"
folium-loader:
  2020load: ["charts/all20_may.html", "500"]
  2019load: ["charts/all19_may.html", "500"]

hv-loader:
  hv-quantile: ["charts/load_factor_quant.html", "330"]
toc: true
toc_sticky: true
---


Load factor is the total passenger number divided by total seats of each route.

You can see that although the flight routes are similar, the load factor for 2020 is much lower than 2019.

This indicates that there might be a waste of aviation resources.

<div id="hv-quantile"></div>


Click the **">"** on the top left and then the **funnel icon** to change the filter condition.

You can
- **specify the origin or destination airports**
- **change selected month(s)** (default month is May)

Click the third button on the top right to see legend.

### 2020 monthly load factor

(default month: May)

<div id="2020load"></div>

### 2019 monthly load factor

(default month: May)

<div id="2019load"></div>

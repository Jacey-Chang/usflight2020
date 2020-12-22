---
title: "Interactive weekly flights by airline"
date: 2019-04-13
published: true
tags: [dataviz, folium]
excerpt: "Embedding interactive Folium charts on static pages using Jekyll."
folium-loader:
  2020byairline: ["charts/2020byairline.html", "500"] # second argument is the height
  2019byairline: ["charts/2019byairline.html", "500"] # second argument is the height
toc: true
toc_sticky: true
---


Graphics on this page is made with [KeplerGL](https://github.com/keplergl/kepler.gl)

You can click the ">" on the top left and then the funnel icon to change selected airlines and week.

The default airline selection is American Airlines(AA), Delta Airlines(DL), and United Airlines(UA).

The default week selection is week 10 (starting with the first Sunday of April)

### 2020 weekly flights by airline

<div id="2020byairline"></div>

### 2019 weekly flights by airline

<div id="2019byairline"></div>

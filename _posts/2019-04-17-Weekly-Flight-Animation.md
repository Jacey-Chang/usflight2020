---
title: "Weekly Flights in US, 2019 and 2020"
date: 2019-04-17
published: true
tags: [dataviz, flights, covid]
excerpt: "Animation of weekly US domestic flights from February to September in 2019 and 2020"
toc: true
toc_sticky: true
read_time: false
---

Animation of weekly US domestic flights from February to September in 2019 and 2020.

You can see that although COVID impacts heavily on the aviation industry, US airports are still closely connected.

The linear interpolation colormap gives more accurate demonstration of the quantity change of flights, and log interpolation colormap shows the routes more clearly. The graphics are made with Python datashader package

### Linear Colormap

![linear_colomap]({{ site.url }}{{ site.baseurl }}/assets/images/20192020_linear_v.gif)

### Log Colormap

![log_colomap]({{ site.url }}{{ site.baseurl }}/assets/images/20192020_log_v.gif)

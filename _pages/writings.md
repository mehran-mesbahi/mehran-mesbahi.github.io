---
layout: page
permalink: /writings/
title: writings
description: publications by categories in reversed chronological order (still in the works ... one year at a time!)
years: [2024, 2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004, 2003, 2002, 2001, 2000, 1999, 1998, 1997, 1996, 1995]
nav: true
---
<div class="publications">
{%- for y in page.years %}
  <!-- <h2 class="year">{{y}}</h2> -->
  <h2 class="year"><span style="color: orange;"> {{y}}</span></h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

---
layout: default
title: GIS with Python
has_children: True
nav_order: 1
---

# Geocoding and Web Mapping
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>

# Learning Objectives:

* Gain Familiarity with Geocoding
* Make a Simple Web-Map 
* Earn Extra Credit!

# Geocoding

The process of attributing coordinates (Latitude/Longitude) to descriptive locations (Street Address).  We can use a variety of web based services (google maps, ESRI, mapbox, open street map, etc.) to perform geocoding.  We're using Mapbox today because it strikes a good balance between accessibility and accuracy.  

## Google Maps
{: .no_toc }

Arguably the best geocoding service, but it costs money :/ [5.00 USD per 1000 request](https://developers.google.com/maps/documentation/geocoding/overview).

## ArcGIS World Geocoder
{: .no_toc }

You can geocode in ArcGIS Pro.  You can find a simple tutorial [here](https://pro.arcgis.com/en/pro-app/latest/help/data/geocoding/tutorial-geocode-a-table-of-addresses.htm) and more information [here](https://pro.arcgis.com/en/pro-app/latest/help/data/geocoding/convert-a-table-to-locations-on-the-map.htm) if you need to geocode for your final proejct.  Feel free to give it a shot on your own time if you want.  The reason I am **not** fond of using ArcGIS Pro to geocode: ESRI geocoding services uses a [credit](https://www.esri.com/en-us/arcgis/products/credits/overview?rsource=%2Fsoftware%2Farcgis%2Farcgisonline%2Fcredits) based system for geocoding because it is a "premium" service.  As a student, you get something like 1,000 credits, which is easy to go through quickly.  You can get more if you request them from Jose, but its inconvenient, and Jose only has a limited number to give out.  It makes learning/troubleshooting difficult.

## Mapbox
{: .no_toc }

A "freemium" service up to [100,000 requests per month](https://www.mapbox.com/pricing/#geocode) and gives fairly reliable results.  This is what we will be using.  It requires you to create a free [Mapbox](https://mapbox.com) account.  Once you have an account, you will be given an [access token](https://account.mapbox.com/access-tokens/).  Which lets you use the Mapbox's services.  We are going to be using Mapbox's Application Programming Interface([API](https://docs.mapbox.com/api/overview/)) which lets us programmatically access Mapbox tools and services. You can use these APIs to retrieve information about your account, upload and change resources, use core Mapbox tools, and etc.

# Web Mapping

Web mapping takes cartography beyond static maps.  It allows us to create dynamic, interactive web maps that can be embedded in webpages!

## ArcGIS Online
{: .no_toc }

ESRI has a platform called [ArcGIS Online](https://www.arcgis.com/index.html).  If you're interested in learning about it, my colleague Maya at the UBC Library Research Commons has created this [workshop](https://ubc-library-rc.github.io/intro-AGOL/).  You can look through this page if you're interested in learning how to use it.

## Leaflet
{: .no_toc }

[Leaflet](https://leafletjs.com/) is an open-source (free) JavaScript library for mobile-friendly interactive maps. It works efficiently across all major desktop and mobile platforms and has a well-documented [API](https://leafletjs.com/reference.html).  We are going to use a Python package called [follium](http://python-visualization.github.io/folium/) to "communicate" with Leaflet and make some simple web maps like this.

<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="Python_Notebooks\MtPleasant_Trees.html" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="Python_Notebooks/MtPleasant_Trees.html" target="_blank">View Map in New Tab</a>

# Using Python for GIS

Its a great programming language, and consistently ranks among the most poplar in the world! But it is not the only language. Just as English, Cantonese, or Punjabi can all be used to write a paper; Python, Javascirpt, or R can all be used to make a map.  I like python because its very flexible, fairly easy to read / write, well suited for data analysis, has lots of packages for GIS, and it's completely free!  You will not be expected to know any code or learn how to code. I just want to introduce you all to some the possibilities.




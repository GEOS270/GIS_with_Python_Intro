---
layout: default
title: Getting Started
parent: GIS with Python
nav_order: 1
---

# Geocoding and Web Mapping Walk Through

I'm going to give you a quick walk through of the geocoding notebook.  Your "Lab" for this week is just to follow along through this tutorial and answer the respective questions.

## Getting Setup: Download the Code and Data

**1**{: .label .label-red } **Start a Jupyter Lab**

UBC provides server space where you can run Python using [Jupyter Lab](https://ubc.syzygy.ca/jupyter).  Login with your CWL.  You'll then be taken to a blank jupyter lab.

* This is good option for getting your bearings because nearly everything is already set up. You don't have to worry about installing anything on your own system.
* This may sound intimidating/confusing.  But don't worry, its easy.  You don't need to know command line to do this.  I'll walk you through step by step.  You can also refer to the video below for help


**2**{: .label .label-red } **Open a terminal**

We're going to open a command terminal and use command line clone the Github workshop's repository.

* In they Jupyter window, click File>"New" in the top right and select "Terminal" from the drop-down menu.

**3**{: .label .label-red } **Clone the Repository**

Cloning tells Git (a file tracking software) to download a repository (collection of code, data, etc.) for this workshop.
In the new terminal window that opens, paste this command and hit enter:

    git clone https://github.com/GEOS270/GIS_with_Python_Intro

A folder called Geocoding-Web-Mapping-with-Python should now be visible.  You can explore it using file viewer on the left, or you can use the command line (see video).

**4**{: .label .label-red } **Installing a Package**

In the terminal window type the command below and hit enter to install the geopy package

    pip install geopy

**5**{: .label .label-red }  **Opening a Jupyter Notebook**

In the file viewer You will notice a folder with the same name as the repository you just cloned, double clicking the folder will open it.  You'll see a folders and a collection of files.  The one we'll be working in is called "Python_Notebooks".  Double click to enter.

* The .ipynb tag on the end denotes a Jupyter "Notebook"
  * A Notebook is a collection of Python code and annotations that can be run interactively.
  * Double click on "Geocoding and Webmapping.ipynb" to open it.

## Video Reference

This video covers the above steps.  **Note** the video is for a workshop I run.  In step 3, the URL and file names are different.  Everything else is the same.

<iframe width="560" height="315" src="https://www.youtube.com/embed/_lqzOLeSlo0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


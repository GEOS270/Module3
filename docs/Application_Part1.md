---
layout: default
title: Data Download and Setup 
parent: Lab Assignment
nav_order: 1
---

# Data Download and Setup
{: .no_toc }

1. TOC
{:toc}

---

# Create a New Project

Open up AcrGIS Pro and create a new project.  You can reference the same steps outlined in [Module 1](https://geos270.github.io/Module1/docs/Application_Part3_0.html) for help creating a project.


**1**{: .label .label-yellow } Name the project **BC_Food_Cost**

**2**{: .label .label-yellow } Create a new "Feature Dataset" called **BC_Census_Data**
* Make sure the feature dataset is in the "NAD 1983 BC Environment Albers" projection
* See the video below for guidance


<div style="overflow: hidden;
  padding-top: 56.25%;
  position: relative">
  <iframe src="content/videos/Setup.mp4" title="Processes" scrolling="no" frameborder="0"
    style="border: 0;
   height: 100%;
   left: 0;
   position: absolute;
   top: 0;
   width: 100%;">
   <p>Your browser does not support iframes.</p>
 </iframe>
</div>
<a href="content/videos/Setup.mp4" target="_blank">View Image in New Tab</a>

# Download the BC Boundary File

# Download the Census Data

We are gong to download population estimates for 2021 using [Simply Analytics](https://resources.library.ubc.ca/page.php?id=1044).  You can also find it by Googling "Simply Analytics UBC Library".  One of the first results will be the Library Indexes & Databases page.

**1**{: .label .label-red } On the library page, click "Connect to the Resource".  This will redirect you to the simply analytics logon page.  

**2**{: .label .label-red } Click the link to create a new account.  **Note** you have to connect via the library, otherwise you will be need to login via the UBC VPN first.

<img src="content/images/connect.png">


Once you're setup, you can download the data.  The video below walks you through using the simply analytics interface.  We are going to download the following data: 

* **Total Population (2021)**
* **Median Household Income (2021)**
* **Average Total Expenditures on Food (2021)**.  

The steps outlined in the video are:

**1**{: .label .label-blue } Create your project to query data.

* Select study area and inspect default variables.
* Explore the interface.
* Watch intro video on Simply Analytics.

**2**{: .label .label-blue } Query additional variables.

* Search for food cost.
* Make sure to select the correct variable.

**3**{: .label .label-blue } Export the data.

* Save the project so its easy to come back if needed.
* Export the shapefile.
	* Make sure all variables are checked.
	* Make sure to export **Census Subdivisions**.


**4**{: .label .label-blue } Import the Data.

* Check your email for the download link.  Extract the Simply Analytics shapefile to the **BC_Food_Cost** project folder.


<iframe width="560" height="315" src="https://www.youtube.com/embed/eEtLTafGxbM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

# Pre-Processing

We have to do a few things to the data to make sure everything setup and ready so we can conduct our analysis.

The steps outlined in the video are:

**1**{: .label .label-green } Make sure the data is in the proper projection!

* Import the census data into the project feature dataset.
	* Think about what projection we're using and **why**.
* Rename the variables.
	* Data from simply analytics comes with generic column headers that can be confusing.
	* The simply analytics data comes with a text file containing header names you can reference to give them more helpful names.


**3**{: .label .label-green } Clip the census subdivisions by the BC boundary file.

* The census subdivision from Simply Analytics look pretty funky along the coast.
	* We can use the **Clip** tool to cut the layer down to size.
	* Think about what projection we're using and **why**
* Rename the variables
	* Data from simply analytics comes with generic column headers that can be confusing
	* The simply analytics data comes with a text file containing header names you can reference to give them more helpful names

<iframe width="560" height="315" src="https://www.youtube.com/embed/YRm8Bv958gw" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


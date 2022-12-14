---
layout: default
title: Data Classification
parent: Lab Assignment
nav_order: 2
---

# Data Classification
{: .no_toc }


1. TOC
{:toc}

# Defining Rural & Urban Areas

Until 2010, Statistics Canada used a Rural/Urban classification scheme to describe Census unit smaller than a Province/Territory:

**Rural**: a population density less than 400 people per square kilometer **or** a total population of less than 1,000 people.

**Urban**: a unit with a population density at least 400 people per square kilometer **and** a total population of at least 1,000 people.

## A Revised Classification

Statistics Canada Now uses the **Population Center and Rural Area Classification**.  You can skim the [Documentation](https://www.statcan.gc.ca/eng/subjects/standard/pcrac/2016/introduction) explaining the classification scheme to get a feel for the reasoning behind updating from the old Rural/Urban method?  The new classification scheme was updated to split the old **Urban** class into three different kinds of **Population Centers**:

|**Rural**         |**Small Population Centers**            |**Medium Population Center**                                            |**Large Urban Population Center**        |
|------------------|----------------------------------------|-------------------------------------------------------------------------|------------------------------------------|
|Same as old method|Not Rural **and**<br>Population < 30,000|Not Rural **and**<br>Population >= 30,000 **and**<br>Population < 100,000|Not Rural **and**<br>Population >= 100,000|


---

# Applying the Classification

Your task is to apply the **Population Center and Rural Area Classification** scheme (see table above).  You can watch the video below for reference, which shows you how to apply the old **Urban/Rural** scheme. 

* You are going to use the **Select by Attribute** function to help apply the classificiation.
	* Select by Attribute allows us to select rows/objects with a certain attribute.
	* It relies on something called a Structured Query Language (SQL).
* We are selecting all rows "Where" our conditions are met.
	* You can use the **And**/**Or** commands to combine querries.
	* **And**: Selects whre **All** statements are true
	* **Or**: Selects whre **Any** statements are true

## **Note**
{: .no_toc }

* The video is from a slightly dated version of the lab, the steps are the same but some of the file names may look a bit different, and it was recorded using an older version of ArcGIS Pro.

* You do not need to apply the old classification scheme, I use this example as a reference.  All your answers and uploads for the lab should be drawn from the **New** classification scheme.  The general steps for classifying the data are:


**1**{: .label .label-red } Calculate population density.

* You can refer to the exercise we did as part of [Module 2](https://ubc-library-rc.github.io/map-projections/content/exercise4-pop-density.html) for help.


**2**{: .label .label-red } Create a field and populate it using select by attribute, following the **Population Center and Rural Area Classification** scheme.

* You can reference the table above for pointers on how to formulate your SQL statements.


<iframe width="560" height="315" src="https://www.youtube.com/embed/uMLtpB6Xjqc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

<!-- ### QA3

The Select by Attribute tool lets us use SQL (Structured Query Language) to define expressions for querying vector data. [T/F] -->


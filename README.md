# Hackathon 4.25.2020 Education Track

> Author: Alex Lau

## Table of Contents
- [Problem Statement](#Problem-Statement)
- [Executive Summary](#Executive-Summary)
- [Conclusion](#Conclusion)
- [Data Dictionary](#Data-Dictionary)

## Problem Statement
The current COVID-19 pandemic has caused huge disruption to health and economies around the world. Our federal and many of our local governments have mandated quanrantine rules. Many people have lost their jobs, most likely their sole source of income. As many of us are staying home and praticing social distancing, this has also become an opportunity to take advantage of learning new skills whether it be for self improvement, or to become competitive in an increasingly digital world. We will attempt to pull data from 3 online course platforms (Coursera, Udemy, EdX) and consolidate to a single data frame to provide a convenient connected platform. Paid courses from these platforms are wonderful, with some sharable certificates, or even complete degrees, however, in the wake of massive unemployment, we will focus on the free ones in this project.

## Executive Summary



## Conclusion
We find 170 free courses online on the Coursera platform in a variety of subjects to explore. While we were not able to scrape the Udemy data, you can find a list of 706 results that Udemy is offering for free in this link: https://www.udemy.com/courses/free/. EdX also offers free courses for audit without a certificate through this link: https://www.edx.org/course/?type=verified. There are plenty of resources for online learning. 

## Data Dictionary
|Feature|Type|Description|
|---|---|---|
|**title**|*object*|Name of the course| 
|**online_course_organization**|*object*|Platform the data is web scraped from| 
|**free**|*object*|Value to indicate this course is free, paid courses are removed from our view|
|**author_organization**|*object*|The partner organization for the course, be it a university, company, organization|
|**course_type**|*object*|Online classes can result in degrees, certificates, specializations or regular courses|
|**level**|*object*|Levels are ordinal values ranging from beginner, mixed, intermediate, and advanced)|
|**ratings**|*float*|Average rating per course are between 0 for least favorable and 5 for most favorable|
|**reviews**|*integer*|Sum of the review count per course|
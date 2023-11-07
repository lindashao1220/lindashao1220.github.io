---
title: "Assignment 2 Working with a Corpus"
last_modified_at: 2023-11-07T16:20:02-05:00
categories:
  - Blog
tags:
  - Assignment
---

This assignment has four main elements: (1) identifying the spatial elements of The Brooklyn City and Business Directory (2) modeling a spatial dataset based on those elements, (3) enriching the spatial data with any other relevant metadata, (4) visualizing the data on a map, discussion and interpretion. So I will go through all of them in this blog post section by section.

Step 1: As for choice of source, the souecebook that I worked with is #1 The Brooklyn City and Business Directory 1879-80. This directory contains names of people, their professions and street addresses, and provides information about businesses, residents, and various establishments in Brooklyn, New York, for the year 1880. 

Such directories were commonplace during the 19th century, functioning as indispensable compasses for locating businesses, professionals, and residents within specific regions. They not only featured comprehensive business listings but also included essential information regarding government offices, schools, churches, and social organizations, along with the names and addresses of city residents. This invaluable resource provided me with key insights into the city's demographics and economic landscape during that specific period. Additionally, it serves as an source to get into a sense of the commercial and social situation of the era, while also preserving a historical record of Brooklyn's evolution and the individuals who were part of its vibrant community during that time.

Step 2: In the second phase of my work, I embarked on the data modeling process. Given the extensive volume of information within the book, I chose to focus on a specific subset of data, namely, the first three pages. These initial pages primarily featured individuals whose names began with the letter "A." My initial step involved employing Optical Character Recognition (OCR) to convert the text from the esteemed "Brooklyn City and Business Directory 1879-80" (#1 in my sources) into a machine-readable format. This transformed text was subsequently input into ChatGPT, where I get its assistance in extract the names of individuals, their respective jobs, and their specific locations. Once this extraction was successfully completed, I proceeded to organize the gathered data by populating an Excel spreadsheet for further analysis and utilization.

<img src="/assets/images/11.png" style="zoom:80%"/>

The process of collecting data is very interesting. I was amazed by how ChatGPT can classify things into different categories so quickly and efficiently. However, I have found there are some little glitches with the extracted texts sometimes. It sometimes cannot get it right in order, or miss some of the details when extracting the data, especially when feeds it like 60is lines of combined information.

The data collection process was truly fascinating to me. I was particularly impressed by ChatGPT's ability to rapidly and accurately classify information into various categories, such as names, jobs, and their locations. However, I did encounter some minor glitches with the extracted text on occasion. It occasionally struggled with maintaining the correct order of information or missed certain details, particularly when dealing with longer lists of about 60 lines that contained combined information.


Step 3: I had compiled the information lists into the Excel spreadsheet, I delved into the process of geocoding to enhance the data extracted from the book. To accomplish this, I leveraged the geocoding feature provided by the Google extension. The results I obtained were truly remarkable, as they effortlessly populated the spreadsheet with comprehensive location details, including latitude and longitude. 

<img src="/assets/images/12.png" style="zoom:80%"/>

Also to import all the data in the Kepler, I have converted the excel format into the CVS format.

<img src="/assets/images/13.png" style="zoom:80%"/>

Step 4: The last step I did with the data is I put them in Kepler and visualise all of them. This is the final result that I get.

<img src="/assets/images/14.png" style="zoom:80%"/>

By hovering around the data point in the map, I have found that the directory like churches and religious organizations are everywhere, which can reveal the diversity of religious denominations present in Brooklyn. It can also show the distribution of churches across different neighborhoods. So probably people in that time are feeling affiliated with religion.

It's essential to recognize that directories of this nature might lack completeness, and not all residents would have necessarily been included. Various reasons could account for individuals not appearing in the directory. Furthermore, my analysis focused solely on individuals whose names commenced with the letter 'A,' which implies that the final assessment may be limited in its representation of the entire population.

There is also drawbacks of the charts, as the picture shown below, we can see the population is distributed around the US, but not limited in New York City. I think this is very suspicious, since the book is only about the Brooklyn population distribution. I think the problem is because the geocoding part get wrong 😭But yea, thankfully most of them get right.
<img src="/assets/images/15.png" style="zoom:80%"/>










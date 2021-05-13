---
layout: page
title:  "Canadian Migration"
subtitle: "Dataviz"
date:   2021-05-05 21:21:21 +0530
categories: data
---

I am a multi-time statistic of the Canadian inter-provincial migration. I’ve lived on the Pacific and the Atlantic coasts,
on the Upper and Lower Canada dividing line, and the country’s only true metropolis, Toronto. At all my stops,
I met and befriended many like myself: Canadians who’ve crossed provincial lines to pursue career opportunities not available at home.
Trying to understand the flows of domestic migration, I lookup up the data available from the Statistics Canada website. Judging from my own experience,
I had assumed that there would be a few provinces with net increases (Ontario, BC, and Alberta) with the rest bleeding citizens.
I compiled the data spanning 11 years — from the time I left NS in July 2007, to June 2018, the last data available on StatsCan.
I transformed the data to create a chord diagram showing the movements from province-to-province as well as diverging bar charts to show the total 
and the relative net changes for the period. I will post the R code on my GitHub page and update the code and numbers in 6 months time when we have estimates on the change during 
COVID. Judging by how ridiculous the local market is right now, I suspect we'll see more coming into the province.

<p align="center">
  <img align="center" src="https://jfm-data.github.io/imgages/Canada_migration.jpg">
</p> 

What was most surprising about the analysis is that it revealed Ontario being a net negative province. I assumed Toronto and Ottawa, large cities full of transplants, made Ontario the top draw for all Canadians. Secondly, I was shocked that the Atlantic provinces were not clustered at the bottom of the list. Newfoundland & Labrador and Nova Scotia were only slightly negative and higher on the list than the non-Alberta Prairie provinces and Quebec. I suspect this might be related to Ontario’s lower than expected relative numbers. Older people might be re-locating east for cheaper property values and slower pace of life. Lastly, seeing BC was near twice the relative increase than Alberta. It was conventional wisdom to think Alberta was number one in net inter-provincial migration given the opportunities created by oilsands development for both blue and white-collar workers. While BC is the most beautiful province (if you filter for the homelessness and drug addicts) there are no apparent growth industries in BC. Perhaps the natural beauty makes it difficult for people to leave.

<p align="center">
  <img align="center" src="https://jfm-data.github.io/images/pyramidplot_can.png">
</p> 

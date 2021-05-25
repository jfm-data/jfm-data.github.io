---
layout: page
title:  "Canadian Migration"
subtitle: "Dataviz"
date:   2021-05-05 21:21:21 +0530
categories: data
---

I am a multi-time statistic of the Canadian inter-provincial migration. I’ve lived on the Pacific and the Atlantic coasts,
on the Upper and Lower Canada dividing line, and the country’s only true metropolis. At all my stops,
I met and befriended many like myself: Canadians who’ve crossed provincial lines to pursue interesting career opportunities not available at home.
Trying to understand the flows of domestic migration, I looked up up the data available from the Statistics Canada website. Judging from my own experience,
I had assumed only a few provinces of net positive migration (Ontario, BC, and Alberta) with the rest bleeding citizens.
I compiled and processed the data spanning 11 years from 2007 to 2018. I was able to transform the data to create a province-to-province chord diagram. It is a little difficult to read since Canada has many small provinces, so I added a diverging bar charts to show to show the totals for the period. I will post the R code on my GitHub page and update the code and numbers in 6 months time when we have estimates on the change during COVID. 

<p align="center">
  <img align="center" src="https://jfm-data.github.io/images/Canada_migration.jpg">
</p> 

What was most surprising about the analysis is that it revealed Ontario being a net negative province. I assumed Toronto and Ottawa, large cities full of transplants, made Ontario the top draw for all Canadians. Secondly, I was shocked that the Atlantic provinces weren't clustered at the bottom. Newfoundland and Nova Scotia were only slightly negative and higher on the list than the non-Alberta Prairie provinces and Quebec! I suspect this might be strongly related with Ontario's net negative numbers. Perhaps seniors are re-locating east for cheaper property values and a slower pace of life. 

<p align="center">
  <img align="center" src="https://jfm-data.github.io/images/pyramidplot_can.png">
</p> 

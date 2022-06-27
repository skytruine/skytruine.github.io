---
layout:     post
title:      "Air Pollution Perception Bias Based on Social Media: Spatiotemporal Pattern & Mechanism"
date:       2020-01-01 12:00:00
author:     "Yifan"
catalog: true
tags: [archived project]
---

# 1. Introduction
&emsp;The project aims to measure the public's perception of air pollution using geo-tagged weibo data (the Chinese Twitter) and to further discuss the discrepancy between perceived and actual air pollution levels and the rationale behind it. We used the web crawler technology to obtain the daily monitoring data of China's air monitoring sites from 2012 to 2014 and tens of millions Weibo records in the corresponding period. Taking the data when the air quality is good as the benchmark, we represent the public's perception of air pollution through the fluctuation of weibo check-in number and weibo emotional fluctuation, moreover, the air pollution perception deviation was measured by  the difference between the normalized perception index and AQI.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190808140558992.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3NreXRydWluZQ==,size_16,color_FFFFFF,t_70)
# 2. Main content
# 2.1 Weibo data and pollution data capture
&emsp;We randomly grabbed the personal data of 1 million weibo users and their posts.The most important personal data are location and gender.We used the location to represent the user's city, and the gender attribute was used when discussing the population difference of air pollution perception bias.For the body content of weibo, we pay attention to two kinds of information, one is the non-forwarding body of weibo, and the other is the geographical tag of weibo.In order to further support the research, we conducted text emotional analysis on the body of weibo, and divided the corresponding activities of weibo into outdoor and indoor ones through the analysis of geographical tags.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190808152337289.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3NreXRydWluZQ==,size_16,color_FFFFFF,t_70)
&emsp;We captured the historical data of air pollution in city level from 2012 to 2014 from China's online air quality monitoring and analysis platform(https://www.aqistudy.cn). The specific attributes of air pollution data includes AQI, PM2.5, PM10, CO, NO2, O3 and SO2.For the classification of air pollution, we adopted the general standard in China, and considered that when the AQI is greater than 100, the city was in the state of pollution.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190808152351471.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3NreXRydWluZQ==,size_16,color_FFFFFF,t_70)
# 2.2 Establish the air pollution society perception evaluation index system
&emsp;Taking the data when the air quality is good as the benchmark, we represent the public's perception of air pollution through the fluctuation of weibo check-in number and weibo emotional fluctuation, moreover, the air pollution perception deviation was measured by  the difference between the normalized perception index and AQI.
# 2.3 Analysis of spatial and temporal characteristics of air pollution perception deviation
&emsp;The spatial and temporal patterns of various air pollution perception deviation indicators reflecting different air pollution and perception patterns were mined, and their spatial and temporal distribution patterns were analyzed and compared.
# 2.4 Deviation mechanism research and driving force analysis
&emsp;Based on the analysis of the mechanism of pollution deviation, the spatiotemporal geographical weighted regression model is used to analyze the relationship between the mean of pollution perception deviation of each city and the environmental, economic and social factors of the city.
# 3. My contribution
 - Obtained massive Weibo data and city-level air pollution data using web crawler.
 - Conducted text sentiment analysis on Weibo data.
 - Proposed a method to measure the deviation between air pollution monitoring and social pollution perception.
# 4. Additional information
&emsp;Unfortunately, during the above project, due to personnel changes and other disturbances, we failed to complete the project completely as planned and output the results in the form of a paper.Existing analysis results show that there are significant differences in air pollution perception bias among people of different genders and cities, which are spatially correlated and influenced by urban environmental, economic and social factors.
&emsp;Recently, I noticed the "weibo smog" project of the MIT's senseable city lab (http://senseable.mit.edu/weibo_smog/), which uses weibo check-in data to explore the influence of air pollution on residents' activities. This research has rekindled my interest in relevant researches, and I hope that in the near future, my collaborators and I can further improve the work that has not been completed before.

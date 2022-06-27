---
layout:     post
title:      "The Optimization Research of First Aid Resource Allocation in Wuhan Based on GIS"
date:       2020-01-01 12:00:00
author:     "Yifan"
catalog: true
tags: [archived project]
---
# 1. Introduction
&emsp;This is the first independent research project I have come into contact with and the starting point of my academic career. The project aims to optimize the allocation of first-aid resources in Wuhan. Based on the discussion of the accessibility of first-aid resources in Wuhan, it established a rational evaluation system for the distribution of first-atid sites and an optimization model for the setting of first-aid sies, and further proposed two stratagies to help optimize the allocation of first-aid resources: ① Use neural networks to predict the load of each first-aid station and allocate emergency resources such as emergency vehicles as needed; ②Set temporary parking area for ambulances in the service area of ​​the first-aid site.
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190806224916261.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3NreXRydWluZQ==,size_16,color_FFFFFF,t_70)
![在这里插入图片描述](https://img-blog.csdnimg.cn/20190806225156780.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3NreXRydWluZQ==,size_16,color_FFFFFF,t_70)

# 2. My contribution
-  Used 2SFCA to obtain the potential accessibility of first-aid services
 - Established a comprehensive evaluation index system to evaluate the availability of first aid service.
 - Predicted First aid stations’ load using ARMA model and NAR neural network.
 - Established serval multi-objective linear optimization models for first aid station site selection under different strategies, and solved them using simulated annealing genetic algorithm (SAGA).
 - Applied spatiotemporal hotspot analysis to figure out and visualize the patterns of different types of emergency events.
# 3. Publications
[\[1\] Sun, Y., Zhao, M., Zhang, K., Chen, B., Lin, H., &Lu, C., 2017. Bibliometric Analysis of Medical Geographic Information System Research. Medical information, 30, 53-56. (In Chinese)](https://file-1253725173.cos.ap-chengdu.myqcloud.com/PWeb/SPublication_J_CN_2017_2.pdf)
[\[2\] Sun, Y., Zhao, M., Liu, Z., Lin, H., Zhang, K., &Chen, B., 2017. Evaluation Indexes and Empirical Research on the Rationality of Layout of First-aid Sites. Journal of Medical Informatics, 38, 48-53. (In Chinese)](https://file-1253725173.cos.ap-chengdu.myqcloud.com/PWeb/SPublication_J_CN_2017_1.pdf)

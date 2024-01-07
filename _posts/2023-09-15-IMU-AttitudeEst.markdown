---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_IMU_Est
title: "IMU Attitude Estimation using Madgwick and Unscented Kalman Filters"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Shiva Surya Lolla
# multiple category is not supported
category: Projects
# multiple tag entries are possible
tags: [Python]
# thumbnail image for post
img: ":Madg_UKF/attitude_est.png"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-09-15 10:04:30 +0900

# seo
# if not specified, date will be used.
#meta_modify_date: 2023-01-09 10:04:30 +0900
# check the meta_common_description in _data/owner/[language].yml
#meta_description: ""

# optional
# please use the "image_viewer_on" below to enable image viewer for individual pages or posts (_posts/ or [language]/_posts folders).
# image viewer can be enabled or disabled for all posts using the "image_viewer_posts: true" setting in _data/conf/main.yml.
#image_viewer_on: true
# please use the "image_lazy_loader_on" below to enable image lazy loader for individual pages or posts (_posts/ or [language]/_posts folders).
# image lazy loader can be enabled or disabled for all posts using the "image_lazy_loader_posts: true" setting in _data/conf/main.yml.
#image_lazy_loader_on: true
# exclude from on site search
#on_site_search_exclude: true
# exclude from search engines
#search_engine_exclude: true
# to disable this page, simply set published: false or delete this file
#published: false
---
## **Summary:**
In this project, an IMU attitude estimation system was developed using five methods: accelerometer-only, gyroscope-only, a complementary filter, a Madgwick filter, and an Unscented Kalman filter (UKF). The project utilized pre-existing ground truth data from a Vicon motion capture system, paired with gyroscope and accelerometer data from an ArduIMU + V2. An essential step was the preprocessing of these sensor measurements to correct biases in the gyroscope and accelerometer.

The project's emphasis was on the utilization of the Madgwick and UKF methods for accurate attitude estimation. These advanced techniques were applied to compute roll, pitch, and yaw estimates. The estimates were then plotted and compared against the available ground truth data from the Vicon system, across various datasets. The comparisons, detailed in the report, are supplemented with animations for enhanced visualization.

The comparison results revealed that the attitude estimates from both the Madgwick and UKF methods showed close conformity with the ground truth data. This finding underscores the precision and effectiveness of these filtering techniques in IMU attitude estimation.

## **Github:**
[Link](https://github.com/Chaitanya-01/Magical-Filtering-RBE595)

## **Report:**
[Link](https://drive.google.com/file/d/1o-r79p3kwjRQDIR4JlsRGdJaqDAWyf7p/view?usp=sharing)

## **Animation 1:**
<iframe width="560" height="315" src="https://www.youtube.com/embed/QqZrlZt3IWk?si=KFj19L5qvRLlBc2P" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **Animation 2**
<iframe width="560" height="315" src="https://www.youtube.com/embed/VEVUZr9buow?si=WUYTNHcoAdgnC2sI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>






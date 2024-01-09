---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_Agent_Motion
title: "Agent Motion Prediction using Deep Learning for Autonomous Navigation"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Shiva Surya Lolla
# multiple category is not supported
category: Projects
# multiple tag entries are possible
tags: [PyTorch]
# thumbnail image for post
img: ":Agent_Motion/motion_pred.jpeg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-05-03 10:04:30 +0900

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
This project tackled the challenge of predicting future trajectories of entities such as pedestrians, bicycles, and vehicles in real-world environments, a crucial aspect for autonomous vehicle decision-making and collision avoidance. A novel deep learning framework was developed, aimed at predicting an agent’s future positions using Birds Eye View (BEV) images and past trajectory data from Woven Planet’s motion prediction dataset. The approach combined a ResNet50 baseline with a sequence-to-sequence model, capturing both spatial image data and sequential trajectory data to enhance prediction accuracy.

The primary innovation lay in integrating these two models to process and analyze complex spatial and temporal patterns in the data. This methodology was designed to yield more robust and accurate future trajectory predictions compared to existing models. A thorough analysis was conducted, comparing the performance of this new approach against the baseline model. Initially, it was anticipated that the proposed method would significantly outperform the baseline. However, the results revealed that, within the confines of the available training data and project scope, the improvement in performance was not as substantial as expected.

These findings led to a comprehensive summary of insights and limitations encountered during the project. Despite the modest advancements over the baseline, the project offered valuable lessons and highlighted potential areas for further improvement. Future work was proposed to expand the dataset and refine the model, aiming to achieve greater accuracy in trajectory prediction for autonomous vehicles. 

## **Github:**
[Link](https://github.com/omgaikwad08/Agent-Motion-Preditction)

## **Report:**
[Link](https://drive.google.com/file/d/1l-NGrGgitmoy3Z2imV5qNMXszRSEHPof/view?usp=sharing)

## **Presentation Video:**
<iframe width="560" height="315" src="https://www.youtube.com/embed/FUbTU5KM1EM?si=v7myOsyEL2O_dJ_X" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>







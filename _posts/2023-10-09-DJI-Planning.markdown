---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_DJI_Perc
title: "RRT*-Based Planning and Control pipeline for the DJI Tello EDU Quadcopter"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Shiva Surya Lolla
# multiple category is not supported
category: Projects
# multiple tag entries are possible
tags: [Python, Blender]
# thumbnail image for post
img: ":DJI_Planning/RRT_Tello.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-10-09 10:04:30 +0900

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
In this project, a comprehensive quadcopter path planning and control pipeline was created. The initial setup involved defining start and goal locations, as well as obstacles, within a pre-mapped environment. To navigate this environment, the Rapidly-exploring Random Tree Star (RRT*) algorithm was employed to generate three-dimensional waypoints.

For code validation and a more intuitive understanding of the planned path, the waypoints and the path planner's tree were visualized using Blender. These waypoints then became the basis for trajectory planning, which aimed to create a minimum snap trajectory. This approach ensured smooth navigation across the waypoints.

To bring this plan into action, a Proportional-Integral-Derivative (PID) controller was implemented. This controller was crucial in guiding the quadcopter from its starting point to the target goal, closely following the devised trajectory.

The culmination of this project was the practical deployment of the developed navigation stack on the DJI Tello EDU quadcopter. This real-world application demonstrated the system's ability to navigate effectively from start to finish within a mapped environment, showcasing the successful integration of advanced planning algorithms and control systems.

## **Github:**
[Link](https://github.com/Chaitanya-01/P2-Path-Following-RBE595)

## **Report:**
[Link](https://drive.google.com/file/d/1x2u4JSi61k8i5ROOObEdO_TMS6pKRYl0/view?usp=sharing)

## **Run Video:**
<iframe width="560" height="315" src="https://www.youtube.com/embed/1HOdJ2UzKZM?si=RiU3Ia0_W6W-UwSz" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **Visualization**
<iframe width="560" height="315" src="https://www.youtube.com/embed/L_uQLSAiuyI?si=F9LJtNqrPpRnvX1r" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>






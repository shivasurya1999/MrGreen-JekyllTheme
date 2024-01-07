---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_DJI_GapFlyt
title: "Optical Flow-Driven Autonomy: Navigating the DJI Tello EDU Quadcopter Through Irregular Gaps"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Shiva Surya Lolla
# multiple category is not supported
category: Projects
# multiple tag entries are possible
tags: [Python, OpenCV, PyTorch, Blender]
# thumbnail image for post
img: ":DJI_GapFlyt/GapFlight.png"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-11-21 10:04:30 +0900

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
This project involved developing a perception system for the DJI Tello EDU quadcopter, enabling it to autonomously navigate through irregularly shaped, unknown windows within a wall. The main challenge was to identify and fly through the largest gap in a wall that featured gaps of varying sizes. This task was complicated by the similarity in texture between the foreground (wall) and the background, rendering traditional methods like thresholding and edge detection ineffective.

To overcome this, the project leveraged the concept of optical flow, utilizing the quadcopter's movement to distinguish gaps in the wall. The procedure began by positioning the quadcopter so that it had a clear view of the entire gap. The next step involved capturing the optical flow from the frames recorded by the quadcopter as it moved vertically in front of the wall. This flow data was then analyzed and processed to accurately define the contours of the largest gap and locate its central point.

Once the center of the gap was identified, visual servoing techniques were employed. These techniques enabled the quadcopter to align its camera's center with the gap's center, ensuring precise and safe navigation through the gap. This approach not only addressed the challenges posed by texture similarity but also demonstrated an innovative use of optical flow and visual servoing in autonomous navigation.

## **Github:**
[Link](https://github.com/Chaitanya-01/P4-navigating-the-unknown)

## **Report:**
[Link](https://drive.google.com/file/d/1oLerZucIXcNuciHgMpFx9Pgg9y2poERI/view?usp=sharing)

## **Run Video:**
<iframe width="560" height="315" src="https://www.youtube.com/embed/wt_jdC7YsPk?si=b7pHOx09WoFf63R4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **Visualization**
<iframe width="560" height="315" src="https://www.youtube.com/embed/kCroe-EPg3U?si=ik6Pp3moPOJQvGcd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>





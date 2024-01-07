---
# multilingual page pair id, this must pair with translations of this page. (This name must be unique)
lng_pair: id_NewtonMin
title: "Advanced Newton Optimizer Using MATLAB for Non-linear Multivariate Function Minimization"

# post specific
# if not specified, .name will be used from _data/owner/[language].yml
author: Shiva Surya Lolla
# multiple category is not supported
category: Projects
# multiple tag entries are possible
tags: [MATLAB, Nonlinear optimization]
# thumbnail image for post
img: ":NewtonMin/NewtonMinim.jpg"
# disable comments on this page
#comments_disable: true

# publish date
date: 2023-12-10 10:04:30 +0900

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
In this project, I developed and rigorously tested an advanced Newton optimization routine from the ground up, specifically for minimizing multivariate non-linear functions.

At the heart of this endeavor was the implementation of Newton's method, which employed Hessian conditioning and the computation of the Newton direction. The optimizer was designed to transition to back-tracking line searches when the Armijo condition was not met. Furthermore, if repeated line searches failed to satisfy the Armijo condition, the optimizer would switch to a Double Dogleg trust region strategy. This deviation from the Newton direction was crucial in navigating the optimizer more effectively towards the function's minimum. 

To validate the optimizer's performance, I conducted extensive testing on benchmark functions, including Rosenbrock, Extended Powell, and Wood functions. The optimizer demonstrated high accuracy and adaptability under various initial conditions. The project also featured detailed visualizations, such as graphs and summary tables, to clearly demonstrate the methodology and results. These visual tools were instrumental in illustrating the complex dynamics of the optimization process.

## **Github:**  
[Link](https://github.com/shivasurya1999/AdvancedNewtonOptimization/tree/main)

## **Report:**
[Link](https://drive.google.com/file/d/1rz9mNh902f9pArbsI1I4rCAbQtptJ4HU/view?usp=sharing)

<!-- ## **Run Video:**
<iframe width="560" height="315" src="https://www.youtube.com/embed/wt_jdC7YsPk?si=b7pHOx09WoFf63R4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## **Visualization**
<iframe width="560" height="315" src="https://www.youtube.com/embed/kCroe-EPg3U?si=ik6Pp3moPOJQvGcd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> -->





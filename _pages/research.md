---
layout: archive
title: "Research Projects"
permalink: /research/
author_profile: true
---

## Current Research

In my current research, I focus primarily on the digital systems (websites, smartphone apps etc) and the privacy mechanisms they provide. By using the services, user take certain privacy risks, which are not always known to the users. My research attempts to use Machine Learning and Natural Language Processing to build technological solutions which empower users and enable them to make informed choices regarding their data. More details about the research projects I have been involved in are given below:

### PriSEC 
In this project, we are lookings at online users' interaction with privacy controls. Online service providers offer online menus and forms so users can control their privacy settings. However, in their current form, privacy control settings suffer from usability and reachability issues, making it hard for users to exercise informed control. To mitigate this and make the privacy controls more usable, we designed and developed PriSEC - a privacy setting enforcer that transforms privacy control pages from domains using machine learning techniques into a machine-readable format. Applications can be built on this machine-readable format to enhance the user experience. We demonstrated this by developing a browser extension that leverages a search interface where the users can easily select and enforce the desired setting.  
> Khandelwal, Linden, T., Harkous, H., & Fawaz, K. (2021). PriSEC: A Privacy Settings Enforcement Controller. 30th USENIX Security Symposium, August 2021. 
> [[Code & Dataset]](https://github.com/wi-pi/prisec_data)


### Surfacing Privacy Settings Using Semantic Matching
Online services utilize privacy settings to provide users with control over their data. However, these privacy settings are often hard to locate, causing the user to rely on provider-chosen default values. In this work, we train privacy settings centric encoders and leverage them to create an interface that allows users to search for privacy settings using free-form queries. To achieve this, we create a custom Semantic Similarity dataset, which consists of real user queries covering various privacy settings. We then use this dataset to fine-tune the state of the art encoders. Using these fine-tuned encoders, we perform semantic matching between the user queries and the privacy settings to retrieve the most relevant setting. Finally, we also use these encoders to generate embeddings of privacy settings from the top 100 websites and perform unsupervised clustering to learn about the online privacy settings types.  
> Khandelwal, R., Nayak, A., Yao, Y., Fawaz, K. (2020). Surfacing Privacy Settings using Semantic Matching. Proceedings on PrivateNLP@EMNLP 2020. 
> [[Code & Dataset]](https://github.com/wi-pi/surface_privacy_dataset)


### The Privacy Policy Landscape After the GDPR
In this project, we studied the impact of the General Data Protection Regulation (GDPR) on the landscape of privacy policies online. We conducted the first longitudinal, in-depth, and at-scale assessment of privacy policies before and after the GDPR. We gauged the complete consumption cycle of these policies, from the first user impressions until the compliance assessment. To achieve this, we created a diverse corpus of two sets of 6,278 unique English-language privacy policies from inside and outside the EU, covering their pre-GDPR and post-GDPR versions. We further developed a workflow for the automated assessment of requirements in privacy policies using natural language processing techniques.

> Linden, T., Khandelwal, R., Harkous, H., & Fawaz, K. (2020). The privacy policy landscape after the GDPR. Proceedings on Privacy Enhancing Technologies, 2020(1), 47-64. 
> [[PDF]](https://petsymposium.org/2020/files/papers/issue1/popets-2020-0004.pdf) 
> [[Code & DataSet]](https://github.com/wi-pi/GDPR)


<!-- ## Research In Physics -->
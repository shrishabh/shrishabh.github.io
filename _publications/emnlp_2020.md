---
title: "Surfacing Privacy Settings Using Semantic Matching"
collection: publications
permalink: /publication/emnlp_2020
excerpt: 'Developing privacy settings centric embeddings to allow users to search for privacy settings across domains.'
date: 2020-11-20
venue: 'PrivateNLP @ EMNLP'
paperurl: 'https://www.aclweb.org/anthology/2020.privatenlp-1.4.pdf'
# citation: 'Your Name, You. (2009). &quot;Paper Title Number 1.&quot; <i>Journal 1</i>. 1(1).'
---

## Abstract
Online services utilize privacy settings to provide users with control over their data. However, these privacy settings are often hard to locate, causing the user to rely on provider-chosen default values. In this work, we train privacy settings centric encoders and leverage them to create an interface that allows users to search for privacy settings using free-form queries. To achieve this, we create a custom Semantic Similarity dataset, which consists of real user queries covering various privacy settings. We then use this dataset to fine-tune the state of the art encoders. Using these fine-tuned encoders, we perform semantic matching between the user queries and the privacy settings to retrieve the most relevant setting. Finally, we also use these encoders to generate embeddings of privacy settings from the top 100 websites and perform unsupervised clustering to learn about the online privacy settings types.

> The paper can be [downloaded](https://www.aclweb.org/anthology/2020.privatenlp-1.4.pdf) from here. <br>
> The talk and presentation can be found [here](https://virtual.2020.emnlp.org/paper_WS-24.11.html).
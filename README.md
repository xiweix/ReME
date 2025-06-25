<div align="left">

# ReME
Xiwei Xuan, Ziquan Deng, and Kwan-Liu Ma
##### [ICCV'25] ReME: A Data-Centric Framework for Training-Free Open-Vocabulary Segmentation

<a name="intro"></a>

## Introduction

Training-free open-vocabulary semantic segmentation (OVS) aims to segment images given a set of arbitrary textual categories without costly model fine-tuning. Existing solutions often explore attention mechanisms of pre-trained models, such as CLIP, or generate synthetic data and design complex retrieval processes to perform OVS. However, their performance is limited by the capability of reliant models or the suboptimal quality of reference sets. In this work, we investigate the largely overlooked data quality problem for this challenging dense scene understanding task, and identify that a high-quality reference set can significantly benefit training-free OVS. With this observation, we introduce a data-quality-oriented framework, comprising a data pipeline to construct a reference set with well-paired segment-text embeddings and a simple similarity-based retrieval to unveil the essential effect of data. Remarkably, extensive evaluations on ten benchmark datasets demonstrate that our method outperforms all existing training-free OVS approaches, highlighting the importance of data-centric design for advancing OVS without training.


## 
Code and dataset will be released soon.
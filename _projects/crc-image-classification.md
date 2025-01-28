---
title: "Enhancing CRC image classification using CNN"
collection: projects
topic: artificial_intelligence
permalink: /projects/crc-image-classification/
abstract: "Research project I conducted at ECNU, supervised by <a href='https://faculty.ecnu.edu.cn/_s43/cyx_en/main.psp'>Prof. Chen YiXiang</a>, 2018 ~ 2021. In this research project, we introduce a method to improve the classification accuracy from previous studies that used the National Center for Tumor diseases (NCT) data sets. We utilized transfer learning and fine-tunning techniques to improve the accuracy."
excerpt: "<img src='/cv/images/projects/crc-image-classification/F3.large.jpg' width='700px'>"
date: 2021-6-01
---

{% include base_path %}

*Last updated in January 2025.*

---

## Introduction

Research project I conducted at [ECNU](https://english.ecnu.edu.cn/), supervised by <a href='https://faculty.ecnu.edu.cn/_s43/cyx_en/main.psp'>Prof. Chen YiXiang</a>, 2018 ~ 2021. In this research project, we introduce a method to improve the classification accuracy from previous studies that used the National Center for Tumor diseases (NCT) data sets. We utilized transfer learning and fine-tunning techniques to improve the accuracy. 

Our Experimentresults show that ResNet_50 network is the best CNN architecture so far for classifyingCRC histopathological images on the NCT Biobank open source dataset. In addition tothat using transfer learning allow us to obtain 97.7% accuracy on the validation dataset,which is better than all previous results we found in literature.

![model](/cv/images/projects/crc-image-classification/F3.large.jpg)

The training process is conducted as follows: We first download the model and parameters of ResNet_50 network trained on the ImageNet dataset. Then, we froze all123the parameters before the last few layers of the network. After that we fine-tune the fully connected layer and change the numbers of neurons of the dense layer as 9 for multi-class classification. Finally, we train the unfrozen layers of the network until achieve the best results.

![results](/cv/images/projects/crc-image-classification/F4.large.jpg)
![results_2](/cv/images/projects/crc-image-classification/F5.large.jpg)

## Relevant publication

For more technical details, please see our publication:
>**R. Al.Shawesh** and Y. X. Chen. “Enhancing histopathological colorectal cancer image classification by using convolutional neural network.” doi: [10.1101/2021.03.17.21253390](https://doi.org/10.1101/2021.03.17.21253390).

## For more info

For more information you can visit the public repository of the project on [github](https://github.com/radwanCS/ResNet_50_enhanced_for_CRC_image_classification).

<!--
## Demo

Here is a video demo of our system performing lung ultrasound examination of the anterior-superior region of a volunteer through the second and third intercostal spaces.

<video controls style="width: 100%; height: auto;" controlsList="nodownload" oncontextmenu="return false;" preload="auto">
  <source src="/files/webm/lus.webm" type="video/webm">
  Your browser does not support the video tag.
</video>
-->

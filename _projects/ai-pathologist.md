---
title: "AI Pathologiest desktop application for pathologist"
collection: projects
topic: software_development
permalink: /projects/ai-pathologiest/
abstract: "This project is a school project I participated in at ECNU, supervised by <a href='https://faculty.ecnu.edu.cn/_s43/cyx_en/main.psp'>Prof. Chen YiXiang</a>, 2020 ~ 2021. In this project, we created a software made to aid pathologiest in their labwork, using our fined-tuned artificial model from a previous research study." 
excerpt: "<img src='/cv/images/projects/ai-pathologist/interface2.png' width='700px'>"
date: 2021-06-15
---

{% include base_path %}
*Last updated on January 2025.*

---

## Introduction

This project is a school project I participated in at ECNU, supervised by <a href='https://faculty.ecnu.edu.cn/_s43/cyx_en/main.psp'>Prof. Chen YiXiang</a>, 2020 ~ 2021. In this project, we created a software made to aid pathologiest in their labwork, using our fined-tuned deep learning model from a previous research study."

This Software program can assets pathologists in diagnose histology images of Colorectal cancer, and produce reliable results, this will be extremely beneficial for physicians, since this will surely help them increase their work efficiency and also allow lab doctors to diagnose histology images of CRC with no requirement for prior knowledge in this field.

The innovation of the project can be summarized in these points：

1. Using our Fine-tunned neural network to create the most accurate and reliable
CRC image classifier program.
2. The software will be capable of running using either the CPU or GPU,
3. Most computers will be able to run the software. there is no requirement for owning a NIVIDIA video card or installing CUDA software or any another third-party software in the case of the CPU version of the software.
4. Provides an option for pathologist to conduct manual diagnosis when the
accuracy results are not reliable enough.

<img src="/cv/images/projects/ai-pathologist/training_dataset.png" alt="dataset" width="600px"/>

### Functional Requirements

1. Upload images or entire folders using the program to classify them.
2. Classify images after being uploaded.
3. Output successfully classified images into several folders, each for a specific type of tissue.
4. Provide a manual diagnosis option when the neural network has finished its classification and the result accuracy is below 60% for any single image.
5. Show model classification results for each single image.

![usecase](/cv/images/projects/ai-pathologist/flowchart.png)

### Performance requirements

1. **Time characteristics:** The software responds quickly enough and the image classification is fast enough to meet user requirements.
2. **Usability:** The operation interface is simple and clear, easy to operate, and verify the data with restricted format and data type.

![UI](/cv/images/projects/ai-pathologist/user_interface.png)

## Relevant publication

For more technical details, please see our publication:

>**R. Al.Shawesh**, “Histopathological colorectal cancer image classification based on convolutional neural network and tools development,” Master’s thesis, East China Normal University (ECNU), Shanghai, China, 2021. Accessed: Dec. 30, 2024. [Online]. Available: [xueshu.baidu.com](https://xueshu.baidu.com/usercenter/paper/show?paperid=1v1y0e90f55404w0js3p00w0p5214691)

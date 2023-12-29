# A NEW DEEP-LEARNING APPROACH FOR CELL DETECTION AND COUNTING

## Abstract
Cell adhesion is a fundamental biological process underpinning various physiological and pathological phenomena, including tissue repair and cancer metastasis. Traditional assays for assessing cell adhesion, while straightforward, suffer from poor reproducibility and low throughput. This study introduces a novel deep learning-based approach utilizing the You Only Look Once (YOLO) convolutional neural networks to automate cell detection and counting, thereby enhancing the precision and efficiency of cell adhesion assays. Employing the YOLOv3, YOLOv5, and YOLOv8 architectures, we address the challenges of variability in cell density and illumination within adhesion experiments. Our methodology involved the analysis of cell cultures using AQP2-RCCD1 cells and subsequent adhesion assays, with the data captured and processed using the latest YOLO models. These models were trained on various image resolutions to assess the trade-offs between image quality and computational efficiency, significantly optimizing the detection process. In commitment to open science principles, the source code and trained models will be shared to foster innovation and collaboration in the field. The study not only demonstrates the integration of cutting-edge AI in cell biology but also sets a precedent for the wider application of machine learning in biomedical research.

## Introduction
Cell adhesion plays a pivotal role in numerous biological processes, such as cell proliferation, migration, wound healing, epithelial-mesenchymal transition, and tumor metastasis. Traditional methods of assessing cell adhesion, typically involving 'wash assays', are manual, time-consuming, and often less reproducible.

With the advent of Artificial Intelligence (AI), and specifically Deep Learning (DL), a subset of AI, there has been a significant shift in automating tasks that were traditionally manual. DL, particularly deep neural networks, are known for their ability to learn directly from data, outperforming conventional techniques in various applications. However, the requirement of large datasets and the computational expense remains a challenge, partially mitigated by transfer learning approaches.

Recent advancements in AI algorithms, especially convolutional neural networks like You Only Look Once (YOLO), have shown promising results in automating and enhancing the accuracy of cell counting, as demonstrated in various studies employing different YOLO versions.

## Our Study
In this study, we extend the application of YOLO algorithms, specifically YOLOv3, YOLOv5, and YOLOv8, to cell adhesion experiments. Our aim is to develop a robust and automatic method for cell counting in adhesion imagery, addressing challenges such as variability in cell density and lighting conditions. This work is expected to significantly contribute to understanding key biological processes and developing new medical therapies.

## Commitment to Open Science
Aligned with open science principles, we plan to release both the source code and the developed machine learning models. We believe that sharing resources can help accelerate advancements in the field. By making these tools accessible, we aim to empower researchers to replicate, refine, and apply our methodologies, fostering innovation and transparency in scientific research.

## Paper Link
The paper associated with this repository is currently being written and is not yet published.

## YOLO Versions Used in This Study
In our study, we have utilized the following versions of the YOLO algorithm:

1. **YOLOv3**: An Incremental Improvement by Joseph Redmon and Ali Farhadi (2018). This version introduced several improvements over its predecessors, particularly in terms of speed and accuracy. [Read the paper here](https://arxiv.org/abs/1804.02767).

2. **YOLOv5**: Developed by Ultralytics, YOLOv5 is a more recent and advanced iteration of the YOLO series, known for its efficiency and ease of use. [Check out the GitHub repository](https://github.com/ultralytics/yolov5).

3. [Link to Roboflow]()

## Repository Structure
This repository is organized into several key directories, each serving a specific role in our project:

### Notebooks
- _Description_: Contains Jupyter notebooks that demonstrate the implementation and results of our YOLO-based cell detection models. These notebooks are well-annotated and cover various aspects from data preprocessing to model inference and result visualization.

### Pretrained Models
- _Description_: Holds pretrained models, which are used as starting points in our study. These YOLO architecture-based models have been pre-trained on general datasets and fine-tuned for our specific tasks in cell detection.

### Scripts
- _Description_: This directory includes all scripts necessary for processing, training, and evaluating our models. It encompasses data preparation scripts, training routines, and evaluation scripts, along with other utility scripts essential to the project.

### Trained Models
- _Description_: Contains the models trained during our research, specifically optimized YOLOv3, YOLOv5, and YOLOv8 models for cell adhesion imagery. This folder may include model weights, configuration files, and other training artifacts.

## Contact
For further inquiries, please contact:
Juan J. Casal, PhD
Email: [jcasal@fmed.uba.ar](mailto:jcasal@fmed.uba.ar)


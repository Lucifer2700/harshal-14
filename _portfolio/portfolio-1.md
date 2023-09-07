---
title: "Road Segmentation using Convolutional Neural Networks (CNN)"
excerpt: "Autonomous Vehicle drivable area estimation<br/><img src='/images/Model_prediction.png'>"
collection: portfolio
---

Introduction
Road segmentation is a critical task in computer vision for autonomous driving. This project demonstrates the implementation of a CNN-based road segmentation model that takes input images and predicts pixel-wise road and non-road classes.

Dataset
I used the UC Berkeley BDD 100K dataset for training and evaluation. It contains labeled images with pixel-level annotations for road regions. The dataset includes a variety of scenarios, lighting conditions, and road types. Test_Image Fig. Test Image

Model Architecture
Our road segmentation model is built using a FCN architecture, which has proven effective for image segmentation tasks. The architecture consists of an encoder that captures image features and a decoder that produces the segmentation mask. The model is trained end-to-end on the dataset.

Results
Our trained model achieves an accuracy of over 95% on the test dataset. The road segmentation output demonstrates accurate identification of road regions in various environments.
Code can be fouund here<\href https://github.com/Lucifer2700/UCBerkley_Segmentation \href>

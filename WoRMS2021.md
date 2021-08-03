---
layout: post-default
---
![worms2021]({% link /assets/img/worms2021.png %})

The third edition of The International Workshop on Reading Music Systems (WoRMS) was held in a hybrid live/virtual setting last Friday, 23rd of July. It brought together many researchers working in Optical Music Recognition (OMR) and also from the industry. This edition 11 papers researching a broad list of topics in OMR were presented, and an outstanding keynote from Anthony Wilkes (Organum Ltd) was talking on The design of ReadScoreLib. 

Below I will try to summarise some of the papers presented. 

[Hybrid Annotation Systems for Music Transcription by Ioannis Petros Samiotis, Christoph Lofi and Alessandro Bozzon](https://drive.google.com/file/d/17BdTUfU6Fk8qyrpxo6L-BGTqIhLvStL5/view)

Dwells on the idea of bringing human annotation and automated methods together for music transcription. In other words, how can a non-specialist carry out music transcription with careful task interaction using AI automated methods. Among 144 workers that executed tasks in MTurk, those with formal knowledge in music were rare. Audio extracts of target music scores were offered to increase performance, especially for short segments of one or two measures. For longer segments, audio extracts have shown better results against textual measures, but a combination of the two was used as more preferable. 


[Implementation and evaluation of a neural network for the recognition of handwritten melodies by Nils Wenzlitschke](https://drive.google.com/file/d/17Dp9gIjQPZVwSFJzKK8QA6Xjcgv894wj/view)

This research came as a fruit of a current need for digital archiving and digitalisation of music for the
University Library of Regensburg. It evaluates if the existing SOTA deep learning architecture is able to recognise handwritten monophonic scores for the purpose of digitalisation. Based on existing work, the architecture includes two neural networks: a stave recognition network using autoencoders and an end-to-end note recognition using recurrent convolutional networks. One limitation mentioned is the amount of annotated data available for this research. 


[DoReMi: First glance at a universal OMR dataset by Elona Shatri and George Fazekas ](https://scholar.google.com/scholar_url?url=https://arxiv.org/abs/2107.07786&hl=en&sa=T&oi=gsb&ct=res&cd=0&d=14810089764046134622&ei=zZr-YJCFNYqImgHdz7SYBQ&scisig=AAGBfm3Isc8XU8MWS1mRRgnn5ctiET7y8g)

We were also part of this workshop presenting our work in our newly published dataset DoReMi. We presented some of the challenges the lack of a well-annotated, that supports more than one stage of OMR poses and how DoReMi moves closer to such dataset. Furthermore, statistics on the dataset and baseline experiments on object detection using Faster R-CNN models. 

[The Challenge of Reconstructing Digits in Music Scores by Alexander Pacha](https://drive.google.com/file/d/10uUCaORERAzD-ISSm6FUeNNOOzrTRDzF/view)

Pacha presented some focused research he is currently conducting at e[note](https://enote.com/index) in recognising and reconstructing the digit elements in sheet music. He shows the main challenges posed by the ambiguity of the variations in their classes, their contextual nature and more computer vision issues. He then shows the results in using deep learning to recognise digits. The network was trained in synthetic samples and achieved a validation accuracy of 95%, which does not live it up in real-world scores. To address it was fine tunned on 7000 manually annotated real scores, but yet again, accuracy does not reach 60%. In the end, this opened up a long discussion in the workshop on why does this happen and the ways to tackle it. 

[Detecting Staves and Measures in Music Scores with Deep Learning](https://drive.google.com/file/d/1uSIrbiLrx1RfXEV86STS7XRuwJoa34O7/view)

This paper investigates strategies of detecting measures, staves and system measures using machine learning. That is to aid the detection of structural elements as a basis for an OMR system. A neural network is trained in handwritten music scores to generate annotations for typeset music. Detectron2 was used as a framework and Faster R-CNNs as a model to predict the bounding boxes in images. The datasets used for training were MUSCIMA++ and AudioLabs datasets. They applied the model in three settings: single class models (system measures, stave measures, staves), two class models (system measures & staves) and three class models (system measures & stave measures & staves). The first setting is performing best. However, considering that that model lacks diversity, it might not work well for every kind of sheet music. 

[Unsupervised Neural Document Analysis for Music Score Images](https://drive.google.com/file/d/1ZBRaOwsTkdOUo6sfm9xdQPuPMNyM89ho/view)

Given the lack of large training annotated set, this study suggests using Domain Adaptation (DA) based on adversarial training. The propose combining DA and Selectional Auto-Encoders for unsupervised document analysis. They utilise three corpora manually labelled for the layers: SALZINNES, EINSIEDELN and CAPITAN, and using F-score as an evaluation metric. Results obtained show the proposed method slightly improves state-of-the-art, but such adaptation should not be carried out in every type of layer. 

[Multimodal Audio and Image Music Transcription](https://drive.google.com/file/d/1ZDlU0WDmqC4-37s2gkCf2nOAt4Z5Ow-S/view)

This paper draws attention to Optical Music Recognition (OMR) and Automatic Music Transcription (AMT) similarities and exploits them to assist each field. The paper presents a proof-of-concept that combines end-to-end AMT and OMR systems predictions over a set of monophonic scores. Using Symbol Error Rate (SER), they show that a fusion model of the two can slightly improve the error rate in OMR.

[Sequential Next-Symbol Prediction for Optical Music Recognition](https://drive.google.com/file/d/1o4zm_fx_Fa7zclWkqgbVLx2x3DuvZidz/view)

This study proposes to address the lack of large training sets with a sequential classification-based approach for music scores. That is by predicting the symbol locations and their respective music-notation label using Convolutional Neural Networks (CNN). 

[Completing Optical Music Recognition with Agnostic Transcription and Machine](https://drive.google.com/file/d/1WAhrcPRzpuoB1fJsMkGCZamIp1CHv3c5/view)

This work focuses on the last stage of OMR, encoding, where outputs from images are converted to a score encoding format. The paper investigates the implementations of recognition pipelines that use Machine Translation to do the encoding. 



[back](./)


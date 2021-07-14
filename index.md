---
layout: default
---

* [Personal Website](www.elonashatri.co.uk)
* [School Page](http://eecs.qmul.ac.uk/profiles/shatrielona-1.html)
* [Medium](https://medium.com/@e.shatri1)

Hello there!

I'm a PhD candidate at the UKRI Centre for Doctoral Training in Artificial Intelligence and Music (AIM). I am part of Centre for Digital Music (C4DM) research group at Queen Mary University of London. 

My research interest is mainly Optial Music Recogntion as well as other MIR related subfields. My goal is to have computers read sheet music computationally. I started working in this problem in September 2019 when I was granted the studentship from QMUL and Steinberg GmBH with which we collaborate closely. 

My work focuses on how can we bring new machine learning solutions to the field of OMR and achieve an end-to-end solution to the problem.


Optical Music Recognition (OMR) is concerned with digitizing music sheets into a machine-readable format. Being able to compose, transcribe and edit music by means of taking a picture of a music sheet, would put musician?s workload at ease. Such automation would allow musicians to use search-ability and to perform quantitative measures in the musical pieces. This problem comes down to a simple, how can computers be made to read music. The output to this process being a machine-readable file such as MIDI, MusicXML, MEI files. The objective is outputting semantic mark-up identifying as many notational elements as possible, along with the relationship to their position in the original image.


Prior solutions have used algorithmic approaches and have involved layers of algorithmic rules applied to traditional feature detection techniques such as edge detection. One of the approaches we want to further investigate is using deep neural networks to solve the problem. Before going into this step another very important processing should be performed, that is, tackling the quality of the input picture of the music sheet. Image preprocessing steps are to be taken which will later help in the training step.

 

An OMR pipeline should be able to capture the right position and the relationships between two notes and its distinctive features. Pacha et al. (2018) proposed an end-to-end trainable object detector that can detect almost the full vocabulary of modern music notation in handwritten scores. Using deep convolutional networks in a dataset with symbol-level notations they achieve a mean average precision up to 80 %.

The OMR pipeline has four main blocks, and we want to tackle them one by one, using a deep learning technique and compare to the already existing techniques. If the DL techniques show improvements, then an end-to-end network is the final goal of our work. Since the existing datasets do not offer enough classes and data, the first step for use would be data augmentation. This will be done using the digitized musical sheets from music notation software Dorico, having this way a ground truth. These sheets will be subject to image degradation techniques, using the depredated images as inputs in our pipeline. The next step would be designing the methodology for object recognition and reconstruction using the deep neural network approach.


## [DoReMi Dataset](./doremi-dataset.html)
We recently published our DoReMi dataset at the [3rd International Workshop on Reading Music Systems 2021](https://sites.google.com/view/worms2021/home). We made our dataset available in [this page](https://github.com/steinbergmedia/DoReMi/releases/tag/v1.0) open for anyone to use it, experiment with it and maybe suggesting new ways to represent these data.  

Documentation is also availabe in the same repository of the data release. 

## Papers

*   [Optical Music Recogntion: State of the Art and Major Challenges at TENOR2020-2021](https://www.tenor-conference.org/proceedings/2020/23_Shatri_tenor20.pdf)
*   [DoReMi: First glance at a universal OMR dataset - WoRMS2021](https://sites.google.com/view/worms2021/home)

## Blogposts

*   [What is Optical Music Recognition?](https://towardsdatascience.com/what-is-optical-music-recognition-6515d8a53e01)
*   [A review on Super-Resolution](https://medium.com/analytics-vidhya/a-review-on-super-resolution-2c78cd77885a)
*   [A review of Generative Adversarial Networks](https://towardsdatascience.com/a-review-of-generative-adversarial-networks-9af21e94bda4)
*   [Optical Music Recognition: State of the Art and Major Challenges](https://towardsdatascience.com/optical-music-recognition-state-of-the-art-and-major-challenges-aa100923c78d)

## Teaching

### Machine Learning (Postgraduate) 2020
The aim of the module is to give students an understanding of machine learning methods, including pattern recognition, clustering and neural networks, and to allow them to apply such methods in a range of areas.

### Machine Learning for Visual Data Analysis (Postgraduate) 2021
The module will cover the following topics: The Discrete Fourier Transform and the frequency content of images. The design and use of Gabor filters. Principal Component Analysis for denoising and compression. Unsupervised classification via feature space clustering. Texture segmentation with Gabor filters.

### RMRI Research Methods and Responsible Methods (Postgraduate) 2020

This module will teach generic high-level research and transferable skills applicable to pure and applied research in computer science and engineering. The module fosters the development of practical understanding of established approaches, methods and techniques of research; conceptual understanding that enables critical and rigorous evaluation of research; ability to communicate ideas and conclusions logically and fluently in both written and oral contexts.

## Affiliations

*   [UKRI Centre for Doctoral Training in Artificial Intelligence and Music](https://aim.qmul.ac.uk/) 
*   [Centre for Digital Msusic](http://c4dm.eecs.qmul.ac.uk/)
*   [Centre for Intelligent Sensing](http://cis.eecs.qmul.ac.uk/)
*   [Steinberg](https://www.steinberg.net/en/home.html)

## Education

* 2019 - Currently Ph.D. on Optical Music Recognition - Queen Mary University of London

* 2017 - 2019 MSc in Information Systems and Applications - National Tsing Hua University

* 2013 - 2017 BSc in Telecommunications: Faculty of Electrical and Computer Engineering, University of Prishtina




<!-- ##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax. -->



## Contact
* e.shatri1@gmail.com
* e.shatri@qmul.ac.uk

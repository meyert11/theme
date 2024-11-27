---
layout: default
---

## News
* [Highlights from WoRMS-2021 3rd edition](./WoRMS2021.html)


## Published Research


*    [Knowledge Discovery in Optical Music Recognition: Enhancing Information Retrieval with Instance Segmentation, in Proceedings of the 16th International Conference on Knowledge Discovery and Information Retrieval, Best Student Paper Award, 2024.](https://arxiv.org/abs/2408.15002)
*    [Synthesising Handwritten Music with GANs: A Comprehensive Evaluation of CycleWGAN, ProGAN, and DCGAN, IEEE Big Data 2024 2nd Workshop on AI Music Generation (AIMG 2024)), 2024.](https://arxiv.org/abs/2411.16405)
*   [Low-Data Classification of Historical Music Manuscripts: A Few-Shot Learning Approach, The Sixth IEEE International Conference on Image Processing Applications and Systems, 2024](https://arxiv.org/abs/2411.16408)
*   [Crafting Handwritten Notations: Towards Sheet Music Generation, in 6th International Workshop on Reading Music Systems, 2024](https://arxiv.org/abs/2411.15741)
*   [DoReMi: First glance at a universal OMR dataset, in 3rd International Workshop on Reading Music Systems, 2021](https://sites.google.com/view/worms2021/home)
*   [CompldNet: Sheet Music Composer Identification using Deep Neural Network, in 4th International Workshop on Reading Music Systems, 2022](https://arxiv.org/pdf/2211.13285.pdf#page=10)
*   [Towards Artificially Generated Handwritten Sheet Music Datasets, in 5th International Workshop on Reading Music Systems, 2023 ](https://arxiv.org/pdf/2311.04091.pdf#page=26)
*   [Improving Sheet Music Recognition using Data Augmentation and Image Enhancement, in 5th International Workshop on Reading Music Systems, 2023](https://arxiv.org/pdf/2311.04091.pdf#page=32)
*   [Optical Music Recogntion: State of the Art and Major Challenges, in The International Conference on Technologies for Music Notation and Representation, 2020](https://www.tenor-conference.org/proceedings/2020/23_Shatri_tenor20.pdf)
*   [Foundation Models for Music: A Survey](https://arxiv.org/abs/2408.14340)

## Proceedings Editor
*   [Proceedings of the 4th International Workshop on Reading Music Systems](https://arxiv.org/abs/2211.13285)
*   [Proceedings of the 5th International Workshop on Reading Music Systems](https://arxiv.org/pdf/2311.04091)
*   [Proceedings of the 6th International Workshop on Reading Music Systems](https://arxiv.org/abs/2411.15741)

## Presentations
* [ E. Shatri, “Crafting responsive assessments of AI and tech futures (CREAATIF),” Poster presented at the Policy Forum of the Harvard Data Science Review’s Special Issue on Generative AI (GenAI), June 2024.](https://www.qmul.ac.uk/deri/news--events-/featured-event-policy-forum-of-the-harvard-data-science-review---futureshock/)
* [E. Shatri, “Navigating the intersection of AI and creativity: A case study of musicians in the age of GenAI,” Presentation at the AI & Music Lecture Symposium and Jam, Bloomsbury Festival, October 2024.](https://bloomsburyfestival.org.uk/events/ai-music-lecture-symposium/)
* [Enhancing Handwritten Music Sheet Datasets Using Generative Adversarial Networks, the 6th International Workshop on Reading Music Systems ](https://sites.google.com/view/worms2024/program)

## Podcast
* [Womanthology podcast episode 23: Women in Robotics and Artificial Intelligence](https://www.womanthology.co.uk/womanthology-podcast-episode-23-women-in-robotics-and-artificial-intelligence-with-special-guests-elona-shatri-artificial-intelligence-and-music-phd-researcher-and-ines-santos/)

## [Blogposts](./blogposts.md)

*   [Favourites at ISMIR 2021](./2021-11-16-ismir-2021.md)
*   [Highlights from WoRMS-2021 3rd edition](./WoRMS2021.html)
*   [What is Optical Music Recognition?](https://towardsdatascience.com/what-is-optical-music-recognition-6515d8a53e01)
*   [A review on Super-Resolution](https://medium.com/analytics-vidhya/a-review-on-super-resolution-2c78cd77885a)
*   [A review of Generative Adversarial Networks](https://towardsdatascience.com/a-review-of-generative-adversarial-networks-9af21e94bda4)
*   [Optical Music Recognition: State of the Art and Major Challenges](https://towardsdatascience.com/optical-music-recognition-state-of-the-art-and-major-challenges-aa100923c78d)


## Commitements
* [Member of the Editorial Team at Women in Music Information Retrieval (WiMIR)](https://wimir.wordpress.com/2023/06/19/introducing-the-wimir-editorial-team-and-issuing-a-call-for-contributions-2/)
* [General Chair at the 3rd, 4th, 5th, 6th International Workshop on Reading Music Systems](https://sites.google.com/view/worms2024/people)
* [Member of the Equality, Diversity and Inclusion initiative at EECS and Women in EECS site at QMUL](https://www.qmul.ac.uk/eecs/about-us/equality-diversity-and-inclusion/edi-committee/)
* [Student Ambassador at EECS]


## About Me 

Hello there!

I'm a PhD candidate at the UKRI Centre for Doctoral Training in Artificial Intelligence and Music (AIM). I am part of Centre for Digital Music (C4DM) research group at Queen Mary University of London. 

My research interest is mainly Optical Music Recogntion as well as other MIR related subfields. My goal is to have computers read sheet music computationally. I started working in this problem in September 2019 when I was granted the studentship from QMUL and Steinberg GmBH with which we collaborate closely. 

My work focuses on how can we bring new machine learning solutions to the field of OMR and achieve an end-to-end solution to the problem.


Optical Music Recognition (OMR) is concerned with digitizing music sheets into a machine-readable format. Being able to compose, transcribe and edit music by means of taking a picture of a music sheet, would put musician's workload at ease. Such automation would allow musicians to use search-ability and to perform quantitative measures in the musical pieces. This problem comes down to a simple, how can computers be made to read music. The output to this process being a machine-readable file such as MIDI, MusicXML, MEI files. The objective is outputting semantic mark-up identifying as many notational elements as possible, along with the relationship to their position in the original image.


Prior solutions have used algorithmic approaches and have involved layers of algorithmic rules applied to traditional feature detection techniques such as edge detection. One of the approaches we want to further investigate is using deep neural networks to solve the problem. Before going into this step another very important processing should be performed, that is, tackling the quality of the input picture of the music sheet. Image preprocessing steps are to be taken which will later help in the training step.

 

An OMR pipeline should be able to capture the right position and the relationships between two notes and its distinctive features. Pacha et al. (2018) proposed an end-to-end trainable object detector that can detect almost the full vocabulary of modern music notation in handwritten scores. Using deep convolutional networks in a dataset with symbol-level notations they achieve a mean average precision up to 80 %.

The OMR pipeline has four main blocks, and we want to tackle them one by one, using a deep learning technique and compare to the already existing techniques. If the DL techniques show improvements, then an end-to-end network is the final goal of our work. Since the existing datasets do not offer enough classes and data, the first step for use would be data augmentation. This will be done using the digitized musical sheets from music notation software Dorico, having this way a ground truth. These sheets will be subject to image degradation techniques, using the degraded images as inputs in our pipeline. The next step would be designing the methodology for object recognition and reconstruction using the deep neural network approach.


## [DoReMi Dataset](./doremi-dataset.html)
We recently published our DoReMi dataset at the [3rd International Workshop on Reading Music Systems 2021](https://sites.google.com/view/worms2021/home). We made our dataset available in [this page](https://github.com/steinbergmedia/DoReMi/releases/tag/v1.0) open for anyone to use it, experiment with it and maybe suggesting new ways to represent these data.  

Documentation is also availabe in the same repository of the data release. 




## Teaching




* [School Page](http://eecs.qmul.ac.uk/profiles/shatrielona-1.html)
* [Medium](https://medium.com/@e.shatri1)


## Affiliations

*   [UKRI Centre for Doctoral Training in Artificial Intelligence and Music](https://aim.qmul.ac.uk/) 
*   [Centre for Digital Music](http://c4dm.eecs.qmul.ac.uk/)
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

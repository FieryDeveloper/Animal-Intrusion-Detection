# Animal-Intrusion-Detection
We address the alarming rise of animal-inflicted harm in residential areas, proposing an image classification-based identification system for enhanced safety.  The research highlights the urgent need for improved safety measures, especially in residential lifts, to protect children and the elderly from stray animal attacks.

 <div align="center">
  <img src="cctvsvg.svg" width="300" alt="CCTV SVG" />
</div>



#  Representation of Display Panel using HCI Principle.

<div align="center">
  <img src="Next Step Estimated Time Total Steps (1).png" width="400" height="400">
</div>


## Table of contents

- [Overview](#Overview)
- [Contributions](#Contributions)
- [Literature Review](#literaturereview)
- [Methodology](#methodology)
  -[CNN](#cnn)
  -[ResNet](#resnet) 
  -[EfficientNet](#efficientnet) 

- [Connect with me!](#connectwithme)


## Overview
Recently, a new alarming problem has emerged, particularly in residential areas,where dogs and other animals have inflicted substantial harm on children, the elderly, and others arising from stray animals. The severity of such incidents has escalated, leading to serious injuries and even fatalities. In India, these incidents have occurred within the confined environment of residential lifts. In order to address this pressing issue, this paper proposes an innovative solution: implementing an image classification-based identification system. In this study, ten distinct animal classes are classified using the Animals-10 dataset. In order to implement this idea, Convolutional Neural Networks (CNN) and pre-trained architectures like ResNet50 and EfficientNetB7 have been used. Improved results were achieved by fine-tuning these models. The metric used for evaluation was accuracy, ensuring the highest level of improvement. This work achieved an accuracy of 81.65% using CNN and an accuracy of 93.53% using ResNet50. However, we achieved the best results using the EfficientNetB7 model and by fine-tuning it further. The maximum test accuracy obtained is 98.52%. To demonstrate the effectiveness of the work, a comparative study with the previous work is included.

## Contributions 

1. The team has proposed a customised CNN model and a transfer-learning
approach like ResNet50 and EfficientNetB7 for classifying images of animals in
surroundings such as elevators, parks and other residential areas.
2. The transfer learning models have been trained and tested on animal (fauna)
images. The images are obtained from Google Photos and have been published in
a publically available dataset Animals-10. The dataset contains 28000 images of
animals divided into 10 classes. Furthermore, augmentation of images is performed
for higher impact.
3. This work has performed adjustments of various hyperparameters to obtain the
best performance possible.
4. The underlying idea of this work is to design an approach to ensure the co-existence
of animals (pets) and humans in a confined residential area. A comparative study
comprising the latest previous works has been conducted to show the effectiveness
of the work.

### Literature Review

<div align="center">
  <img src="https://github.com/FieryDeveloper/Animal-Intrusion-Detection/blob/main/LiteratureReview.png" width="400" alt="Literaturereview" />
</div>

### Methodology
<div align="center">
  <img src="https://github.com/FieryDeveloper/Animal-Intrusion-Detection/blob/main/methodology.png" width="400" alt="Literaturereview" />
</div>

#### CNN

Convolutional neural networks (CNNs) are commonly employed in solving deep
learning problems like object detection, image classification, and text recognition, as
well as other computer vision-related tasks. For image classification, CNNs have been
utilized for several years. They use a system composed of a multi-layer perceptron that
reduces processing requirements. The input layer allows for the use of various images
as input. The convolutional layer is the core of CNN’s architecture, which extracts and
differentiates various features from the input image using parameters such as filters,
kernel size, padding, strides, and more.

<div align="center">
  <img src="https://github.com/FieryDeveloper/Animal-Intrusion-Detection/blob/main/methodology.png" width="400" alt="Literaturereview" />
</div>


#### ResNet

By introducing skip connections, ResNet enables the gradient to flow more easily
through the network during backpropagation. This facilitates the training of very deep
networks with hundreds or even thousands of layers. Additionally, the skip connections
enable the network to learn the identity mapping if it is optimal, which can be useful
for preserving low-level features in the input.
The ResNet architecture has shown remarkable success in various computer vision
tasks, such as image classification, object detection, and semantic segmentation. It
has become a foundational building block for many state-of-the-art deep learning
models in computer vision.

<div align="center">
  <img src="https://github.com/FieryDeveloper/Animal-Intrusion-Detection/blob/main/methodology.png" width="400" alt="Literaturereview" />
</div>



#### EfficientNet

The EfficientNet scaling method uniformly adjusts network width, depth,
and resolution with a set of parameters, in contrast to standard practice, which
scales these components arbitrarily [42]. The compound coefficient ”phi” is utilised
by EfficientNet to uni-systematically scale network depth, resolution, and width. The
rationale behind the scaling approach is that if the input image is larger, then for the
network to have a larger receptive field and more channels for capture, more layers
are required. In the bigger image, there are more granular patterns.
EfficientNetB7 stands out for its versatility; in addition to being outstanding in image
classification, it also has the capacity to detect objects, segment data semantically,
and identify faces. This adaptability, together with shorter training times than with
larger structures, improves the effectiveness of research and development. Furthermore, it supports hardware acceleration devices like GPUs and TPUs, guaranteeing rapid inference without compromising accuracy.

<div align="center">
  <img src="https://github.com/FieryDeveloper/Animal-Intrusion-Detection/blob/main/methodology.png" width="400" alt="Literaturereview" />
</div>


### Connect with me!

- ⭐️ Star [`FieryDeveloper` on GitHub]([https://github.com/themerdev/themer](https://github.com/FieryDeveloper))
- 📧 [Mail me:amoghag2003@gmail.com]


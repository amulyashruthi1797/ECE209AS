# ECE209AS
This repo contains project details for ECE 209AS Lip Reading Project. This project is done under Prof. Mani Srivastava during the Spring Quarter in UCLA (academic year: 2021 - 2022).

# Team Members
1. Shweta Katti (UID: 505604846)
2. Amulya Shruthi Tammireddi (UID: 505626283) - ashruthi1797@g.ucla.edu

# Project Description 
The project focuses on lip reading and maximizing efficiency of detection on existing video datasets. The problem statement can be found on 

# Code Base
All code changes can be found along the path https://github.com/amulyashruthi1797/ECE209AS/

# Literature Survey and Previous Work 
Out of the 25 papers studied, we will first start off with the implementation of these methodologies to begin with the comparitive analysis for the best architecture
| Paper citation                                     | Architecture                 | Dataset  | Preprocessing | Pre-trained weights | Word Error Rate|
| -------------------------------------------------- | -----------------------------|----------|---------------|---------------------|----------------|
|Assael, Yannis M., et al. "Lipnet: End-to-end sentence-level lipreading." arXiv preprint arXiv:1611.01599 (2016).|LipNet - CNN+BiGRU+CTC loss | GRID Corpus |D-lib for face detection, data augmentation | Weights available online | 26.3% |
|B. Martinez, P. Ma, S. Petridis and M. Pantic, "Lipreading Using Temporal Convolutional Networks," ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2020, pp. 6319-6323, doi: 10.1109/ICASSP40776.2020.9053841| The network consists of a 3D convolution layer, followed by a 18-layer ResNet and a Temporal Convolution Network | LRW BBC dataset | SSD face detection, pre-training and data augmentation | Weights available online | 12% |
|G. Potamianos, C. Neti, G. Gravier, A. Garg and A. W. Senior, "Recent advances in the automatic recognition of audiovisual speech," in Proceedings of the IEEE, vol. 91, no. 9, pp. 1306-1326, Sept. 2003, doi: 10.1109/JPROC.2003.817150. | MLLR, MAP, HMMs |
|Almajai, I., Cox, S., Harvey, R. and Lan, Y., 2016, March. Improved speaker independent lip reading using speaker adaptive training and deep neural networks. In 2016 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP) (pp. 2722-2726). IEEE. | Error rates reduced by using Context - Dependent DNN architectures |
|Chung, Joon Son, et al. "Lip reading sentences in the wild." 2017 IEEE conference on computer vision and pattern recognition (CVPR). IEEE, 2017.|‘Watch, Listen, Attend and Spell’ (WLAS) network:The convolutional network is based on the VGG-M model, followed by LSTM encoder and transducer.| 


# Work Done
1. Literature survey was completed for around 25 papers. Primary architectures that can be chosen for the detection were shortlisted. Also publicly available datasets 
 for the same were chosen.
2.

# Upcoming Targets
1.

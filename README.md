# ECE209AS
This repo contains project details for ECE 209AS Lip Reading Project. This project is done under Prof. Mani Srivastava during the Spring Quarter in UCLA (academic year: 2021 - 2022).

# Team Members
1. Shweta Katti (UID: 505604846)
2. Amulya Shruthi Tammireddi (UID: 505626283) - ashruthi1797@g.ucla.edu


# Project Description 
The project focuses on lip reading and maximizing efficiency of detection on existing video datasets. The problem statement can be found on 


# Code Base
All code changes can be found along the path https://github.com/amulyashruthi1797/ECE209AS/


# Work Done
1. Our aim was to test several popular models and architectures available for lip reading and conduct a survey to analyze their performance on a given test dataset.
2. We selected a combination of popular and relatively new architectures based on our literature survey and obtained their pre-trained weights for evaluation.
3. Utilized various metrics to understand which of the implemented models perform the best given a particular dataset.


# Literature Survey and Previous Work 
Out of the 25 papers studied, we will first start off with the implementation of these methodologies to begin with the comparitive analysis for the best architecture
| Paper citation                | Architecture         | Dataset  | Preprocessing | Pre-trained weights | Word Error Rate|
| -------------------------------------------------- | -----------------------------|----------|---------------|---------------------|----------------|
|Assael, Yannis M., et al. "Lipnet: End-to-end sentence-level lipreading." arXiv preprint arXiv:1611.01599 (2016).|LipNet - CNN+BiGRU+CTC loss | GRID Corpus |D-lib for face detection, data augmentation | Weights available online | 26.3% |
|B. Martinez, P. Ma, S. Petridis and M. Pantic, "Lipreading Using Temporal Convolutional Networks," ICASSP 2020 - 2020 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2020, pp. 6319-6323, doi: 10.1109/ICASSP40776.2020.9053841| The network consists of a 3D convolution layer, followed by a 18-layer ResNet and a Temporal Convolution Network | LRW BBC dataset | SSD face detection, pre-training and data augmentation | Weights available online | 12% |
|Stafylakis, Themos & Tzimiropoulos, Georgios. (2017). Combining Residual Networks with LSTMs for Lipreading| Spatiotemporal convolution + ResNet + Bidirectional LSTM + Softmax layer| LRW BBC dataset| Detections of landmarks + cropping of ROI + conversion to grayscale| Trained on the lab GPU| 24.3%|
| Afouras, Triantafyllos & Chung, Joon Son & Senior, Andrew & Vinyals, Oriol & Zisserman, Andrew. (2018). Deep Audio-visual Speech Recognition. IEEE Transactions on Pattern Analysis and Machine Intelligence. PP. 1-1. 10.1109/TPAMI.2018.2889052. | TM - CTC model - Self-attention-based encoder architecture| LRS2-BBC | SSD face detection, pre-training and data augmentation |Pre-trained weights available online| 57.2% |
|Chung, Joon Son, et al. "Lip reading sentences in the wild." 2017 IEEE conference on computer vision and pattern recognition (CVPR). IEEE, 2017.|‘Watch, Listen, Attend and Spell’ (WLAS) network:The convolutional network is based on the VGG-M model, followed by LSTM encoder and transducer.| 


# Future Work
1. We can incorporate more personalized videos into the dataset for testing the models.
2. We can check how the models performance varies when multiple datasets are combined and used for training.
3. We can incorporate other evaluation metrics such as CER or SER.


# IGDA: Intention-Guided Driver Attention Selection in Traffic Scenes
The paper presents a new work on an unresolved problem in the field of autonomous driving, namely intention-driven visual attention selection in actively perceived environments.The core problem that needs to be solved to realize active perception is the problem of intention-driven visual attention selection on the one hand, and the accuracy of visual attention localization and the completeness of the attention area on the other. Based on the above problems, this paper proposes a novel intentiondriven visual attention selection model (IDVA). First, based on Score-CAM, this paper proposes a fast integrate multi-feature of local space (FIMF Score-CAM) method for attention map generation. The method achieves weighted fusion of feature maps based on their contribution to specific object recognition, generates an attention map related to the observed object, and combines spatial attention with feature attention to improve visual attention localization. Second, we propose a guided erasure learning strategy that forces the network to pay more comprehensive attention to the target-related region, overcoming the shortcoming of the original learning strategy that only focuses on the most discriminative feature region, thus enabling visual attention to better cover the entire target region. Finally, we collected actual human eye movement data to construct a largescale intention-related driving attention dataset called IRDA.


# Method：
Schematic diagram of the principles of the visual attention selection model. The red lines and text represent important object categories that need to be observed in a given situation. Important object categories to be observed in a given situation.
![f9e3522f991c84089cb088668ceeff3](https://github.com/JulyAndGanyu/IGDA/assets/110894437/552e0b74-c9e8-4ad3-8086-abcccab866dc)




# Dataset:
Quantitative Comparison of Multiple Data Visual Attention Datasets.
![5760b52c7602cdac397a5bb3b6681cf](https://github.com/JulyAndGanyu/IGDA/assets/110894437/52043612-d69c-43f5-b064-20f0120d6408)



# Results：
Attention map driven by different driving intentions. According to the statistical data, we generate the attention map of the most important 1-3 categories of targets in the intersection and straight-line scenarios based on different driving intentions.
![微信图片_20240103201140](https://github.com/JulyAndGanyu/IDVA/assets/110894437/7978b8be-f510-46d4-afaf-2bcfa10858a3)








# Evaluation metrics
In this paper, the following evaluation metrics are used to assess the performance of their proposed model for driving visual attention prediction:
1. KL dispersion (KLdiv): measures the difference between predicted attention and true attention.
2. Pearson's correlation coefficient (CC): measures the strength and direction of the linear relationship between predicted and true attention.
3. Similarity (SIM): assessed the degree of similarity between the predicted and real concern maps.

# Benchmark download
Our IDVA dataset can be downloaded from (https://drive.google.com/drive/folders/1xEn0J-CcOf54_cOcPPmoADr88cuDgEGd?usp=sharing)

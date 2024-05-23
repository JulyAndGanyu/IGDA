# IGDA: Intention-Guided Driver Attention Selection in Traffic Scenes
Active perception is an important way to achieve accurate and efficient understanding of the environment and is an unsolved problem in the field of autonomous driving. The core problem that needs to be solved to realize active perception is the problem of intention-guided driver attention selection on the one hand, and the accuracy of driver attention localization and the completeness of the attention area on the other. Based on the above problems, this paper proposes a novel intention-guided driver attention selection model (IGDA). First, based on Score-CAM, a fast integrate multi-feature of local space (FIMF Score-CAM) method is proposed for intention-guided driver attention map generation. Second, we propose a guided erasing learning strategy that forces the network to pay more comprehensive attention to the overall target-related region. Finally, an intention-related driving attention dataset (IRDA) is collected, which is more able to test the predictive performance of the model for intention-driven driver attention selection in driving scenarios. Experiments on several public datasets and IRDA show that the proposed model can switch the object of attention at any time during driving in response to changes in observational intention. At the same time, the model also exhibits excellent driver attention localization accuracy and attentional region completeness.


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

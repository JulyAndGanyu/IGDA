# IDVA: Intention-Driven Visual Attention Selection for Traffic Scene Active Perception
The paper presents a new work on an unresolved problem in the field of autonomous driving, namely intention-driven visual attention selection in actively perceived environments.The core problem that needs to be solved to realize active perception is the problem of intention-driven visual attention selection on the one hand, and the accuracy of visual attention localization and the completeness of the attention area on the other. Based on the above problems, this paper proposes a novel intentiondriven visual attention selection model (IDVA). First, based on Score-CAM, this paper proposes a fast integrate multi-feature of local space (FIMF Score-CAM) method for attention map generation. The method achieves weighted fusion of feature maps based on their contribution to specific object recognition, generates an attention map related to the observed object, and combines spatial attention with feature attention to improve visual attention localization. Second, we propose a guided erasure learning strategy that forces the network to pay more comprehensive attention to the target-related region, overcoming the shortcoming of the original learning strategy that only focuses on the most discriminative feature region, thus enabling visual attention to better cover the entire target region. Finally, we collected actual human eye movement data to construct a largescale intention-related driving attention dataset called IRDA.

# Detail
Attention intention object heatmap generation by IDVA.

![image](https://github.com/JulyAndGanyu/IDVA/assets/110894437/7c8c3774-b7b5-48e7-9545-70308e39d156)


Flow chart of FIMF Score-CAM.

![image](https://github.com/JulyAndGanyu/IDVA/assets/110894437/7f465140-993c-4248-899c-a00285a9b279)


Results.

![1212](https://github.com/JulyAndGanyu/IDVA/assets/110894437/02685c4f-657f-46cd-a447-92a96d457c23)


# Evaluation metrics
In this paper, the following evaluation metrics are used to assess the performance of their proposed model for driving visual attention prediction:
1. KL dispersion (KLdiv): measures the difference between predicted attention and true attention.
2. Pearson's correlation coefficient (CC): measures the strength and direction of the linear relationship between predicted and true attention.
3. Similarity (SIM): assessed the degree of similarity between the predicted and real concern maps.
4. Normalized Scan Path Significance (NSS): measured the significance of the true concerns in the predicted concern graph.
5. AUC-Borji: measured the consistency between the predicted attention graph and the true attention graph based on the area under the ROC curve.
6. AUC-Judd: based on the area under the ROC curve, measured the consistency of the predicted attention graph with the average attention graph.

# Benchmark download
Our IDVA dataset can be downloaded from (https://drive.google.com/drive/folders/1xEn0J-CcOf54_cOcPPmoADr88cuDgEGd?usp=sharing)

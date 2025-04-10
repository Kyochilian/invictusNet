# invictusNet:the UNet-like Semantic Segmentation Network with ViT Backup

*Haobin XU,Zhendong Li*
![image.png](attachment:204c55fd-120d-4e83-946a-1869065c642f:image.png)
### Abstract

> In the field of medical image segmentation, there have been many U-Net-type architectures based on convolutional neural networks (CNNs) with transformers that have achieved significant success in segmentation tasks. However, the inadequacy of CNNs in capturing global features and the high computational effort of transformers lead to limitations in the segmentation task, especially in the case of medical platforms with limited resources and deployed in edge devices, many excellent neural networks cannot perform as well as they should. To address this problem, this paper proposes a lightweight segmentation network architecture that deeply integrates ViT, significantly reduces the computational complexity, and integrates multiple attention mechanisms such as multi-head attention mechanism (MHA), channel attention (CA), etc., to ensure that it achieves a balance between parameters and accuracy on resource-limited medical devices and mobile platforms. Experimental results show that the network achieves an accuracy of 82.01% on the Synapse dataset, effectively validating the effectiveness and feasibility of the method. The code is open source on invictusNet.


### Data pre

Synapse dataset is used in our paper. [Download](https://paperswithcode.com/sota/medical-image-segmentation-on-synapse-multi)

![image.png](attachment:a7866259-38f7-4afe-a659-07d5363dcbdd:image.png)

### Thanks for the code provided by:

**EfficientFormerV2** https://github.com/snap-research/EfficientFormer/blob/main/README.md

**Swin-Unet** https://github.com/HuCaoFighting/Swin-Unet

**SelfReg-UNet** https://github.com/ChongQingNoSubway/SelfReg-UNet

**UCTransNet** https://github.com/McGregorWwww/UCTransNet/blob/main/nets/UCTransNet.py

**EViT-UNet**  https://github.com/Retinal-Research/EVIT-UNET

### Thanks for the datasets open-sourced by:

https://paperswithcode.com/sota/medical-image-segmentation-on-synapse

https://arxiv.org/abs/2306.07863

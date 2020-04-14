# face-hallucination

人脸幻视，也就是实现对低质模糊图像的重构。paper and code.

## Paper and Code
### 1. Deep cascaded bi-network for face hallucination
note: utilizes the facial prior by alternately optimizing FH and dense correspondence field estimation <br>
code: https://github.com/zhusz/ECCV16-CBN [matlab]

### 2. Super-fan: Integrated facial landmark localization and super-resolution of real-world low resolution faces in arbitrary poses with gans
note: guarantee the consistency of facial landmarks by end-to-end multi-task learning <br> 
code: https://github.com/jzijin/Super-FAN

### 3. Fsrnet: End-to-end learning face super-resolution with facial priors
note: uses not only facial landmark heatmaps but also face parsing maps as prior constraints. <br>
code: https://github.com/cs-giung/FSRNet-pytorch

### 4. Super-identity convolutional neural network for face hallucination
note: recovering the real iden- tity, adopts a super-identity loss function and a domain- integrated training approach to stable the joint training <br>
code: https://github.com/SirLPS/Face-Hallucination

### 5 Hallucinating compressed face images
note: decompose deblocked face images into facial components and background, use the component landmarks to retrieve adequate HR exemplars in external datasets, perform generic SR on the background, and finally fuse them to complete HR faces. <br>
code: https://github.com/yangchihyuan/HallucinatingCompressedFaceImages [matlab]

### 6. Attribute augmented convolutional neural network for face hallucination
note: utilize additional facial attribute information to perform FH with the specified attributes, based on the conditional GAN <br>
code: https://github.com/steven413d/AACNN [tensorflow]




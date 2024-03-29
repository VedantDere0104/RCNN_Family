# Rich feature hierarchies for accurate object detection and semantic segmentation :- 

Pytorch implementation of RCNN .


## Abstract :- 
Object detection performance, as measured on the
canonical PASCAL VOC dataset, has plateaued in the last
few years. The best-performing methods are complex ensemble systems that typically combine multiple low-level
image features with high-level context. In this paper, we
propose a simple and scalable detection algorithm that improves mean average precision (mAP) by more than 30%
relative to the previous best result on VOC 2012—achieving
a mAP of 53.3%. Our approach combines two key insights:
(1) one can apply high-capacity convolutional neural networks (CNNs) to bottom-up region proposals in order to
localize and segment objects and (2) when labeled training
data is scarce, supervised pre-training for an auxiliary task,
followed by domain-specific fine-tuning, yields a significant
performance boost. Since we combine region proposals
with CNNs, we call our method R-CNN: Regions with CNN
features. We also compare R-CNN to OverFeat, a recently
proposed sliding-window detector based on a similar CNN
architecture. We find that R-CNN outperforms OverFeat
by a large margin on the 200-class ILSVRC2013 detection
dataset.

## Model Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134125956-1765eefb-c6c1-436a-89a9-5972d3847805.png)

```
@misc{girshick2014rich,
      title={Rich feature hierarchies for accurate object detection and semantic segmentation}, 
      author={Ross Girshick and Jeff Donahue and Trevor Darrell and Jitendra Malik},
      year={2014},
      eprint={1311.2524},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

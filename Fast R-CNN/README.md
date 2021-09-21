# Fast R-CNN

Pytorch implementation of Fast R-CNN .

## Abstract :- 
This paper proposes a Fast Region-based Convolutional
Network method (Fast R-CNN) for object detection. Fast
R-CNN builds on previous work to efficiently classify object proposals using deep convolutional networks. Compared to previous work, Fast R-CNN employs several innovations to improve training and testing speed while also
increasing detection accuracy. Fast R-CNN trains the very
deep VGG16 network 9× faster than R-CNN, is 213× faster
at test-time, and achieves a higher mAP on PASCAL VOC
2012. Compared to SPPnet, Fast R-CNN trains VGG16 3×
faster, tests 10× faster, and is more accurate.

## Architecture :- 
![image](https://user-images.githubusercontent.com/76057253/134172183-d6b81bc5-e6e1-420c-9cbf-bed5c9f0d8f9.png)

![image](https://user-images.githubusercontent.com/76057253/134127469-819e1076-667e-42ed-ba1a-bbd2d08cccab.png)


# Results :- 
![image](https://user-images.githubusercontent.com/76057253/134127573-a613a259-c8a9-4829-a373-fc1b2782e41d.png)


```
@misc{girshick2015fast,
      title={Fast R-CNN}, 
      author={Ross Girshick},
      year={2015},
      eprint={1504.08083},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

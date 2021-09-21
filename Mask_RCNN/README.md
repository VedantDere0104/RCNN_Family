# Mask R-CNN


Pytorch implementation of Mask R-CNN.

## Abstract :- 
We present a conceptually simple, flexible, and general
framework for object instance segmentation. Our approach
efficiently detects objects in an image while simultaneously
generating a high-quality segmentation mask for each instance. The method, called Mask R-CNN, extends Faster
R-CNN by adding a branch for predicting an object mask in
parallel with the existing branch for bounding box recognition. Mask R-CNN is simple to train and adds only a small
overhead to Faster R-CNN, running at 5 fps. Moreover,
Mask R-CNN is easy to generalize to other tasks, e.g., allowing us to estimate human poses in the same framework.
We show top results in all three tracks of the COCO suite
of challenges, including instance segmentation, boundingbox object detection, and person keypoint detection. Without bells and whistles, Mask R-CNN outperforms all existing, single-model entries on every task, including the
COCO 2016 challenge winners. We hope our simple and
effective approach will serve as a solid baseline and help
ease future research in instance-level recognition.

## Architecture :- 

![image](https://user-images.githubusercontent.com/76057253/134179736-14193c10-de92-44fe-86bf-d3ca05f419ac.png)

```
@misc{he2018mask,
      title={Mask R-CNN}, 
      author={Kaiming He and Georgia Gkioxari and Piotr Dollár and Ross Girshick},
      year={2018},
      eprint={1703.06870},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```

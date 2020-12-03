# CompFeat: Comprehensive Feature Aggregation for Video Instance Segmentation
# CompFeat: Comprehensive Feature Aggregation for Video Instance Segmentation

This is the repo to host the dataset TextSeg and code for ComFeat from the following paper:

**CompFeat: Comprehensive Feature Aggregation for Video Instance Segmentation**, [ArXiv Link]() 

Yang Fu, Linjie Yang, Ding Liu, Thomas S. Huang and Humphrey Shi.

**Note:**
Our code will be released here, stay tuned.

## Introduction
Video instance segmentation is a complex task in which we need to detect, segment, and track each object for any given video. Previous approaches only utilize single-frame features for the detection, segmentation, and tracking of objects and they suffer in the video scenario due to several distinct challenges such as motion blur and drastic appearance change. 
To eliminate ambiguities introduced by only using single-frame features, we propose a novel comprehensive feature aggregation approach (**ComFeat**) to refine features at both frame-level and object-level with temporal and spatial context information. 
The aggregation process is carefully designed with a new attention mechanism which significantly increases the discriminative power of the learned features.
We further improve the tracking capability of our model through a siamese design by incorporating both feature similarities and spatial similarities.
Our proposed CompFeat achieves the state-of-the-art results on the challenging YouTube-VIS dataset.

## Framework
![Illustration of the Self-similarity Grouping.](./figs/framework.png)

## Bibtex
```
@article{fu2021compfeat,
  title={CompFeat: Comprehensive Feature Aggregation for Video Instance Segmentation},
  author={Yang Fu, Linjie Yang, Ding Liu, Thomas S. Huang and Humphrey Shi},
  journal={AAAI},
  year={2021}
}
```
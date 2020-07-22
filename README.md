[<img height="23" src="https://github.com/lh9171338/Outline/blob/master/icon.jpg"/>](https://github.com/lh9171338/Outline) Monocular-Depth-Estimation-Papers
===

A collection of monocular depth estimation papers.

# Outline

- [Methods](#1-Methods)
  - [Supervised](#11-Supervised)
  - [Unsupervised](#12-Unsupervised)
  - [Video based](#13-Video-based)  
- [Datasets](#2-Datasets)
- [SOTA](#3-SOTA)

# 1. Methods

## 1.1 Supervised

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
|  | [High Quality Monocular Depth Estimation via Transfer Learning](https://arxiv.org/abs/1812.11941) | arXiv 2018 | [[Code]](https://github.com/ialhashim/DenseDepth) |
| SVS | [Single View Stereo Matching](https://arxiv.org/abs/1803.02612) | CVPR 2018 | [[Code]](https://github.com/lawy623/SVS) |
| DORN | [Deep Ordinal Regression Network for Monocular Depth Estimation](https://arxiv.org/abs/1806.02446) | CVPR 2018 | [[Caffe]](https://github.com/hufu6371/DORN) [[PyTorch]](https://github.com/dontLoveBugs/DORN_pytorch) |
| GeoNet | [GeoNet: Unsupervised Learning of Dense Depth, Optical Flow and Camera Pose](https://arxiv.org/abs/1803.02276) | CVPR 2018 | [[Code]](https://github.com/yzcjtr/GeoNet) |
| CCRF-CNN | [Multi-Scale Continuous CRFs as Sequential Deep Networks for Monocular Depth Estimation](https://arxiv.org/abs/1704.02157) | CVPR 2017 | [[Code]](https://github.com/danxuhk/ContinuousCRF-CNN) |
| CNN-SLAM | [CNN-SLAM: Real-time dense monocular SLAM with learned depth prediction](https://arxiv.org/abs/1704.03489) | CVPR 2017 | [[Code]](https://github.com/iitmcvg/CNN_SLAM)  |
|  | [A Two-Streamed Network for Estimating Fine-Scaled Depth Maps from Single RGB Images](https://arxiv.org/abs/1607.00730) | ICCV 2017 |   |
|  | [Joint Semantic Segmentation and Depth Estimation with Deep Convolutional Networks](https://arxiv.org/abs/1604.07480) | 3DV 2016 |   |
| FCRN | [Deeper Depth Prediction with Fully Convolutional Residual Networks](https://arxiv.org/abs/1606.00373) | 3DV 2016 | [[Code]](https://github.com/iro-cp/FCRN-DepthPrediction) |
| Deep3D | [Deep3D: Fully Automatic 2D-to-3D Video Conversion with Deep Convolutional Neural Networks](https://arxiv.org/abs/1604.03650) | ECCV 2016 | [[Code]](https://github.com/piiswrong/deep3d) |
|  | [Predicting depth, surface normals and semantic labels with a common multi-scale convolutional architecture](https://arxiv.org/abs/1411.4734) | ICCV 2015 | [[Project]](https://cs.nyu.edu/~deigen/dnl/) |
|  | [Depth Map Prediction from a Single Image using a Multi-Scale Deep Network](https://papers.nips.cc/paper/5539-depth-map-prediction-from-a-single-image-using-a-multi-scale-deep-network.pdf) | NIPS 2014 | [[Code]](https://github.com/hjimce/Depth-Map-Prediction) |
 
## 1.2 Unsupervised

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
| Monodepth2  | [Digging into Self-Supervised Monocular Depth Prediction](https://arxiv.org/abs/1806.01260) | ICCV 2019 | [[Code]](https://github.com/nianticlabs/monodepth2) |
|  | [Learning Monocular Depth by Distilling Cross-domain Stereo Networks](https://arxiv.org/abs/1808.06586) | ECCV 2018 | [[Code]](https://github.com/xy-guo/Learning-Monocular-Depth-by-Stereo) |
| SemoDepth | [Semi-Supervised Deep Learning for Monocular Depth Map Prediction](https://arxiv.org/abs/1702.02706) | CVPR 2017 | [[Code]](https://github.com/apllolulu/SemoDepth)  |
| Monodepth | [Unsupervised Monocular Depth Estimation with Left-Right Consistency](https://arxiv.org/abs/1609.03677) | CVPR 2017 | [[Project]](http://visual.cs.ucl.ac.uk/pubs/monoDepth/) [[Code]](https://github.com/mrharicot/monodepth) |
|  | [Unsupervised CNN for Single View Depth Estimation: Geometry to the Rescue](https://arxiv.org/abs/1603.04992) | ECCV 2016 | [[Code]](https://github.com/Ravi-Garg/Unsupervised_Depth_Estimation) |

## 1.3 Video based

| Name | Paper | Source | Code/Project |
| --- | --- | --- | --- |
| Struct2depth | [Depth Prediction Without the Sensors: Leveraging Structure for Unsupervised Learning from Monocular Videos](https://arxiv.org/abs/1811.06152) | AAAI 2019 | [[Project]](https://sites.google.com/view/struct2depth) [[Code]](https://github.com/tensorflow/models/tree/master/research/struct2depth) |
| Vid2depth | [Unsupervised Learning of Depth and Ego-Motion from Monocular Video Using 3D Geometric Constraints](https://arxiv.org/abs/1802.05522) | CVPR 2018 | [[Project]](https://sites.google.com/view/vid2depth) [[Code]](https://github.com/tensorflow/models/tree/master/research/vid2depth) |
| Depth-VO-Feat | [Unsupervised Learning of Monocular Depth Estimation and Visual Odometry with Deep Feature Reconstruction](https://arxiv.org/abs/1803.03893) | CVPR 2018 | [[Code]](https://github.com/Huangying-Zhan/Depth-VO-Feat) |
| SfMLearner | [Unsupervised Learning of Depth and Ego-Motion from Video](http://arxiv.org/abs/1704.07813) | CVPR 2017 | [[Code]](https://github.com/tinghuiz/SfMLearner) |

---

# 2. Datasets

- [KITTI](http://www.cvlibs.net/datasets/kitti/raw_data.php)
- [MVSEC Dataset](https://daniilidis-group.github.io/mvsec/)
- [CMU Visual Localization Dataset](http://3dvis.ri.cmu.edu/data-sets/localization/)
- [TUM RGB-D Dataset](https://vision.in.tum.de/data/datasets/rgbd-dataset)
- [Cityscapes](https://www.cityscapes-dataset.com/)
- [NYU Depth V2](https://cs.nyu.edu/~silberman/datasets/nyu_depth_v2.html)
- [ScanNet](http://www.scan-net.org/#code-and-data)
- [Make3D](http://make3d.cs.cornell.edu/data.html)
 
# 3. SOTA
- [Papers with code](https://paperswithcode.com/task/monocular-depth-estimation)
- [KITTI benchmark](http://www.cvlibs.net/datasets/kitti/eval_depth.php?benchmark=depth_prediction)


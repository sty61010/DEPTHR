# CrossDTR: Cross-view and Depth-guided Transformers for 3D Object Detection 
[![arXiv](https://img.shields.io/badge/arXiv-Paper-<COLOR>.svg)](https://arxiv.org/abs/2209.13507)
[![project](https://img.shields.io/badge/project-Page-yellow.svg)](https://sty61010.github.io/CrossDTR/)
![visitors](https://visitor-badge.glitch.me/badge?page_id=sty61010/CrossDTR)
![stars](https://img.shields.io/github/stars/sty61010/CrossDTR?color=purple)
![last commit](https://img.shields.io/github/last-commit/sty61010/CrossDTR?color=red)
<!-- ![stars](https://img.shields.io/github/stars/sty61010/CrossDTR?style=social) -->

## Demo Video
<!-- {%youtube _5kscaGVDu0 %} -->
<!-- [![Watch the video](https://img.youtube.com/vi/_5kscaGVDu0/default.jpg)](https://youtu.be/_5kscaGVDu0) -->

<!-- <iframe width="560" height="315" src="https://www.youtube.com/embed/_5kscaGVDu0" title="CrossDTR: Cross-view and Depth-guided Transformers for 3D Object Detection" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe> -->
<!-- [Direct Link to video](https://youtu.be/_5kscaGVDu0) -->

[<img src="https://i.ytimg.com/vi/RZFhqkC_xoA/maxresdefault.jpg" width="100%">](https://www.youtube.com/watch?v=RZFhqkC_xoA "Now in Android: 55")

## News
- [2022/10/11] CrossDTR is updated the second version on arxiv.
- [2022/09/28] CrossDTR is released on arxiv.

## Abstract
To achieve accurate 3D object detection at a low cost for autonomous driving, many multi-camera methods have been proposed and solved the occlusion problem of monocular approaches. However, due to the lack of accurate estimated depth, existing multi-camera methods often generate multiple bounding boxes along a ray of depth direction for difficult small objects such as pedestrians, resulting in an extremely low recall. Furthermore, directly applying depth prediction modules to existing multi-camera methods, generally composed of large network architectures, cannot meet the real-time requirements of self-driving applications. To address these issues, we propose Cross-view and Depth-guided Transformers for 3D Object Detection, CrossDTR. First, our lightweight depth predictor is designed to produce precise object-wise sparse depth maps and low-dimensional depth embeddings without extra depth datasets during supervision. Second, a cross-view depth-guided transformer is developed to fuse the depth embeddings as well as image features from cameras of different views and generate 3D bounding boxes. Extensive experiments demonstrated that our method hugely surpassed existing multi-camera methods by 10 percent in pedestrian detection and about 3 percent in overall mAP and NDS metrics. Also, computational analyses showed that our method is 5 times faster than prior approaches. Our codes will be made publicly available at https://github.com/sty61010/CrossDTR.

## Methods
<!-- ![](https://i.imgur.com/CXLTkjD.png) -->
![Methods](docs/figs/fig2_v2.png)

## Visualization
### Camera View
<!-- ![](https://i.imgur.com/9oVaxg6.jpg) -->
<!-- ![](https://i.imgur.com/FHspPqt.gif) -->
<!-- ![](https://i.imgur.com/2btgS60.gif) -->
<!-- ![](https://i.imgur.com/bvOaCCj.gif) -->
![Camera View](docs/gifs/ours_camera.gif)

### Bird Eye View
<!-- ![width="50%"](https://i.imgur.com/PeAAw8P.gif) -->
<!-- ![](https://i.imgur.com/HkpF552.gif) -->
<!-- ![](https://i.imgur.com/8ZNHHuR.gif) -->
<!-- ![](https://i.imgur.com/BxQ1YAu.gif) -->
<!-- ![](https://i.imgur.com/IbEpxN5.gif) -->
![Camera View](docs/gifs/BEV.gif)

## Getting Started
- The code is coming soon.

## BibTeX
If this work is helpful for your research, please consider citing the following BibTeX entry.
```bibtex
@article{tseng2022crossdtr,
  title={CrossDTR: Cross-view and Depth-guided Transformers for 3D Object Detection},
  author={Tseng, Ching-Yu and Chen, Yi-Rong and Lee, Hsin-Ying and Wu, Tsung-Han and Chen, Wen-Chin and Hsu, Winston},
  journal={arXiv preprint arXiv:2209.13507},
  year={2022}
}
```

## Acknowledgement
Many thanks to these excellent open source projects:
- [MonoDETR](https://github.com/ZrrSkywalker/MonoDETR)
- [PETR](https://github.com/megvii-research/PETR)
- [MMDetection3D](https://github.com/open-mmlab/mmdetection3d)



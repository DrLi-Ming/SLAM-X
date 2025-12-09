<p align="center">
  <h1 align="center">SLAM-<i>X</i>: Generalizable Dynamic Removal for NeRF and Gaussian Splatting SLAM</h1>
  <h3 align="center">MM '25</h3>
    <p align="center">Mingrui Li<sup>*</sup>, Dong Li<sup>*</sup>, Sijia Hu, Kangxu Wang, Zhenjun Zhao and Hongyu Wang<sup>†</sup></p>
    <h3 align="center"><a href="https://dl.acm.org/doi/10.1145/3746027.3754971">Paper</a> | <a href="https://github.com/user-attachments/assets/511c5911-9158-425c-a87e-ca107bbe068a">Video</a> </h3>
    <video src="https://github.com/user-attachments/assets/511c5911-9158-425c-a87e-ca107bbe068a" width="100%" controls autoplay > </video>
</p>


## Abstract

SLAM-X is a plug-and-play module that enhances dynamic-scene robustness for a wide range of NeRF-SLAM and GS-SLAM systems. It uses zero-shot segmentation and adaptive sparse optical flow to generate dynamic masks, enabling tracking and mapping correction while removing dynamic artifacts—without any task-specific fine-tuning.

We utilize [TUM RGB-D](https://cvg.cit.tum.de/data/datasets/rgbd-dataset) and [BONN RGB-D](https://www.ipb.uni-bonn.de/data/rgbd-dynamic-dataset/index.html) datasets to evaluate the performance of our algorithm, showing that it reliably mitigates dynamic disturbances and integrates seamlessly with existing SLAM frameworks, achieving state-of-the-art performance in dynamic environments.

<img alt="image" src="https://github.com/user-attachments/assets/6996fba4-19d7-40af-b766-9c963298c30c" />



## Build

_**Source code will be released soon.**_

## License
SLAM-X is released under the [GNU General Public License v3.0](LICENSE).

## Citation

If you find our work useful, please kindly cite us:

```bibtex
@inproceedings{10.1145/3746027.3754971,
author = {Li, Mingrui and Li, Dong and Hu, Sijia and Wang, Kangxu and Zhao, Zhenjun and Wang, Hongyu},
title = {SLAM-X: Generalizable Dynamic Removal for NeRF and Gaussian Splatting SLAM},
year = {2025},
isbn = {9798400720352},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3746027.3754971},
doi = {10.1145/3746027.3754971},
abstract = {NeRF-SLAM and GS-SLAM demonstrate excellent performance in high-fidelity rendering and real-time reconstruction in static scenes. However, real-world environments are often filled with dynamic objects, leading to tracking errors and mapping failures. Several dynamic SLAM approaches have been proposed, but they remain difficult to adopt due to challenges in deployment, framework compatibility, and generalization. To address these challenges, we introduce SLAM-X, the first plug-and-play module designed to universally enhance dynamic scene handling across a range of SLAM architectures. SLAM-Xleverages zero-shot segmentation and adaptively tracked sparse optical flow to generate dynamic masks, enabling tracking and mapping correction through continuous scene learning, while removing dynamic artifacts without requiring any task-specific fine-tuning. Extensive experiments on multiple real-world datasets demonstrate that SLAM-X effectively mitigates dynamic disturbances and seamlessly integrates with various NeRF-SLAM and GS-SLAM frameworks, achieving state-of-the-art performance in dynamic environments.},
booktitle = {Proceedings of the 33rd ACM International Conference on Multimedia},
pages = {1132–1140},
numpages = {9},
keywords = {3d gaussian splatting, dynamic object removal, nerf, slam},
location = {Dublin, Ireland},
series = {MM '25}
}
```
 

# SaRAN: Segmentation and Regression Attention Network for Data-Constrained Scene Understanding

## Evaluated Datasets (TBD):
- KITTI-360 ([Link](https://www.cvlibs.net/datasets/kitti-360/))
- nuScenes Panoptic ([Link](https://www.nuscenes.org/nuscenes#panoptic))
- CityScapes ([Link](https://www.cityscapes-dataset.com/))
- Audi A2D2 ([Link](https://www.a2d2.audi/en/))

## Evaluation Questions:
- How does deep supervision affect how well SaRAN converges?
- How small of a model can knowledge distillation (+ deep supervision) leverage that still results in reasonable performance?
- How well does knowledge sharing between Segmentation <-> Regression work?
- How effective can semi-supervised fine-tuning be when the model is pretrained on a different objective of the same dataset?

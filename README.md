# SaRAN: Segmentation and Regression Attention Network for Data-Constrained Scene Understanding

## Evaluated Datasets (TBD):
- KITTI-360 ([Link](https://www.cvlibs.net/datasets/kitti-360/))
- nuScenes Panoptic ([Link](https://www.nuscenes.org/nuscenes#panoptic))
- CityScapes ([Link](https://www.cityscapes-dataset.com/)) -> Random crop 512 x 512.
- Audi A2D2 ([Link](https://www.a2d2.audi/en/))

## Evaluation Questions:
- How does deep supervision affect how well a hybrid architecture converges?
- How small of a performant model can be achieved with  knowledge distillation (+ deep supervision)?
- How well does knowledge sharing between Segmentation <-> Regression work?
- How effective is semi-supervised fine-tuning when pretrained on a different objective of the same dataset?

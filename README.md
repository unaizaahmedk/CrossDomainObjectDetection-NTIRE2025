# CrossDomainObjectDetection-NTIRE2025

This repository contains our implementation project inspired by the **NTIRE 2025 Cross Object Detection Challenge** (CVPR 2025).

Rather than replicating the exact methodology from the paper, we explored a practical approach to few-shot object detection using a 5-shot subset of the COCO 2017 dataset and a pre-trained **DETR (DEtection TRansformer)** model.

The goal was to understand and experiment with cross-domain object detection concepts presented in the challenge through our own simplified pipeline.


---

## Features

- 5-shot dataset creation using COCO 2017 annotations
- Object detection using HuggingFace’s pre-trained `facebook/detr-resnet-50`
- Visualization of predictions with bounding boxes and class labels

---

## Contributors

- [@Khoula Adil](https://github.com/KhoulaAdil)
- [@Farheen Fatima](https://github.com/farheeen16)
- [@Uroosha Zehra Abidi](https://github.com/Uroosha4048)
- [@Nigarish Rehman Sarmad](https://github.com/nigarishrehmansarmad)

---

## Reference

- [NTIRE 2025: Cross Domain Object Detection Challenge](https://arxiv.org/pdf/2504.10685)
- [COCO Dataset](https://cocodataset.org)
- [DETR by Facebook](https://github.com/facebookresearch/detectron2)

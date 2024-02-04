# BlendMimic3D: A Synthetic Dataset for Human Pose Estimation
![Blendmimic3DOccl2](https://github.com/FilipaLino/BlendMimic3D/assets/102179022/f8c2147b-aadd-4a54-9500-09940f156373)

## Overview
BlendMimic3D is a synthetic dataset designed for Human Pose Estimation (HPE) research, particularly tailored to address challenges in smart retail environments. Developed using Blender, this dataset bridges the gap in existing HPE datasets by incorporating a diverse range of scenarios, including self-occlusions, object-based occlusions, and out-of-frame occlusions.

## Motivation
The creation of BlendMimic3D is driven by the need for more comprehensive and versatile datasets in the HPE field. While datasets like COCO and Human3.6M have significantly advanced HPE algorithms, they are limited in capturing complex real-world scenarios, particularly in retail settings.

## Dataset Features
- **Realistic Retail Environments:** BlendMimic3D encompasses various shopping activities and multi-person interactions, simulating real-world retail environments.
- **Diverse Occlusion Scenarios:** Specifically addresses self-occlusions, object occlusions, and out-of-frame occlusions.
- **Multi-Perspective Capture:** Utilizes four strategically placed cameras to capture a wide array of human movements and interactions.
- **Pixel-Perfect Annotations:** Offers detailed annotations for keypoints, bounding boxes, and labels.
- **Synthetic and Real Dataset Integration:** Merges with the Human3.6M dataset for enhanced diversity and complexity.

## Dataset Components
- **Videos:** A collection of videos capturing a range of actions from four different camera perspectives.
- **Camera Parameters:** Includes intrinsic and extrinsic parameters for camera calibration.
- **3D and 2D Keypoint Positions:** Provides both 3D and 2D positions of keypoints for comprehensive pose estimation.
- **Occlusion Data:** Contains information on occluded keypoints for each frame.

## Methodology
We employed a structured approach for dataset creation, including 3D model setup, environment creation, camera configuration, character animation, rendering, keypoint extraction, occlusion detection, and data saving. Our focus was on ensuring that the synthetic scenarios closely mirror real-world complexities.

## Usage and Integration
BlendMimic3D is designed for versatility and can be easily integrated with existing HPE models like VideoPose3D. The dataset is structured to facilitate direct comparisons with Human3.6M, enabling researchers to evaluate and benchmark their models effectively.

## Accessing the Dataset
The dataset is available for research purposes. Please follow this link to request access: [Dataset Access Link].

## Citation
If you use BlendMimic3D in your research, please cite it as follows:

```
[ citation format]
```

## Acknowledgements
This project has been supported by the Smart Retail project at the Institute for Systems and Robotics, funded by the Portuguese Recovery and Resilience Plan.


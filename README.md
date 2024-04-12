# BlendMimic3D: A Synthetic Dataset for Human Pose Estimation
![Blendmimic3DOccl2](https://github.com/FilipaLino/BlendMimic3D/assets/102179022/f8c2147b-aadd-4a54-9500-09940f156373)
BlendMimic3D is a pioneering synthetic dataset developed using Blender, designed to enhance Human Pose Estimation (HPE) research. This dataset features diverse scenarios including self-occlusions, object-based occlusions, and out-of-frame occlusions, tailored for the development and testing of advanced HPE models.

## Overview
BlendMimic3D bridges the gap in existing datasets by offering realistic scenarios, facilitating the development of algorithms capable of handling complex real-world challenges.

## Motivation
Existing HPE datasets have significantly contributed to the advancement of pose estimation technologies. However, the complexity and variability of real-world scenarios demand more versatile and comprehensive datasets. BlendMimic3D addresses these needs by providing detailed scenarios that mimic real-life challenges.

## Dataset Features
- **Realistic Environments:** BlendMimic3D encompasses simple environments, resembling Human3.6M dataset, shopping activities and multi-person contexts, simulating real-world environments.
- **Diverse Occlusion Scenarios:** Specifically addresses self-occlusions, object-based occlusions, and out-of-frame occlusions.
- **Multi-Perspective Capture:** Utilizes four cameras to capture diverse human movements and interactions from multiple angles.
- **Pixel-Perfect Annotations:** Offers detailed annotations for 2D keypoints, 3D keypoints, and occlusion data.
<p align="center">
  <img src="https://github.com/FilipaLino/BlendMimic3D/assets/102179022/41064897-98a3-40a5-8642-71fbc1f03dd0" width="70%" height="70%">
</p>

## Dataset Components
- **Videos:** A collection of videos capturing a range of actions from four different camera perspectives.
- **Camera Parameters:** Includes intrinsic and extrinsic parameters for camera calibration.
- **3D and 2D Keypoint Positions:** Provides both 3D and 2D positions of keypoints for comprehensive pose estimation.
- **Occlusion Data:** Contains a binary array depicting which keypoints are occluded in each frame.
![Dataset-Data (1)](https://github.com/FilipaLino/BlendMimic3D/assets/102179022/4fc14114-6cda-42a1-8b73-eda562e7cf46)

## Usage and Integration
BlendMimic3D is designed for versatility and can be easily integrated with existing HPE models. The dataset is structured to facilitate direct comparisons with Human3.6M, enabling researchers to evaluate and benchmark their models effectively.

## Dataset Organization 

The BlendMimic3D dataset is organized ensuring comprehensive coverage of various human pose estimation challenges:

- **Scenarios:** Three distinct scenarios ranging from simple environments to more complex and realistic settings.
- **Subjects:** Three synthetic subjects, each performing a variety of actions to simulate single and multi-person contexts, with up to three subjects present.
- **Videos:** A total of 128 videos, each with an average duration of 20 seconds (600 frames), capturing a wide array of actions from four different camera perspectives.
- **Data Structure:** For each subject, the dataset is organized into folders for Videos, D2_Positions, D3_Positions, Occlusions, and Cameras, containing files with their respective information.

This dataset is designed to reflect the structure of the Human3.6M dataset, categorized by subject and action. Synthetic subjects designated as S1, S2, and S3 each cover 14 distinct actions. S1 focuses on self-occlusions, S2 on object and out-of-frame occlusions, and S3 tackles both occlusions and multi-person scenarios in a retail environment. 

## Citation
If you use our dataset in your research, please cite our paper: 
```
[ citation format]
```

## Acknowledgements
This work was supported by LARSyS funding (DOI: 10.54499/LA/P/0083/2020, 10.54499/UIDP/50009/2020, and 10.54499/UIDB/50009/2020) and 10.54499/2022.07849.CEECIND/CP1713/CT0001, through Fundação para a Ciência e a Tecnologia, and by the SmartRetail project [PRR - C645440011-00000062], through IAPMEI - Agência para a Competitividade e Inovação.
<p align="center">
  <img src="https://github.com/FilipaLino/BlendMimic3D/assets/102179022/670897d0-1f7d-43e8-b63b-b2b961242730" width="50%" height="50%">
</p>


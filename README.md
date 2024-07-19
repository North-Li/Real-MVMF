## Real-MVMF: a set of real-world multi-view multi-focus datasets

This dataset is captured by a 3x3 multi-view multi-focus (MVMF) imaging system, including 7 indoor scenes and 3 outdoor scenes. Thumbnails of all scenes are shown below:

<img src="https://github.com/hanna-xu/road-scene-infrared-visible-images/blob/master/crop_HR_visible/FLIR_05164.jpg" width="400" height="220"/>


This dataset contains 630 defocus image sequences and corresponding ground-truth with 1920x1080 resolution captured from 7 scenens ("Meetingroom"scene, "Livingroom"scene, "Bathroom"scene, "Street"scene, "Furniture" scene, "Machine" scene and "Industrialparts"scene). At present, for each scene, we provide 81 multi-focus images at the first frame with 240x135 resolution for download. The complete dataset will be released upon publication.

## Code

The source codes for our extensive validation experiments on depth estimation, 3D reconstruction and novel view synthesis tasks are now available. Please refer to the [Code](https://github.com/North-Li/MVMFI/tree/main/Code) folder.

## Environment

- Python >= 3.7
- PyTorch >= 1.4.0 is recommended
- opencv-python = 4.5.1
- matplotlib
- tensorboard
- pytorch_msssim
  
## Results

We release all the depth estimation, 3D reconstruction and novel view synthesis comparison results with 240x135 resolution between MVMFI and conventional multi-view video. For each scene, we reconstruct 81 dynamic depth map videos, 1 dynamic 3D point cloud video and synthesize 120 dynamic novel view videos. Please refer to the [Results](https://github.com/North-Li/MVMFI/tree/main/Results) folder. The complete comparison results with 1920x1080 resolution will be released upon publication.

## Declare

This dataset and results cannot be used for commercial purposes. For non-commercial research or educational purposes, please inform us for our permission via yangyou AT hust DOT edu DOT cn.

# 🛡️ Awesome Anti-UAV

A curated collection of **datasets and research papers for Anti-UAV**.

This repository provides a concise and continuously updated resource for researchers working on UAV perception and Anti-UAV systems.

---

## 📊 Datasets

A collection of publicly available datasets for UAV classification, detection, and tracking.

| Dataset | Task | Modality | Scale | Year |
|---|---|---|---|---:|
| [Anti-UAV](https://github.com/ZhaoJ9014/Anti-UAV) | D, T | RGB, IR | 318 sequences / 297K frames | 2021 |
| [Anti-UAV410](https://github.com/HwangBo94/Anti-UAV410) | D, T | IR | 410 sequences / 438K frames | 2023 |
| [Anti-UAV600](https://github.com/ZhaoJ9014/Anti-UAV) | D, T | IR | 600 sequences / 723K frames | 2023 |
| [MMAUD](https://ntu-aris.github.io/MMAUD/) | C, D, T | RGB, Audio, Radar, LiDAR | 50 sequences / 45K frames | 2024 |
| [MM-UAV](https://xuefeng-zhu5.github.io/MM-UAV/) | T | RGB, IR, Event | 1,321 sequences / 2.8M frames | 2025 |
| [Tri-Modal Anti-UAV](https://github.com/eulerbaby123/Tri-Modal-Anti-UAV) | D | RGB, IR, Event | 1,060 triplets | 2025 |
| [MMA-UAV](https://ieee-dataport.org/documents/mma-uava-multimodal-low-altitude-anti-uav-dataset-based-infraredvisible-light-images) | D | RGB, IR, LiDAR, RF | — | 2025 |
| [UAV-CB](https://github.com/hye999/UAV-CB) | D | RGB, IR | 3,393 pairs | 2026 |

**Task:** C = Classification, D = Detection, T = Tracking

[**View all datasets →**](datasets.md)

---

## 🎯 UAV Classification

Research on UAV/drone classification and identification using visual, infrared, radar, RF, acoustic, and other sensing modalities.

| Paper            | Venue  | Modality | Dataset | Code |
| ---------------- | ------ | -------- | ------- | ---- |
| [Multi-Modal UAV Detection, Classification and Tracking Algorithm](https://arxiv.org/abs/2405.16464) | CVPRW 2024 | RGB, Audio, Radar, LiDAR | MMAUD | [GitHub](https://github.com/dtc111111/Multi-Modal-UAV) |


[**View all classification papers →**](classification.md)

---

## 🔍 UAV Detection

Research on UAV/drone detection using RGB, infrared, radar, RF, acoustic, and multimodal sensing.

| Paper            | Venue  | Modality | Dataset | Code |
| ---------------- | ------ | -------- | ------- | ---- |
| [Multi-Modal UAV Detection, Classification and Tracking Algorithm](https://arxiv.org/abs/2405.16464) | CVPRW 2024 | RGB, Audio, Radar, LiDAR | MMAUD | [GitHub](https://github.com/dtc111111/Multi-Modal-UAV) |
| [SCINet: Spatial and Contrast Interactive Super-Resolution Assisted Infrared UAV Target Detection](https://doi.org/10.1109/TGRS.2024.3471786) | TGRS 2024 | IR | Infrared UAV Sequences | [GitHub](https://github.com/IVPLabs/SCINet) |
| [Visible and Clear: Finding Tiny Objects in Difference Map](https://arxiv.org/abs/2405.11276) | ECCV 2024 | RGB | DroneSwarms | [GitHub](https://github.com/Hiyuur/SR-TOD) |
| [Detection and Localization of Drones and UAVs Using Sound and Vision](https://openaccess.thecvf.com/content/CVPR2025W/Anti-UAV/html/Tegler_Detection_and_Localization_of_Drones_and_UAVs_Using_Sound_and_Vision_CVPRW_2025_paper.html) | CVPRW 2025 | RGB, Audio | — | — |
| [Detection-Friendly Nonuniformity Correction: A Union Framework for Infrared UAV Target Detection](https://openaccess.thecvf.com/content/CVPR2025/html/Fang_Detection-Friendly_Nonuniformity_Correction_A_Union_Framework_for_Infrared_UAV_Target_CVPR_2025_paper.html) | CVPR 2025 | IR | IRBFD | [GitHub](https://github.com/IVPLabs/UniCD) |
| [YOLO-RAW: Advancing UAV Detection With Robustness to Adverse Weather Conditions](https://doi.org/10.1109/TITS.2025.3560792) | TITS 2025 | RGB | YOLO-RAW Dataset | [GitHub](https://github.com/AdnanMunir338/YOLO-RAW) |
| [Event-based Tiny Object Detection: A Benchmark Dataset and Baseline](https://openaccess.thecvf.com/content/ICCV2025/html/Chen_Event-based_Tiny_Object_Detection_A_Benchmark_Dataset_and_Baseline_ICCV_2025_paper.html) | ICCV 2025 | Event | EV-UAV | [GitHub](https://github.com/ChenYichen9527/EV-UAV) |
| [TransAUAV: A Transformer-Enhanced RGB-Infrared Fusion Network for Anti-UAV Detection](https://doi.org/10.1109/TAES.2025.3646996) | TAES 2025 | RGB, IR | Anti-UAV | — |
| [Blur-Robust Detection via Feature Restoration: An End-to-End Framework for Prior-Guided Infrared UAV Target Detection](https://ojs.aaai.org/index.php/AAAI/article/view/37986) | AAAI 2026 | IR | IRBlurUAV | [GitHub](https://github.com/IVPLabs/JFD3) |
| [Adaptive 3D Perception for Small Aerial Targets Under Sparse Sampling via Reinforcement Learning](https://openaccess.thecvf.com/content/CVPR2026/html/Yuan_Adaptive_3D_Perception_for_Small_Aerial_Targets_Under_Sparse_Sampling_CVPR_2026_paper.html) | CVPR 2026 | LiDAR | MMAUD | — |
| [UAV-CB: A Complex-Background RGB-T Dataset and Local Frequency Bridge Network for UAV Detection](https://openaccess.thecvf.com/content/CVPR2026/html/Huang_UAV-CB_A_Complex-Background_RGB-T_Dataset_and_Local_Frequency_Bridge_Network_CVPR_2026_paper.html) | CVPR 2026 | RGB, IR | UAV-CB | [GitHub](https://github.com/hye999/UAV-CB) |
| [UAV-DETR: DETR for Anti-Drone Target Detection](https://arxiv.org/abs/2603.22841) | arXiv 2026 | RGB | DUT-ANTI-UAV | [GitHub](https://github.com/wd-sir/UAVDETR) |

[**View all detection papers →**](detection.md)

---

## 🚁 UAV Tracking

Research on UAV/drone tracking, including single-object tracking, multi-object tracking, and multimodal tracking.

| Paper | Venue | Modality | Dataset | Code |
| ---------------- | ------ | -------- | ------- | ---- |
| [Multi-Modal UAV Detection, Classification and Tracking Algorithm](https://arxiv.org/abs/2405.16464) | CVPRW 2024 | RGB, Audio, Radar, LiDAR | MMAUD | [GitHub](https://github.com/dtc111111/Multi-Modal-UAV) |
| [JTD-UAV: MLLM-Enhanced Joint Tracking and Description Framework for Anti-UAV Systems](https://openaccess.thecvf.com/content/CVPR2025/html/Wang_JTD-UAV_MLLM-Enhanced_Joint_Tracking_and_Description_Framework_for_Anti-UAV_Systems_CVPR_2025_paper.html) | CVPR 2025 | RGB, IR | TDUAV | — |
| [Tracking Tiny Drones against Clutter: Large-Scale Infrared Benchmark with Motion-Centric Adaptive Algorithm](https://openaccess.thecvf.com/content/ICCV2025/html/Zhang_Tracking_Tiny_Drones_against_Clutter_Large-Scale_Infrared_Benchmark_with_Motion-Centric_ICCV_2025_paper.html) | ICCV 2025 | IR | TDTIV, Anti-UAV410 | [GitHub](https://github.com/zhangjiahao02/MCATrack) |


[**View all tracking papers →**](tracking.md)

---

<p align="center">
  ⭐ If you find this repository useful, please consider starring it.
</p>


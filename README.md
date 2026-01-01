# Research Review in 2025
The main themes are in 1) efficient multi-agent learning, 2) simulation and 3) end-to-end autonomous driving.

## Efficient Multi-agent learning
1. Inference-efficient multi-agent system via full-stack quantization: **QuantV2X: A Fully Quantized Multi-Agent System for Cooperative Perception** ([paper link](https://arxiv.org/abs/2509.03704)).
2. Training-efficient multi-agent system for end-to-end learning: **TurboTrain: Towards Efficient and Balanced Multi-Task Learning for Multi-Agent Perception and Prediction** ([paper link](https://www.arxiv.org/abs/2508.04682)).
3. Real-world system-level efficiency oriented benchmark for V2X system: **V2X-ReaLO: An Open Online Framework and Dataset for Cooperative Perception in Reality** ([paper link](https://arxiv.org/pdf/2503.10034)).

## Simulation
1. Scalable urban simulation platform enables scalable closed-loop agentic training: **Towards Autonomous Micromobility through Scalable Urban Simulation** ([paper link](https://arxiv.org/abs/2505.00690)).

## End-to-end Autonomous Driving
1. Vision-language-action (VLA) model for end-to-end autonomous driving: **AutoVLA: A Vision-Language-Action Model for End-to-End Autonomous Driving with Adaptive Reasoning and Reinforcement Fine-Tuning** ([paper link](https://arxiv.org/abs/2506.13757)).
  
# Research Review in 2024
The main themes are in 1) efficient multi-agent learning and 2) agentic AI in the Autonomous Driving Scenarios.

## Efficient Multi-agent Learning
1. Data-efficient Self-supervised Learning on Multi-agent Perception: **CooPre: Cooperative Pretraining for V2X Cooperative Perception** ([paper link](https://arxiv.org/abs/2408.11241)). We leverage a self-supervised reconstruction pretraining method to improve multi-agent perception framework in a data efficient way.
2. Communication-efficient on Multi-agent Perception and Prediction: **V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction** ([paper link](https://arxiv.org/pdf/2412.01812)).
3. Heterogeneous Modality Alignment on Multi-agent Perception: **AgentAlign: Misalignment-Adapted Multi-Agent Perception for Resilient Inter-Agent Sensor Correlations** ([paper link](https://arxiv.org/pdf/2412.06142)).

## Agentic AI
1. Agentic Interaction & Intention Benchmark: **WOMD-Reasoning: A Large-Scale Dataset for Interaction Reasoning in Driving** ([paper link](https://arxiv.org/pdf/2407.04281)).
2. Agentic Decision-making: **Driving with Regulation: Trustworthy and Interpretable Decision-Making for Autonomous Driving with Retrieval-Augmented Reasoning** ([paper link](https://arxiv.org/pdf/2410.04759)).



# Research Review in 2022 & 2023
The main themes are in 1) self-supervised learning in multimodal setting and 2) 3D algorithm and benchmarking.

## Self-supervised Learning in Multimodal Deep Learning
We have three algorithms presented across vision, language, speech domains, as well as for trajectory prediction problem in autonomous driving.

1. **Multimodal Semantic Mismatch Detection in Social Media Posts** ([paper link](https://ieeexplore.ieee.org/abstract/document/9949462)). We leveraged a self-supervised contrastive learning method to let the model learn semantic difference in a large training batch on video and text semantic mismatch detection in social media.
2. **Enhancing GAN-Based Vocoders with Contrastive Learning Under Data-limited Condition** ([paper link](http://arxiv.org/abs/2309.09088)). We observed the low-resource scenarios presented in speech synthesis and proposed to apply self-supervised contrastive learning method to improve the perceptual quality of the vocoder without modifying its architecture or adding more data.
3. **Pre-training on Synthetic Driving Data for Trajectory Prediction** ([paper link](https://arxiv.org/abs/2309.10121)). We introduced a novel map augmentation and trajectory data generation process to effortlessly address data scarcity issues for trajectory forecasting. We comprehensively explore the self-supervised pretraining strategy and extend the concept of Masked AutoEncoder (MAE), utilizing it for trajectory forecasting.

## 3D Object Tracking & Localization
We have two continuous work on the Digital-Twin 3D object pose estimation benchmarks and algorithms.

1. **Digital Twin Tracking Dataset (DTTD): A New RGB+Depth 3D Dataset for Longer-Range Object Tracking Applications** ([paper link](https://openaccess.thecvf.com/content/CVPR2023W/VDU/html/Feng_Digital_Twin_Tracking_Dataset_DTTD_A_New_RGBDepth_3D_Dataset_CVPRW_2023_paper.html)). A novel RGB-D dataset captured by Microsoft Azure Kinect to enable further research of the 3D Object Tracking problem and extend potential solutions towards longer ranges and mm localization accuracy.
2. **Robust 6DoF Pose Estimation Against Depth Noise and a Comprehensive Evaluation on a Mobile Dataset** ([paper link](https://arxiv.org/abs/2309.13570)). A continuous work of DTTD, where we extend Digital-Twin Tracking into mobile AR scenarios by creating a comprehensive pose estimation dataset captured by iPhone sensor and a depth-robust pose estimator against noisy depth input.
3. **Pose-Aware Weakly-Supervised Action Segmentation** ([paper link](https://arxiv.org/abs/2504.05700)). We apply pose information for video action segmentation task via contrastive learning based knowledge distillation.

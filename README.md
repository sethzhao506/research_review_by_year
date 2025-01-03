# Research Review in 2024
The main themes are in 1) efficient multi-agent learning and 2) agentic AI in the Autonomous Driving Scenarios.

## Efficient Multi-agent Learning
1. Data-efficient Self-supervised Learning on Multi-agent Perception: **CooPre: Cooperative Pretraining for V2X Cooperative Perception** ([paper link](https://arxiv.org/abs/2408.11241)). We leverage a self-supervised reconstruction pretraining method to improve multi-agent perception framework in a data efficient way.
2. Communication-efficient on Multi-agent Perception and Prediction: **V2XPnP: Vehicle-to-Everything Spatio-Temporal Fusion for Multi-Agent Perception and Prediction** ([paper link](https://arxiv.org/pdf/2412.01812)).
3. Heterogeneous Modality Alignment on Multi-agent Perception: **AgentAlign: Misalignment-Adapted Multi-Agent Perception for Resilient Inter-Agent Sensor Correlations** ([paper link](https://arxiv.org/pdf/2412.06142)).

## Agentic AI
1. Agentic Interaction & Intention Benchmark: **WOMD-Reasoning: A Large-Scale Dataset and Benchmark for Interaction and Intention Reasoning in Driving** ([paper link](https://arxiv.org/pdf/2407.04281)).
2. Agentic Decision-making: **Driving with Regulation: Interpretable Decision-Making for Autonomous Vehicles with Retrieval-Augmented Reasoning via LLM** ([paper link](https://arxiv.org/pdf/2410.04759)).



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

2. **Robust Digital-Twin Localization via An RGBD-based Transformer Network and A Comprehensive Evaluation on a Mobile Dataset** ([paper link](https://arxiv.org/abs/2309.13570)). A continuous work of DTTD, where we extend Digital-Twin Tracking into mobile AR scenarios by creating a comprehensive pose estimation dataset captured by iPhone sensor and a depth-robust pose estimator against noisy depth input.

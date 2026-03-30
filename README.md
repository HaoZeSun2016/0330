# 0330
1
## WAM 调研
---
### 论文合集

https://github.com/yzhang2016/video-generation-survey/tree/main 

https://github.com/ChenHsing/Awesome-Video-Diffusion-Models?tab=readme-ov-file

https://github.com/NVlabs/Sana?tab=readme-ov-file 

### WAM核心论文

DreamZero: World Action Models are Zero-shot Policies

https://arxiv.org/pdf/2602.15922 
首次证明视频模型可以引导action的泛化

GigaWorld-Policy: An Efficient Action-Centered World–Action Model

https://arxiv.org/pdf/2603.17240
在Dream基础上提出了action/video frame交错预测的范式

Motus: A Unified Latent Action World Model

https://arxiv.org/pdf/2512.13030
未来VLA+WAM融合的方案

AutoMoT: A Unified Vision-Language-Action Model with Asynchronous Mixture-of-Transformers for End-to-End Autonomous Driving

https://arxiv.org/pdf/2603.14851 
小米的VLA+MoT方案

BagelVLA: Enhancing Long-Horizon Manipulation via Interleaved Vision-Language-Action Generation

https://arxiv.org/pdf/2602.09849 
未来VLA+WAM融合的方案 Residual Flow Guidance (RFG)方案可以参考用于加速

GAIA-2: A Controllable Multi-View Generative World Model for Autonomous Driving

https://arxiv.org/pdf/2503.20523 
首个自动驾驶领域多视角图像videogen world model 非常有参考价值

X-World: Controllable Ego-Centric Multi-Camera World Models for Scalable End-to-End Driving

小鹏的世界模型 基于WAN直接改了vae和condition 但fps太低不适合直接上车
https://arxiv.org/pdf/2603.19979 

GigaWorld-0: World Models as Data Engine to Empower Embodied AI

https://arxiv.org/pdf/2511.19861 

### 视频生成核心论文

SANA-Video: Efficient Video Generation with Block Linear Diffusion Transformer

https://arxiv.org/pdf/2509.24695v2 
满足AR 线性注意力 小模型

MAGI-1: Autoregressive Video Generation at Scale

https://arxiv.org/pdf/2505.13211 
AR Diffusion从0训练范式

[重要] daVinci-MagiHuman最新的单流模型设计

https://github.com/GAIR-NLP/daVinci-MagiHuman/tree/main

Helios: Real Real-Time Long Video Generation Model

https://arxiv.org/pdf/2603.04379 
Next scale AR Diffusion

WAN: OPEN AND ADVANCED LARGE-SCALE VIDEO GENERATIVE MODELS

https://arxiv.org/pdf/2503.20314 
Wan 开源技术报告

LTX-Video: Realtime Video Latent Diffusion

https://arxiv.org/pdf/2501.00103 

[重要] DC-VideoGen: Efficient Video Generation with Deep Compression Video Autoencoder

[重要] DEEP COMPRESSION AUTOENCODER FOR EFFICIENT HIGH-RESOLUTION DIFFUSION MODELS

[重要] DC-AE 1.5: Accelerating Diffusion Model Convergence with Structured Latent Space (channel wise dropout 帮助模型区分语义和细节信息)

https://arxiv.org/pdf/2509.25182  https://arxiv.org/pdf/2410.10733 https://arxiv.org/pdf/2508.00413 
极致的vae压缩，并且在WAN系列基础上更换vae后训练

### 基础研究

Causal Forcing: Autoregressive Diffusion Distillation Done Right for High-Quality Real-Time Interactive Video Generation

https://arxiv.org/pdf/2602.02214 
视频生成双向蒸单向

Self-Supervised Flow Matching for Scalable Multi-Modal Synthesis

https://cdn.sanity.io/files/2gpum2i6/production/3264c9e34dfcbbf57e57ca7efee0a3e83d311a83.pdf 
训练加速 类似REPA

One-step Diffusion with Distribution Matching Distillation

https://openaccess.thecvf.com/content/CVPR2024/papers/Yin_One-step_Diffusion_with_Distribution_Matching_Distillation_CVPR_2024_paper.pdf 
采样加速

MoDification: Mixture of Depths Made Easy  

https://arxiv.org/pdf/2410.14268 
模型结构加速Mix of Depth

FluxMem: Adaptive Hierarchical Memory for Streaming Video Understanding

https://arxiv.org/pdf/2603.02096 
视频理解推理token压缩

FSVideo: Fast Speed Video Diffusion Model in a Highly-Compressed Latent Space

https://arxiv.org/pdf/2602.02092 
Vae tokenizer高倍率压缩以及高维度


Contrastive Flow Matching

https://arxiv.org/pdf/2506.05350v1 
Flow matching 训练加速 可以和REPA叠加使用

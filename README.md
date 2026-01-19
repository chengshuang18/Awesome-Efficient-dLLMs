# Awesome-Efficient-dLLMs

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/FelixMessi/Awesome-Efficient-dLLMs)
[![Stars](https://img.shields.io/github/stars/FelixMessi/Awesome-Efficient-dLLMs?style=social)](https://img.shields.io/github/stars/FelixMessi/Awesome-Efficient-dLLMs?style=social)
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC--BY--NC--ND%204.0-blue.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)
[![PRWelcome](https://img.shields.io/badge/PRs-Welcome-red)](https://img.shields.io/badge/PRs-Welcome-red)



📒A curated list of Awesome **Efficient Diffusion Language Models** Papers with codes.



## ©️Citations 

```BibTeX

```


## 📙 Training Efficiency  

<div id="Training"></div>  

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2024.10| AR-to-diffusion |[**DiffuLLaMA**] Scaling Diffusion Language Models via Adaptation from Autoregressive Models (@HKU)  | [[pdf]](https://arxiv.org/pdf/2410.17891) |[[code]](https://github.com/HKUNLP/DiffuLLaMA) ![](https://img.shields.io/github/stars/HKUNLP/DiffuLLaMA.svg?style=social) |ICLR 2025|

## 📙 Inference Acceleration | Parallel Decoding
 
|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.05| Heuristic Methods |[**Fast-dLLM**] Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2505.22618) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |arXiv|



## 📙 Inference Acceleration | Cache Management

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.05| Architectural Paradigms |[**Fast-dLLM**] Fast-dLLM: Training-free Acceleration of Diffusion LLM by Enabling KV Cache and Parallel Decoding (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2505.22618) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |arXiv|


## 📙 Inference Acceleration | Compression Techniques

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.08| Quantization |[**QDLM**] Quantization Meets dLLMs: A Systematic Study of Post-training Quantization for Diffusion LLMs (@CASIA)| [[pdf]](https://arxiv.org/pdf/2508.14896) |[[code]](https://github.com/FelixMessi/QDLM)![](https://img.shields.io/github/stars/FelixMessi/QDLM.svg?style=social) |arXiv|
|2025.08| Quantization |[**DLLMQuant**] DLLMQuant: Quantizing Diffusion-based Large Language Models (@Houmo)| [[pdf]](https://arxiv.org/pdf/2508.14896) | |arXiv|
|2025.09| Quantization |[**Quant-dLLM**] Quant-dLLM: Post-Training Extreme Low-Bit Quantization for Diffusion Large Language Models (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.03274) |[[code]](https://github.com/ZTA2785/Quant-dLLM)![](https://img.shields.io/github/stars/ZTA2785/Quant-dLLM.svg?style=social) |arXiv|
|2025.06| Distillation |[**DLM-One**] DLM-One: Diffusion Language Models for One-Step Sequence Generation (@UTAustin)| [[pdf]](https://arxiv.org/pdf/2506.00290) | |arXiv|
|2025.12| Distillation |[**FS-DSM**] Fast-Decoding Diffusion Language Models via Progress-Aware Confidence Schedules (@MBZUAI)| [[pdf]](https://arxiv.org/pdf/2512.02892) | |arXiv|
|2026.01| Distillation |[**CD4LM**] CD4LM: Consistency Distillation and aDaptive Decoding for Diffusion Language Models (@Princeton)| [[pdf]](https://arxiv.org/pdf/2601.02236) |[[code]](https://github.com/yihao-liang/CDLM)![](https://img.shields.io/github/stars/yihao-liang/CDLM.svg?style=social) |arXiv|



## 📙 Contextual Scalability | Variable Length

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.08| Variable Length |[**DAEDAL**] Beyond Fixed: Training-Free Variable-Length Denoising for Diffusion Large Language Models (@CUHK)| [[pdf]](https://arxiv.org/pdf/2508.14896) |[[code]](https://github.com/Li-Jinsong/DAEDAL)![](https://img.shields.io/github/stars/Li-Jinsong/DAEDAL.svg?style=social) |arXiv|
|2025.10| Variable Length |[**dLLM-Var**] Diffusion LLM with Native Variable Generation Lengths: Let [EOS] Lead the Way (@SJTU)| [[pdf]](https://arxiv.org/pdf/2510.24605) |[[code]](https://github.com/maomaocun/dLLM-Var)![](https://img.shields.io/github/stars/maomaocun/dLLM-Var.svg?style=social) |arXiv|
|2025.11| Variable Length |[**ODB-dLLM**] Orchestrating Dual-Boundaries: An Arithmetic Intensity Inspired Acceleration Framework for Diffusion Language Models (@PKU)| [[pdf]](https://arxiv.org/pdf/2511.21759) |[[code]](https://github.com/PKU-SEC-Lab/ODB-dLLM)![](https://img.shields.io/github/stars/PKU-SEC-Lab/ODB-dLLM.svg?style=social) |arXiv|
|2025.09| Variable Length |[**FlexMDM**] Any-Order Flexible Length Masked Diffusion (@Harvard)| [[pdf]](https://arxiv.org/pdf/2509.01025) |[[code]](https://github.com/brianlck/FlexMDM)![](https://img.shields.io/github/stars/brianlck/FlexMDM.svg?style=social) |arXiv|
|2022.10| Variable Length |[**DiffuSeq**] DiffuSeq: Sequence to Sequence Text Generation with Diffusion Models (@HKU)| [[pdf]](https://arxiv.org/pdf/2210.08933) |[[code]](https://github.com/Shark-NLP/DiffuSeq)![](https://img.shields.io/github/stars/Shark-NLP/DiffuSeq.svg?style=social) |ICLR 2023|
|2023.05| Variable Length |[**AR-Diffusion**] AR-Diffusion: Auto-Regressive Diffusion Model for Text Generation (@Microsoft)| [[pdf]](https://arxiv.org/pdf/2305.09515) |[[code]](https://github.com/wutong4012/AR-Diffusion)![](https://img.shields.io/github/stars/wutong4012/AR-Diffusion.svg?style=social) |NeurIPS 2023|UW
|2022.10| Variable Length |[**SSD-LM**] SSD-LM: Semi-autoregressive Simplex-based Diffusion Language Model for Text Generation and Modular Control (@UW)| [[pdf]](https://arxiv.org/pdf/2210.17432) |[[code]](https://github.com/xhan77/SSD-LM)![](https://img.shields.io/github/stars/xhan77/SSD-LM.svg?style=social) |ACL 2023|
|2025.10| Variable Length |[**OneFlow**] OneFlow: Concurrent Mixed-Modal and Interleaved Generation with Edit Flows (@Meta)| [[pdf]](https://arxiv.org/pdf/2510.03506) | |arXiv|
|2025.08| Variable Length |[**Dream 7B**] Dream 7B: Diffusion Large Language Models (@HKU)| [[pdf]](https://arxiv.org/pdf/2508.15487) |[[code]](https://github.com/HKUNLP/Dream)![](https://img.shields.io/github/stars/HKUNLP/Dream.svg?style=social) |arXiv|


## 📙 Contextual Scalability | Long Context

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.06| Long context |[**LongLLaDA**] LongLLaDA: Unlocking Long Context Capabilities in Diffusion LLMs (@FDU)| [[pdf]](https://arxiv.org/pdf/2506.14429) |[[code]](https://github.com/OpenMOSS/LongLLaDA)![](https://img.shields.io/github/stars/OpenMOSS/LongLLaDA.svg?style=social) |AAAI2026|
|2025.10| Long Context |[**Rainbow Padding**] Rainbow Padding: Mitigating Early Termination in Instruction-Tuned Diffusion LLMs (@Yonsei)| [[pdf]](https://arxiv.org/pdf/2510.03680) |[[code]](https://github.com/quasar529/rainbow-padding)![](https://img.shields.io/github/stars/quasar529/rainbow-padding.svg?style=social) |arXiv|
|2025.10| Long Context |[**UltraLLaDA**] UltraLLaDA: Scaling the Context Length to 128K for Diffusion Large Language Models (@HKUST)| [[pdf]](https://arxiv.org/pdf/2510.10481) |[[code]](https://github.com/Relaxed-System-Lab/UltraLLaDA)![](https://img.shields.io/github/stars/Relaxed-System-Lab/UltraLLaDA.svg?style=social) |arXiv|
|2025.05| Long Context |[**Dimple**] Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding (@NUS)| [[pdf]](https://arxiv.org/pdf/2505.16990) |[[code]](https://github.com/yu-rp/Dimple)![](https://img.shields.io/github/stars/yu-rp/Dimple.svg?style=social) |arXiv|
|2025.03| Long Context |[**Block Diffusion**] Block Diffusion: Interpolating Between Autoregressive and Diffusion Language Models (@Cornell)| [[pdf]](https://arxiv.org/pdf/2503.09573) |[[code]](https://github.com/kuleshov-group/BD3-LMs)![](https://img.shields.io/github/stars/kuleshov-group/BD3-LMs.svg?style=social) |ICLR 2025|
|2025.09| Long Context |[**Fast-dLLM v2**] Fast-dLLM v2: Efficient Block-Diffusion LLM (@NVIDIA)| [[pdf]](https://arxiv.org/pdf/2509.26328) |[[code]](https://github.com/NVlabs/Fast-dLLM)![](https://img.shields.io/github/stars/NVlabs/Fast-dLLM.svg?style=social) |arXiv|
|2025.05| Long Context |[**CtrlDiff**] CtrlDiff: Boosting Large Diffusion Language Models with Dynamic Block Prediction and Controllable Generation (@PKU)| [[pdf]](https://arxiv.org/pdf/2505.14455) | |arXiv|
|2025.09| Long Context |[**AdaBlock-dLLM**] AdaBlock-dLLM: Semantic-Aware Diffusion LLM Inference via Adaptive Block Size (@ICL)| [[pdf]](https://arxiv.org/pdf/2509.26432) | |arXiv|
|2024.07| Long Context |[**DDLM-Sum**] Discrete Diffusion Language Model for Efficient Text Summarization (@VinUni)| [[pdf]](https://arxiv.org/pdf/2407.10998) | |NAACL 2025|


## 📙 System Framework

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.12| Post-training |[**DiRL**] An Efficient Post-Training Framework for Diffusion Language Models (@FDU)| [[pdf]](https://arxiv.org/pdf/2512.22234) |[[code]](https://github.com/OpenMOSS/DiRL)![](https://img.shields.io/github/stars/OpenMOSS/DiRL.svg?style=social) |arXiv|



## 📙 Multimodal DLM

|Date|Category|Title|Paper|Code|Venue|
|:---:|:---|:---|:---:|:---:|:---:|  
|2025.05| Training & Inference Stage |[**Dimple**] Dimple: Discrete Diffusion Multimodal Large Language Model with Parallel Decoding (@NUS)| [[pdf]](https://arxiv.org/pdf/2505.16990) |[[code]](https://github.com/yu-rp/Dimple)![](https://img.shields.io/github/stars/yu-rp/Dimple.svg?style=social) |arXiv|
|2025.12| Training Stage |[**SDAR-VL**] SDAR-VL: Stable and Efficient Block-wise Diffusion for Vision-Language Understanding (@ZJU)| [[pdf]](https://arxiv.org/pdf/2512.14068) |[[code]](https://github.com/JetAstra/SDAR-VL)![](https://img.shields.io/github/stars/JetAstra/SDAR-VL.svg?style=social) |arXiv|
|2025.10| Inference Stage |[**Lumina-DiMOO**] Lumina-DiMOO: An Omni Diffusion Large Language Model for Multi-Modal Generation and Understanding (@Shanghai AI Lab)| [[pdf]](https://arxiv.org/pdf/2510.06308) |[[code]](https://github.com/Alpha-VLLM/Lumina-DiMOO)![](https://img.shields.io/github/stars/Alpha-VLLM/Lumina-DiMOO.svg?style=social) |arXiv|
|2025.11| Inference Stage |[**D3ToM**] D3ToM: Decider-Guided Dynamic Token Merging for Accelerating Diffusion MLLMs (@SJTU)| [[pdf]](https://arxiv.org/pdf/2511.12280) |[[code]](https://github.com/bcmi/D3ToM-Diffusion-MLLM)![](https://img.shields.io/github/stars/bcmi/D3ToM-Diffusion-MLLM.svg?style=social) |arXiv|
|2025.11| Inference Stage |[**Token-Pruning**] A Comprehensive Study on Visual Token Redundancy for Discrete Diffusion-based Multimodal Large Language Models (@NTU)| [[pdf]](https://arxiv.org/pdf/2511.15098) | |arXiv|
|2025.12| Inference Stage |[**Sparse-LaViDa**] Sparse-LaViDa: Sparse Multimodal Discrete Diffusion Language Models (@Adobe)| [[pdf]](https://arxiv.org/pdf/2512.14008) | |arXiv|


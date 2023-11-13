# Awesome Large Multimodal Models
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository is a collection of useful things about **Large Multimodal Models (LMMs)**. 

Stars, suggestions, and contributions are all welcome.

## Contents
- [Awesome Large Multimodal Models](#awesome-large-multimodal-models)
  - [Contents](#contents)
  - [Papers](#papers)
    - [Survey / Understanding / Analysis](#survey--understanding--analysis)
    - [Foundation Models](#foundation-models)
    - [Instruction Tuning](#instruction-tuning)
    - [Reinforcement Learning with Human Feedback (RLHF)](#reinforcement-learning-with-human-feedback-rlhf)
    - [Capability Expansion](#capability-expansion)
    - [Capability Promotion](#capability-promotion)
      - [Hallucination Correction](#hallucination-correction)
  - [Datasets](#datasets)
    - [Datasets of Instruction Tuning](#datasets-of-instruction-tuning)
    - [Datasets of Reinforcement Learning with Human Feedback (RLHF)](#datasets-of-reinforcement-learning-with-human-feedback-rlhf)
    - [Datasets of Evaluation](#datasets-of-evaluation)

## Papers

### Survey / Understanding / Analysis

> Papers on the survey, understanding, and analysis of LMMs.

| submit_date | research_perspective | paper | publication_venue | project_code |
| --- | --- | --- | --- | --- |
| 2023-10-25 | **evaluation of GPT-4V** | [An Early Evaluation of GPT-4V(ision)](https://arxiv.org/abs/2310.16534) | arXiv 2023 | - |
| 2023-10-25 | **OCR of GPT-4V** | [Exploring OCR Capabilities of GPT-4V(ision) : A Quantitative and In-depth Evaluation](https://arxiv.org/abs/2310.16809) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/SCUT-DLVCLab/GPT-4V_OCR.svg?style=social&label=Star) |
| 2023-10-17 | **visual grounding of GPT-4V** | [Set-of-Mark Prompting Unleashes Extraordinary Visual Grounding in GPT-4V](https://arxiv.org/abs/2310.11441) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/microsoft/SoM.svg?style=social&label=Star) |
| 2023-10-13 | **visual encoder of LMMs** | [From CLIP to DINO: Visual Encoders Shout in Multi-Modal Large Language Models](https://arxiv.org/abs/2310.08825) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/YuchenLiu98/COMM.svg?style=social&label=Star) |
| 2023-09-29 | **evaluation of GPT-4V** | [The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)](https://arxiv.org/abs/2309.17421) | arXiv 2023 | - |
| 2023-09-18 | **scaling of instruction tuning** | [An Empirical Study of Scaling Instruction-Tuned Large Multimodal Models](https://arxiv.org/abs/2309.09958) | arXiv 2023 | - |
| 2023-06-23 | **survey on LMMs** | [A Survey on Multimodal Large Language Models](https://arxiv.org/abs/2306.13549) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) | 


### Foundation Models

> Papers on training LMMs from scratch.

| submit_date | model_name | paper | publication_venue | project_code
| --- | --- | --- | --- | --- |
| 2023-11-10 | **Florence-2** | [Florence-2: Advancing a Unified Representation for a Variety of Vision Tasks](https://arxiv.org/abs/2311.06242) | arXiv 2023 | - |
| 2023-11-07 | **mPLUG-Owl2** | [mPLUG-Owl2: Revolutionizing Multi-modal Large Language Model with Modality Collaboration](https://arxiv.org/abs/2311.04257) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star)<br/>[demo](https://modelscope.cn/studios/damo/mPLUG-Owl2/summary) |
| 2023-10-13 | **PaLI-3** | [PaLI-3 Vision Language Models: Smaller, Faster, Stronger](https://arxiv.org/abs/2310.09199) | arXiv 2023 | - |
| 2023-09-25 | **GPT-4V** | [GPT-4V(ision) system card](https://openai.com/research/gpt-4v-system-card?ref=www.chatgpt-vision.com)  | OpenAI 2023 | - |
| 2023-08-24 | **Qwen-VL** | [Qwen-VL: A Versatile Vision-Language Model for Understanding, Localization, Text Reading, and Beyond](https://arxiv.org/abs/2308.12966) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/QwenLM/Qwen-VL.svg?style=social&label=Star)<br/>[demo](https://modelscope.cn/studios/qwen/Qwen-VL-Chat-Demo/summary) |
| 2023-08-02 | **OpenFlamingo** | [OpenFlamingo: An Open-Source Framework for Training Large Autoregressive Vision-Language Models](https://arxiv.org/abs/2308.01390) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/mlfoundations/open_flamingo.svg?style=social&label=Star)<br/>[demo](https://huggingface.co/spaces/openflamingo/OpenFlamingo) |
| 2023-05-29 | **PaLI-X** | [PaLI-X: On Scaling up a Multilingual Vision and Language Model](https://arxiv.org/abs/2305.18565) | arXiv 2023 | - |
| 2023-04-27 | **mPLUG-Owl** | [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://arxiv.org/abs/2304.14178) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star)<br/>[demo](https://huggingface.co/spaces/MAGAer13/mPLUG-Owl) |
| 2023-03-15 | **GPT-4** | [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) | arXiv 2023 | - |
| 2022-09-14 | **PaLI** | [PaLI: A Jointly-Scaled Multilingual Language-Image Model](https://arxiv.org/abs/2209.06794) | ICLR 2023 | - |
| 2022-04-29 | **Flamingo** | [Flamingo: A Visual Language Model for Few-Shot Learning](https://arxiv.org/abs/2204.14198) | NeurIPS 2022 | - |
| 2022-01-28 | **BLIP** | [BLIP: Bootstrapping Language-Image Pre-training for Unified Vision-Language Understanding and Generation](https://arxiv.org/abs/2201.12086) | ICML 2022 | ![Star](https://img.shields.io/github/stars/salesforce/BLIP.svg?style=social&label=Star)<br/>[demo](https://huggingface.co/spaces/Salesforce/BLIP) |
| 2021-11-22 | **Florence** | [Florence: A New Foundation Model for Computer Vision](https://arxiv.org/abs/2111.11432) | arXiv 2021 | - |

### Instruction Tuning

> Papers on improving LMMs through instruction tuning.

| submit_date | model_name | paper | publication_venue | project_code|
| --- | --- | --- | --- | --- |
| 2023-10-14 | **MiniGPT-v2** | [MiniGPT-v2: large language model as a unified interface for vision-language multi-task learning](https://arxiv.org/abs/2310.09478) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)<br/>[demo](https://minigpt-v2.github.io/) |
| 2023-10-13 | **COMM** | [From CLIP to DINO: Visual Encoders Shout in Multi-Modal Large Language Models](https://arxiv.org/abs/2310.08825) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/YuchenLiu98/COMM.svg?style=social&label=Star) |
| 2023-10-5 | **LLaVA-1.5** | [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)<br/>[demo](https://llava.hliu.cc/) |
| 2023-09-29 | **DeepSpeed-VisualChat** | [DeepSpeed-VisualChat: Multi-Round Multi-Image Interleave Chat via Multi-Modal Causal Attention](https://arxiv.org/abs/2309.14327) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/microsoft/DeepSpeedExamples.svg?style=social&label=Star) |
| 2023-04-20 | **MiniGPT-4** | [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/abs/2304.10592) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star)<br/>[demo](https://huggingface.co/spaces/Vision-CAIR/minigpt4)
| 2023-04-17 |**LLaVA** | [Visual Instruction Tuning](https://browse.arxiv.org/abs/2304.08485) | NeurIPS 2023 | ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star)<br/>[demo](https://llava.hliu.cc/) |

### Reinforcement Learning with Human Feedback (RLHF)

> Papers on LMM alignment through RLHF.

| submit_date | model_name | paper | publication_venue | project_code|
| --- | --- | --- | --- | --- |
| 2023-09-25 | **LLaVA-RLHF** | [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2309.14525) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star)<br/>[demo](http://pitt.lti.cs.cmu.edu:7890/) |

### Capability Expansion

> Papers on expanding capabilities of LMMs, such as segmentation, detection, generation, and etc.

<!-- | submit_date | model_name | paper | publication_venue | project_code |
| --- | --- | --- | --- | --- |
| 2023-11-09 | **LLaVa-Plus** | [LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents](https://arxiv.org/abs/2311.05437) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star)<br/>[demo](https://llavaplus.ngrok.io/) |
| 2023-11-01 | **LLaVA-Interactive** | [LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing](https://arxiv.org/abs/2311.00571) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)<br/>[demo](https://llava-vl.github.io/llava-interactive/) | -->

| submit_date | model_name | paper | project_code |
| --- | --- | --- | --- |
| 2023-11-09 | **LLaVa-Plus** | [LLaVA-Plus: Learning to Use Tools for Creating Multimodal Agents](https://arxiv.org/abs/2311.05437)&nbsp;&nbsp;[arXiv 2023] | ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Plus-Codebase.svg?style=social&label=Star)<br/>[demo](https://llavaplus.ngrok.io/) |
| 2023-11-01 | **LLaVA-Interactive** | [LLaVA-Interactive: An All-in-One Demo for Image Chat, Segmentation, Generation and Editing](https://arxiv.org/abs/2311.00571)&nbsp;&nbsp;[arXiv 2023] | ![Star](https://img.shields.io/github/stars/LLaVA-VL/LLaVA-Interactive-Demo.svg?style=social&label=Star)<br/>[demo](https://llava-vl.github.io/llava-interactive/) |

### Capability Promotion

> Papers on improving capabilities of LMMs like hallucination correction.

#### Hallucination Correction

| submit_date | model_name | paper | publication_venue | project_code |
| --- | --- | --- | --- | --- |
| 2023-10-24 | **Woodpecker** | [Woodpecker: Hallucination Correction for Multimodal Large Language Models](https://arxiv.org/abs/2310.16045) | arXiv 2023 | ![Star](https://img.shields.io/github/stars/BradyFU/Woodpecker.svg?style=social&label=Star)<br/>[demo](https://42976740ac53ddbe7d.gradio.live/) |


## Datasets

### Datasets of Instruction Tuning

| submit_date | dataset | paper | publication_venue | describe |
| --- | --- | --- | --- | --- |
| 2023-04-20 | **cc_sbu_align** [link](https://huggingface.co/datasets/Vision-CAIR/cc_sbu_align) | [paper](https://arxiv.org/abs/2304.10592) | arXiv 2023 | high-quality, well-aligned dataset |
| 2023-04-17 | **LLaVA-Instruct-150K** [link](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K) | [paper](https://browse.arxiv.org/abs/2304.08485) | NeurIPS 2023 | instruction-following dataset |

### Datasets of Reinforcement Learning with Human Feedback (RLHF)

| submit_date | dataset | paper | publication_venue | describe |
| --- | --- | --- | --- | --- |
| 2023-09-25 | **LLaVA-SFT-122K** [link](https://huggingface.co/datasets/shengs/LLaVA-SFT-122K), **LLaVA-Human-Preference-10K** [link](https://huggingface.co/datasets/zhiqings/LLaVA-Human-Preference-10K) | [paper](https://arxiv.org/abs/2309.14525) | arXiv 2023 | factually augment using captions |

### Datasets of Evaluation

| submit_date | dataset | paper | publication_venue | describe |
| --- | --- | --- | --- | --- |
| 2023-09-25 | **MMHal-Bench** [link](https://huggingface.co/datasets/Shengcao1006/MMHal-Bench) | [paper](https://arxiv.org/abs/2309.14525) | arXiv 2023 | focus on hallucination evaluation |
| 2023-04-27 | **OwlEval** [link](https://github.com/X-PLUG/mPLUG-Owl/tree/main/OwlEval) | [paper](https://arxiv.org/abs/2304.14178) | arXiv 2023 | evaluate a variety of model capabilities |
# Awesome Large Multimodal Models
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

This repository is a collection of useful things about **Large Multimodal Models (LMMs)**. 

Stars, suggestions, and contributions are all welcome.

## Contents
- [Awesome Large Multimodal Models](#awesome-large-multimodal-models)
  - [Contents](#contents)
  - [Papers](#papers)
    - [Survey](#survey)
    - [Understanding and Analysis](#understanding-and-analysis)
    - [Foundation Models](#foundation-models)
    - [Instruction Tuning](#instruction-tuning)
    - [Reinforcement Learning with Human Feedback (RLHF)](#reinforcement-learning-with-human-feedback-rlhf)
  - [Datasets](#datasets)
    - [Datasets of Instruction Tuning](#datasets-of-instruction-tuning)
    - [Datasets of Reinforcement Learning with Human Feedback (RLHF)](#datasets-of-reinforcement-learning-with-human-feedback-rlhf)
    - [Datasets of Evaluation](#datasets-of-evaluation)
  - [Acknowledgement](#acknowledgement)

## Papers

### Survey

| submit_date | paper | publication | code | else |
| --- | --- | --- | --- | --- |
| 2023-06-23 | [A Survey on Multimodal Large Language Models](https://arxiv.org/abs/2306.13549) | arXiv_2023 | ![Star](https://img.shields.io/github/stars/BradyFU/Awesome-Multimodal-Large-Language-Models.svg?style=social&label=Star) | - |

### Understanding and Analysis

| submit_date | paper | publication | code | else |
| --- | --- | --- | --- | --- |
| 2023-09-29 | [The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)](https://arxiv.org/abs/2309.17421) | arXiv_2023 | - | - |
| 2023-09-18 |[An Empirical Study of Scaling Instruction-Tuned Large Multimodal Models](https://arxiv.org/abs/2309.09958) | arXiv_2023 | - | - |

### Foundation Models

| submit_date | paper | publication | code | else |
| --- | --- | --- | --- | --- |
| 2023-09-25 | [**GPT-4V**] [GPT-4V(ision) system card](https://openai.com/research/gpt-4v-system-card?ref=www.chatgpt-vision.com)  | OpenAI_2023 | - | - |
| 2023-03-15 | [ **GPT-4** ] [GPT-4 Technical Report](https://arxiv.org/abs/2303.08774) | arXiv_2023 | - | - |

### Instruction Tuning

| submit_date | paper | publication | code | else |
| --- | --- | --- | --- | --- |
| 2023-10-5 | [**LLaVA-1.5**] [Improved Baselines with Visual Instruction Tuning](https://arxiv.org/abs/2310.03744) | arXiv_2023 | ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star) | [demo](https://llava.hliu.cc/) |
| 2023-04-27 | [**mPLUG-Owl**] [mPLUG-Owl: Modularization Empowers Large Language Models with Multimodality](https://arxiv.org/abs/2304.14178) | arXiv_2023 | ![Star](https://img.shields.io/github/stars/X-PLUG/mPLUG-Owl.svg?style=social&label=Star) | [demo](https://huggingface.co/spaces/MAGAer13/mPLUG-Owl) |
| 2023-04-20 | [**MiniGPT-4**] [MiniGPT-4: Enhancing Vision-Language Understanding with Advanced Large Language Models](https://arxiv.org/abs/2304.10592) | arXiv_2023 | ![Star](https://img.shields.io/github/stars/Vision-CAIR/MiniGPT-4.svg?style=social&label=Star) | [demo](https://huggingface.co/spaces/Vision-CAIR/minigpt4) 
| 2023-04-17 | [**LLaVA**] [Visual Instruction Tuning](https://browse.arxiv.org/abs/2304.08485) | NeurIPS_2023 | ![Star](https://img.shields.io/github/stars/haotian-liu/LLaVA.svg?style=social&label=Star) | [demo](https://llava.hliu.cc/) |

### Reinforcement Learning with Human Feedback (RLHF)

| submit_date | paper | publication | code | else |
| --- | --- | --- | --- | --- |
| 2023-09-25 | [**LLaVA-RLHF**] [Aligning Large Multimodal Models with Factually Augmented RLHF](https://arxiv.org/abs/2309.14525) | arXiv_2023 | ![Star](https://img.shields.io/github/stars/llava-rlhf/LLaVA-RLHF.svg?style=social&label=Star) | [demo](http://pitt.lti.cs.cmu.edu:7890/) |

<!-- ### Multi-Modal In-Context Learning -->

<!-- ### Multi-Modal Chain-of-Thought -->

<!-- ### LLM-Driven Visual Reasoning -->

<!-- ### Evaluation -->

<!-- ### Others -->

## Datasets

### Datasets of Instruction Tuning

| submit_date | dataset | paper | publication | describe |
| --- | --- | --- | --- | --- |
| 2023-04-20 | [**cc_sbu_align**] [link](https://huggingface.co/datasets/Vision-CAIR/cc_sbu_align) | [paper](https://arxiv.org/abs/2304.10592) | arXiv_2023 | high-quality, well-aligned dataset |
| 2023-04-17 | [**LLaVA-Instruct-150K**] [link](https://huggingface.co/datasets/liuhaotian/LLaVA-Instruct-150K) | [paper](https://browse.arxiv.org/abs/2304.08485) | NeurIPS_2023 | instruction-following dataset |

### Datasets of Reinforcement Learning with Human Feedback (RLHF)

| submit_date | dataset | paper | publication | describe |
| --- | --- | --- | --- | --- |
| 2023-09-25 | [**LLaVA-SFT-122K**] [link](https://huggingface.co/datasets/shengs/LLaVA-SFT-122K), [**LLaVA-Human-Preference-10K**] [link](https://huggingface.co/datasets/zhiqings/LLaVA-Human-Preference-10K) | [paper](https://arxiv.org/abs/2309.14525) | arXiv_2023 | factually augment using captions |

### Datasets of Evaluation

| submit_date | dataset | paper | publication | describe |
| --- | --- | --- | --- | --- |
| 2023-09-25 | [**MMHal-Bench**] [link](https://huggingface.co/datasets/Shengcao1006/MMHal-Bench) | [paper](https://arxiv.org/abs/2309.14525) | arXiv_2023 | focus on hallucination evaluation |
| 2023-04-27 | [**OwlEval**] [link](https://github.com/X-PLUG/mPLUG-Owl/tree/main/OwlEval) | [paper](https://arxiv.org/abs/2304.14178) | arXiv_2023 | evaluate a variety of model capabilities |

## Acknowledgement

The framework is designed with reference to [Awesome-Multimodal-Large-Language-Models](https://github.com/BradyFU/Awesome-Multimodal-Large-Language-Models).
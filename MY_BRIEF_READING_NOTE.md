# My Brief Reading Notes

## Contents
- [My Brief Reading Notes](#my-brief-reading-notes)
  - [Contents](#contents)
  - [\[2023-10-05\] Improved Baselines with Visual Instruction Tuning (LLaVA-1.5)](#2023-10-05-improved-baselines-with-visual-instruction-tuning-llava-15)
  - [\[2023-09-29\] The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)](#2023-09-29-the-dawn-of-lmms-preliminary-explorations-with-gpt-4vision)

<!-- ## [xxxx-xx-xx] Templete

***Publication:***

***Authors:***

***Affiliations:***

***Summary:***

***Model:***

***Method:***

***Data:***

***Observations:*** -->


## [2023-10-05] Improved Baselines with Visual Instruction Tuning (LLaVA-1.5)

***Publication:*** arXiv 2023

***Authors:*** Haotian Liu, Chunyuan Li, Yuheng Li, Yong Jae Lee

***Affiliations:*** University of Wisconsin-Madison, Microsoft Research

***Summary:***

Several strategies to improve the performance of LLaVA.

***Model:***

1. Language model: LLaMA-7B or LLaMA-13B
2. Vision model: CLIP-ViT-L-336px
3. Vision-language connector: two-layer MLP

***Method:***

Improve over LLaVA:
1. Append "Answer the question using a single word or phrase" when prompting short answers.
2. Replace the linear projection with a two-layer MLP.
3. Add academic task oriented VQA data.
4. Scale up model to 13B.

***Data:***

665K image-text pairs, including LLaVA, ShareGPT, and some VQA datasets.

***Observations:***

LLaVA-1.5 achieves the best across 11 out of 12 benchmarks with the simplest architecture, academic compute and pubic datasets, and yields a fully-reproducible and affordable baseline. 

## [2023-09-29] The Dawn of LMMs: Preliminary Explorations with GPT-4V(ision)

***Publication:*** arXiv 2023

***Authors:*** Zhengyuan Yang, Linjie Li, Kevin Lin, Jianfeng Wang, Chung-Ching Lin, Zicheng Liu, Lijuan Wang

***Affiliations:*** Microsoft Corporation

***Summary:*** To deepen the understanding of large multimodal models (LMMs) by analyzing GPT-4V(ision). 

***Observations:***

- support flexible inputs
  - text-only inputs
  - a single image-text pair or a single image 
  - flexible interleaved image-text inputs
- support flexible working modes
  - text prompts
    - follow constrained prompt well, e.g., "return in the following JSON format {"class":xxx, "name": xxx}"
    - prefer condition prompt, e.g., "you are an expert in counting things, ..."
  - follow visual referring prompts well
    - understand prompts in different modes of visual pointing
  - follow flexible visual + text prompts well
  - in-context learning ability needs to be improved
    - prefer sufficient examples
- good quality and genericity
  - describe image well
    - celebrity recognition
    - landmark recognition
    - food recognition
    - medical image understanding
    - logo recognition
    - scene understanding
    - counterfactual examples
  - perform well in object localization, counting, and dense captioning
    - object counting and localization are more difficult
  - multimodal knowledge and commonsense
    - joke and meme
    - science and knowledge
    - multimodal commonsense
  - perfom well in scene text, table, chart, and document reasoning
    - scene text recognition
    - visual math reasoning
    - chart understanding and reasoning
    - table understanding and reasoning
    - document understanding
  - multilingual multimodal understanding
  - coding capability with vision
  - multi-image sequencing
  - video understanding
    - temporal ordering
    - temporal anticipation
    - temporal localization and reasoning
  - visual referring prompting for grounded temporal understanding
  - abstract visual reasoning
    - abstract visual stimuli
    - discovery and association of parts and objects
  - IQ and EQ test
- promising future directions
  - spot the difference
  - industry defect detection
  - safety inspection
  - medical, e.g., radiology report generation
  - auto insurance
  - customized captioner
  - image generation assistant
  - embodied agent
  - GUI navigation
    - web browsing
    - online shopping
    - notification understanding
    - watching videos
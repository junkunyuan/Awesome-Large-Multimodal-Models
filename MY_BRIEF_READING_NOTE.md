# My Brief Reading Notes

## Contents
- [My Brief Reading Notes](#my-brief-reading-notes)
  - [Contents](#contents)
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
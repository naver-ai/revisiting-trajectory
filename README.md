# Revisiting Complete Reasoning Traces for Post-Training

**Jaehui Hwang<sup>†</sup>, Sangdoo Yun, Byeongho Heo, Dongyoon Han<sup>†</sup>**

NAVER AI Lab († Corresponding authors)

[Paper (coming soon)] &nbsp;·&nbsp; [Project Page (coming soon)]

> This is the official repository of **"Revisiting Complete Reasoning Traces for Post-Training"**.
>
> **EMNLP 2026 Findings**



## Abstract

Large language models (LLMs) are often post-trained on pre-collected reasoning trajectories to improve their reasoning capability. Such trajectories tend to be long due to complex, interwoven paths, which often include detours on the path toward the answer. However, it has been underexplored whether LLMs indeed benefit from learning complete trajectories, particularly under supervised fine-tuning (SFT). Starting from our pilot study, we find that full trajectories provide only limited benefit, while partial trajectories are effective even under heavy truncation. We analyze redundancy in reasoning trajectories through attention-based analyses and controlled token-removal studies, both of which show that intermediate tokens contribute minimally to final reasoning quality. This suggests that avoiding redundant information may allow LLMs to internally infer coherent alternatives by inferring missing steps from their internal knowledge, given known trajectory endpoints. Furthermore, we show that training LLMs using endpoints leads to consistent changes in reasoning behavior, and that it also benefits post-training methods based on reinforcement learning or distillation, highlighting the need to revisit complete reasoning traces.

## Release

The paper and project page links will be released soon.

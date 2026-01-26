---
layout: project_page
permalink: /
title: Compositional Image Synthesis with Inference-Time Scaling
authors: Minsuk Ji, Sanghyeok Lee, Namhyuk Ahn
affiliations: Inha Univer
paper: https://arxiv.org/abs/2510.24133
code: https://github.com/gcl-inha/ReFocus?tab=readme-ov-file
---

## Abstract
Despite their impressive realism, modern text-to-image models still struggle with compositionality, often failing to render accurate object counts, attributes, and spatial relations. To address this challenge, we present a training-free framework that combines an object-centric approach with self-refinement to improve layout faithfulness while preserving aesthetic quality. Specifically, we leverage large language models (LLMs) to synthesize explicit layouts from input prompts, and we inject these layouts into the image generation process, where a object-centric vision-language model (VLM) judge reranks multiple candidates to select the most prompt-aligned outcome iteratively. By unifying explicit layout-grounding with self-refine-based inference-time scaling, our framework achieves stronger scene alignment with prompts compared to recent text-to-image models.

---

## Method

| ![ReFocus pipeline](static/image/pipeline.png) |
|:--:|
| Figure 1: Overview of ReFocus. |

---

## Experimental Results

| ![Quantitative results table](static/image/table.png) |
|:--:|
| Table 1: Quantitative comparison (higher is better). |

| ![Qualitative results](static/image/qual.png) |
|:--:|
| Figure 2: Qualitative results. |

---

## Citation
```bibtex
@article{turing1936computable,
  title={On computable numbers, with an application to the Entscheidungsproblem},
  author={Turing, Alan Mathison},
  journal={Journal of Mathematics},
  volume={58},
  number={345-363},
  pages={5},
  year={1936}
}

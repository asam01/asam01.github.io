---
title: "Efficient Finetuning for Dimensional Speech Emotion Recognition in the Age of Transformers"
collection: publications
category: conferences
permalink: https://ieeexplore.ieee.org/abstract/document/10889878/
excerpt: 'Accurate speech emotion recognition is essential for developing human-facing systems. Recent advancements have included finetuning large, pretrained transformer models like Wav2Vec 2.0. However, the finetuning process requires substantial computational resources, including high-memory GPUs and significant processing time. As the demand for accurate emotion recognition continues to grow, efficient finetuning approaches are needed to reduce the computational burden. Our study focuses on dimensional emotion recognition, predicting attributes such as activation (calm to excited) and valence (negative to positive). We present various finetuning techniques, including full finetuning, partial finetuning of transformer layers, finetuning with mixed precision, partial finetuning with caching, and low-rank adaptation (LoRA) on the Wav2Vec 2.0 base model. We find that partial finetuning with mixed precision achieves performance comparable to full finetuning while increasing training speed by 67%. Caching intermediate representations further boosts efficiency, yielding an 88% speedup and a 71% reduction in learnable parameters. We recommend finetuning the final three transformer layers in mixed precision to balance performance and training efficiency, and adding intermediate representation caching for optimal speed with minimal performance trade-offs. These findings lower the barriers to finetuning speech emotion recognition systems, making accurate emotion recognition more accessible to a broader range of researchers and practitioners.'
date: 2025-04-01
venue: 'IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP)'
authors:
  - name: Aneesha Sampath*
    me: true
  - name: James Tavernor*
  - name: Emily Mower Provost
# slidesurl: 'https://academicpages.github.io/files/slides3.pdf'
# paperurl: 'https://academicpages.github.io/files/paper3.pdf'
# citation: 'Your Name, You. (2015). &quot;Paper Title Number 3.&quot; <i>Journal 1</i>. 1(3).'
---

The contents above will be part of a list of publications, if the user clicks the link for the publication than the contents of section will be rendered as a full page, allowing you to provide more information about the paper for the reader. When publications are displayed as a single page, the contents of the above "citation" field will automatically be included below this section in a smaller font.

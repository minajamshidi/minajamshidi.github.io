---
title: "Beyond Attention Heatmaps: How to Get Better Explanations for Multiple Instance Learning Models in Histopathology"
collection: publications
permalink: /publication/2026-paper-xmil-number-9
excerpt: ' <b>M. Jamshidi Idaji*</b>, J.Hense *, et al.'
date: 2026-03-01
venue: 'arxiv'
---

Citation: <b>M. Jamshidi Idaji*</b>, J. Hense*, Tom Neuhäuser, Augustin Krause, Yanqing Luo, Oliver Eberle, Thomas Schnake, Laure Ciernik, Farnoush Rezaei Jafari, Reza Vahidimajd, Jonas Dippel, Christoph Walz, Frederick Klauschen, Andreas Mock, Klaus-Robert Müller 2026, "Beyond Attention Heatmaps: How to Get Better Explanations for Multiple Instance Learning Models in Histopathology
", arxiv. DOI: [10.48550/arXiv.2603.08328](https://doi.org/10.48550/arXiv.2603.08328), <b>*=equal contribution</b>

* The paper is accessible through [arxiv](https://arxiv.org/abs/2603.08328).

* You can download all the codes via [Github](https://github.com/bifold-pathomics/xMIL/tree/xmil-journal).


<b>Summary</b>: Multiple instance learning (MIL) has enabled substantial progress in computational histopathology, where a large amount of patches from gigapixel whole slide images are aggregated into slide-level predictions. Heatmaps are widely used to validate MIL models and to discover tissue biomarkers. Yet, the validity of these heatmaps has barely been investigated. In this work, we introduce a general framework for evaluating the quality of MIL heatmaps without requiring additional labels. We conduct a large-scale benchmark experiment to assess six explanation methods across histopathology task types (classification, regression, survival), MIL model architectures (Attention-, Transformer-, Mamba-based), and patch encoder backbones (UNI2, Virchow2). Our results show that explanation quality mostly depends on MIL model architecture and task type, with perturbation ("Single"), layer-wise relevance propagation (LRP), and integrated gradients (IG) consistently outperforming attention-based and gradient-based saliency heatmaps, which often fail to reflect model decision mechanisms. We further demonstrate the advanced capabilities of the best-performing explanation methods: (i) We provide a proof-of-concept that MIL heatmaps of a bulk gene expression prediction model can be correlated with spatial transcriptomics for biological validation, and (ii) showcase the discovery of distinct model strategies for predicting human papillomavirus (HPV) infection from head and neck cancer slides. Our work highlights the importance of validating MIL heatmaps and establishes that improved explainability can enable more reliable model validation and yield biological insights, making a case for a broader adoption of explainable AI in digital pathology. 

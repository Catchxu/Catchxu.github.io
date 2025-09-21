---
title: "Multimodal Anomalous Tissue Region Detection Enhanced with Spatial Transcriptomics"
excerpt: "<em>MEATRD</em> is a multimodal anomaly detection method that integrates histology image and Spatial Transcriptomics gene expression data. <br/><img src='/images/MEATRD.png' width='60%'><br/><br/>"
collection: portfolios
---

<div align=center>
<img src='/images/MEATRD.png' width='100%'>
</div>
<br/>

The detection of anomalous tissue regions (ATRs) within affected tissues is crucial in clinical diagnosis and pathological studies. Conventional automated ATR detection methods, primarily based on histology images alone, falter in cases where ATRs and normal tissues have subtle visual differences. The recent spatial transcriptomics (ST) technology profiles gene expressions across tissue regions,
offering a molecular perspective for detecting ATRs. Yet, there is a dearth of ATR detection methods that effectively harness complementary information from both histology images and ST. To address this gap, we propose MEATRD, a novel ATR detection method that integrates histology image and ST data. MEATRD is trained to reconstruct image patches and gene expression profiles of normal tissue spots (inliers) from their multimodal embeddings, followed by learning a one-class classification AD model based on latent multimodal reconstruction errors. This strategy harmonizes the strengths of reconstruction-based and one-class classification approaches. At the heart of MEATRD is an innovative masked graph dual-attention transformer (MGDAT) network, which not only facilitates cross-modality and cross-node information sharing but also addresses the model over-generalization issue commonly seen in reconstruction-based AD methods. Extensive evaluations across eight real ST datasets reveal MEATRD’s superior performance in ATR detection, surpassing various state-of-the-art AD methods. Remarkably, MEATRD also proves adept at discerning ATRs that only show slight visual deviations from normal tissues.

This paper has been accepted by AAAI 2025. 

ArXiv: <https://arxiv.org/abs/2412.10659>

GitHub: <https://github.com/wqlzuel/MEATRD>
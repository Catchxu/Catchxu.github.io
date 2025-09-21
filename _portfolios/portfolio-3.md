---
title: "Detecting anomalous anatomic regions in spatial transcriptomics with STANDS"
excerpt: "<em>STANDS</em> is a GAN-based multi-task deep learning framework, which can detect and dissect anomalous tissue domains (DDATD) with Spatial Transcriptomics or scRNA-seq. <br/><img src='/images/DDATD.png' width='60%'><br/><br/>"
collection: portfolios
---

The accurate detection of anomalous anatomic regions, followed by their dissection into biologically heterogeneous subdomains across multiple tissue slices, is of paramount importance in clinical diagnostics, targeted therapies and biomedical research. This procedure, which we refer to as Detection and Dissection of Anomalous Tissue Domains (DDATD), serves as the first and foremost step in a comprehensive analysis of tissues harvested from affected individuals for revealing population-level and individual-specific factors (e.g., pathogenic cell types) associated with disease developments.

<div align=center>
<img src='/images/DDATD.png' width='80%'>
</div>

Thus, we introduce STANDS, an innovative framework built on a suite of specialized Generative Adversarial Networks (GANs) for seamlessly integrating the three tasks of DDATD. The framework consists of three components.

<i>Component I (C1)</i> trains a GAN model on the reference dataset, learning to reconstruct normal spots from their multimodal representations of both spatial transcriptomics data and associated histology image. Subsequently, the model is applied on the target datasets to identify anomalous spots as those with unexpectedly large reconstruction deviances, namely anomaly scores.

<i>Component II (C2)</i> aims at diminishing the non-biological variations (e.g. batch effects) among anomalies via aligning target datasets in a common space. It employs two cooperative GAN models to identify pairs of reference and target spots that share similar biological contents, based on which the target datasets are aligned to the reference data space via “style-transfer”.

<i>Component III (C3)</i> fuses the embeddings and reconstruction residuals of aligned anomalous spots to serve as inputs to an iterative clustering algorithm which groups anomalies into distinct subtypes.

<div align=center>
<img src='/images/STANDS.png' width='80%'>
</div>

This paper has been accepted by Nature Communications. 

Paper: <https://www.nature.com/articles/s41467-024-52445-9>

GitHub: <https://github.com/Catchxu/STANDS>

Website: <https://catchxu.github.io/STANDS/>
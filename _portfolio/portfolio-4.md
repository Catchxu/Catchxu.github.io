---
title: "Detecting and Dissecting Anomalous Anatomic Regions in Spatial Transcriptomics with STANDS"
excerpt: "<em>STANDS</em> is a GAN-based multi-task deep learning framework, which can detect and dissect anomalous tissue domains (DDATD) with Spatial Transcriptomics or scRNA-seq. <br/><br/><img src='/images/DDATD.png' width='60%'>"
collection: portfolio
---

We proposed STANDS, a GAN-based multi-task deep learning framework that can simultaneously combine multimodal information (single-cell transcriptome, spatial transcriptome, and tissue images) in order to diagnose anomalous regions and perform heterogeneity analysis to discover subtypes of anomalous regions. Meanwhile, Spatial Grouping Discrepancy (SGD), an evaluation metric applicable to the task of abnormal subtype detection, is also proposed for the first time, bridging the gap in the field.

Comparative experiments involving 27 multimodal datasets of different individuals and organizations, and 14 baseline methods demonstrated that STANDS, a multi-task learning framework, outperforms existing methods in tasks such as anomaly detection, batch effect correction, and anomaly subtypes identification.

We designed and write the web pages [STANDS](https://catchxu.github.io/STANDS/) used to present the main features of STANDS, API documentation, and tutorials.

<br/>
<div align=center>
<img src='/images/DDATD.png' width='70%'>
</div>
<br/>
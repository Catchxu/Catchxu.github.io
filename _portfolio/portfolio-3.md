---
title: "Domain Adaptive and Fine-grained Anomaly Detection for Single-cell Sequencing Data and Beyond"
excerpt: "<em>ACSleuth</em> is a GAN-based generative model for domain adaptive and fine-grained anomaly detection in the single-cell/tabular data. <br/><img src='/images/ACSleuth.png' width='60%'><br/><br/>"
collection: portfolio
---

Fined-grained anomalous cell detection from affected tissues is critical for clinical diagnosis and pathological research. Single-cell sequencing data provide unprecedented opportunities for this task. However, current anomaly detection methods struggle to handle domain shifts prevalent in multi-sample and multi-domain single-cell sequencing data, leading to suboptimal performance. Moreover, these methods fall short of distinguishing anomalous cells into pathologically distinct subtypes. In response, we propose ACSleuth, a novel, reconstruction deviation-guided generative framework that integrates the detection, domain adaptation, and fine-grained annotating of anomalous cells into a methodologically cohesive workflow. Notably, we present the first theoretical analysis of using reconstruction deviations output by generative models for anomaly detection in lieu of domain shifts. This analysis informs us to develop a novel and superior maximum mean discrepancy-based anomaly scorer in ACSleuth. Extensive benchmarks over various single-cell data and other types of tabular data demonstrate ACSleuth's superiority over the state-of-the-art methods in identifying and subtyping anomalies in multi-sample and multi-domain contexts.

This paper has been accepted by IJCAI 2024. 

ArXiv: <https://arxiv.org/abs/2404.17454>

GitHub: <https://github.com/Catchxu/ACSleuth>

<br/>
<div align=center>
<img src='/images/ACSleuth.png' width='80%'>
</div>
<br/>
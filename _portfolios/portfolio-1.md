---
title: "Causality-Induced Positional Encoding for Transformer-Based Representation Learning of Non-Sequential Features"
excerpt: "<em>CAPE</em> is a novel positional encoding that identifies underlying causal structure over non-sequential features to improve the performance of transformer-based models. <br/><img src='/images/nonseq.png' width='80%'><br/><br/>"
collection: portfolios
---

<br/>
<div align=center>
<img src='/images/nonseq.png' width='100%'>
</div>
<br/>

Positional encoding is essential for supplementing transformer with positional information of tokens. Existing positional encoding methods demand predefined token/feature order, rendering them unsuitable for real-world data with non-sequential yet causally-related features. To address this limitation, we propose CAPE, a novel method that identifies underlying causal structure over non-sequential features as a weighted directed acyclic graph (DAG) using generalized structural equation modeling. The DAG is then embedded in hyperbolic space where its geometric structure is well-preserved using a hyperboloid model-based approach that effectively captures two important causal graph properties (causal strength & causal specificity). This step yields causality-aware positional encodings for the features, which are converted into their rotary form for integrating with transformer's self-attention mechanism. Theoretical analysis reveals that CAPE-generated rotary positional encodings possess three valuable properties for enhanced self-attention, including causal distance-induced attenuation, causal generality-induced attenuation, and robustness to positional disturbances. We evaluate CAPE over both synthetic and real-word datasets, empirically demonstrating its theoretical properties and effectiveness in enhancing transformer for data with non-sequential features.

<br/>
<div align=center>
<img src='/images/dilemma.png' width='80%'>
</div>
<br/>

This paper has been accepted by NeurIPS 2025. 

ArXiv: TBD

GitHub: <https://github.com/Catchxu/CAPE>
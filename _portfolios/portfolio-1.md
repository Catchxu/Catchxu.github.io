---
title: "Series Anomaly Inference with Nonlinear Markov to Circumvent Walking a Tightrope"
excerpt: "<em>ANIM</em> is a novel probabilistic module based on Nonlinear Markov for the unsupervised time series anomaly inference. <br/><img src='/images/dilemma.png' width='80%'><br/><br/>"
collection: portfolios
---

In the time series anomaly detection (TSAD), current methods often learn representations to differentiate anomalies from normal samples. However, state-of-the-art (SOTA) representation learning frameworks often face challenges in TSAD. One possible reason is that their overly powerful representations treat anomalies as generalizations of normal samples, resulting in inappropriately similar embeddings Therefore, it strikes a delicate but difficult balance in representation, like "Walking a Tightrope", avoiding both excessive strength and inadequacy. To circumvent this representation dilemma, we propose ANIM to guide representation backbones for TSAD. Initially, we fine-tune backbones to extract prototypes from normal series. We assume that the appearance of normal prototypes exhibits a relatively stable regularity, whereas sudden anomalies disrupt this regularity. ANIM infers anomalies by quantifying the extent to which regularity is disrupted through nonlinear Markov stationarity. Extensive benchmarks demonstrate ANIM's superiority over SOTA methods in TSAD.

<br/>
<div align=center>
<img src='/images/dilemma.png' width='100%'>
</div>
<br/>
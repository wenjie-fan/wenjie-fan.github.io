---
title: "Trajectory-Conditioned Modelling of Single-Cell Expression"
date:
description: ""
hidemeta: false
ShowReadingTime: false
slug: ""
draft: false
disableShare: true
cover:
    image: "differentiation.png"
    caption: ""
    alt: ""
    relative: true
weight: 1
---
<br/>
<figure>
    <img align="right" src="differentiation.png" style="width: 340px; margin: 0px 0px 5px 20px;" class="img_floats" />
</figure>


Foundation models for single-cell transcriptomics learn cell representations from millions of profiles, but are commonly pretrained on unordered cells and therefore do not explicitly condition on cell history. We introduce single-cell Transformer-iN-Transformer (scTNT), which conditions gene-expression reconstruction on inferred trajectories, represented here as ordered cell sequences. scTNT combines a frozen reduced-layer scGPT autoencoder with a trainable decoder-only transformer over sequences of latent cell embeddings and is trained by masked gene-expression reconstruction. On a CD8 T-cell exhaustion dataset with optimal transport-derived cell sequences, scTNT improves masked reconstruction relative to the scGPT baseline and outperforms alternative sequence backbones under controlled evaluations. We further propose a gradient-based gene-history attribution pipeline and apply TRRUST regulon enrichment to generate hypotheses about context-associated regulatory programs.
<br/> <br/>
[**ICLR workshop 2026**](https://drive.google.com/file/d/1FzGvaS7rTAN3KOOIxyCeFbbsJQF-l9xq/view?usp=drive_link) &nbsp; &nbsp;
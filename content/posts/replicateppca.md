---
title: "Probabilistic Principal Component Analysis for Replicated Data in Proteomics"
date: 2023-09-28
description: ""
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
ShowReadingTime: false
description: ""
slug: ""
draft: false # 是否为草稿
disableShare: true # 底部不显示分享栏
cover:
    image: "img/emPPCA.pdf" #图片路径：posts/tech/123/123.png
    caption: "" #图片底部描述
    alt: ""
    relative: false
weight: 5
---
<br/>
<figure>
    <img align="right" src="emPPCA.pdf" style="width: 340px; margin: 0px 0px 5px 20px;" class="img_floats" />
<figure>

Principal component analysis (PCA) is frequently used for the visualization and unsupervised clustering of mass spectrometry (MS) proteomics data. However, there is no intuitive method to handle missing values, and the intricate structure of experimental design is often neglected. A typical example is data from biological experiments with replicate structure, which displays both variations and correlations among replicates, and suffers from incomplete observations. Probabilistic principal component analysis (PPCA) recovers missing values soundly within a probabilistic framework, yet it still overlooks the replicate-wise variations. 

In this study, we extend PPCA to be conscious of the replicated model for MS data with replicated structures and possibly broader. We present  two distinct inference approaches: one focuses on the likelihood model by the Expectation-Maximization (EM) algorithm, while the other lies in the Bayesian framework employing the Markov chain Monte Carlo (MCMC) method. Our findings indicate that both approaches yield more nuanced analyses, some aspects of which have previously been ignored by researchers. The likelihood-centric approach hints replicates that may be unsuitable for PCA and tackles the challenge of missing values. In contrast, the Bayesian approach provides insightful visualizations, quantifies clustering uncertainty, and determines the risk-minimizing clustering rule.
<br/> <br/>
[**Report**](https://drive.google.com/file/d/1EsX1yQZZN1iXGRjbkQOIjj3y7H-gD_zo/view?usp=share_link) &nbsp; &nbsp;
[**Github**](https://github.com/wenjie-fan/replicatePPCA) &nbsp; &nbsp; 
<br/> <br/>
<!-- **Vignettes:** &nbsp; [EM algorithm](replicateppca/emPPCA_examples.html) &nbsp; [MCMC]() -->

---

This is an on-going summer project supervised by [Dr. Oliver Crook](https://olivercrook.co.uk) from the University of Oxford.

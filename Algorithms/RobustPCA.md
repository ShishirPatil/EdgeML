---
layout: page
title: RobustPCA
category: Algorithms
---

**Downloads:**
<span class="publ-linklist">
    [<a href="{{ site.baseurl}}{{ site.customurl.rpca.pdf }}">PDF</a>]
    [<a href="{{ site.baseurl}}{{ site.customurl.rpca.matlabcode }}">Matlab ZIP</a>]
    [<a href="{{ site.customurl.rpca.code }}">More Code</a>]
    [<a href="{{ site.baseurl}}{{ site.customurl.rpca.poster }}">Poster</a>]
    [<a href="{{ site.baseurl}}{{ site.customurl.rpca.coltslides }}">COLT 2017 Slides</a>]
</span>


Robust Principal Components Analysis (Robust PCA) is a general-purpose anomaly detection algorithm that can be deployed in tiny iot devices.


PCA-based outlier or anomaly detection algorithm is an unsupervised learning algorithm, that tries to model the “normal” class by a linear subspace. At prediction time, the points that are “distant” from the subspace are detected as anomalies. In many cases, training with anomalies (outliers) in the (unlabeled) training data might lead to learning wrong detection models. Robust PCA iteratively learns the linear subspace as well as identifies the anomalies in the training data - thereby removing the detected anomalies, and retraining with each iteration. This makes the method suited for anomaly detection in iot scenarios where labeling comes at the cost of expert’s time and labor - no pre-processing of training data is required. 


The model size is controlled by a single hyperparameter ‘k’ (dimension of the linear subspace). The prediction time is very fast, similar to the case of [ProtoNN]({{ site.baseurl }}/Algorithms/ProtoNN/). 

Refer to our [paper]({{ site.baseurl }}{{ site.customurl.rpca.pdf }}), where precise theoretical guarantees are developed; the iterative algorithm provably converges to the true subspace of the normal class, despite the presence of a constant fraction of outliers (anomalies) in the training data.

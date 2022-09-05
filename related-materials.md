---
layout: default
title: Related materials
description: Including presentation slides, demos, source code, related papers, etc.
---

# General information about River

`River` is a Python library for online machine learning. With `River`, as opposed to the batch setting, we encourage a different approach, which is to continuously learn a stream of data. This would allow any massive dataset to be learned, even when it does not fit in the memory. It has a lot of use cases, ranging from time series forecasting, spam filtering, recommender systems, CTR prediction and IoT applications.

The clustering module of `River` is currently the most complete among all open-source projects, with not only the highest number of already-available clustering algorithms, but also with the large number of internal and external metrics that supports online learning contexts.

The currently available clustering algorithms include

* Incremental KMeans
* CluStream
* DenStream
* DBSTREAM
* STREAMKMeans
* evoStream

Additionally, with **20** internal validation metrics and **18** external validation metrics, River is currently the package with the highest number of metrics offered for data stream continuous or incremental validation.

* **Internal validation metrics**: Cohesion, SSB, SSW, Separation, Silhouette, Ball-Hall, CH, Hartigan, WB, Xie-Beni, Xu, (Root) Mean Squared Standard Deviation, R-Squared, I Index, Davies-Bouldin, Partition Separation, Dunn’s indices 43 and 53, SD Validation Index, and Bayesian Information Criterion.

* **External validation metrics**: Completeness, Homogeneity, VBeta, (Adjusted, Expected, Normalized) Mutual Information, Q0 and Q2, Fowlkes-Mallows, Markedness, Informedness, Matthews Correlation Coefficient, (Adjusted) Rand Index, Purity, Prevalence Threshold, and Sorensen-Dice index.

The viewers may also be interested to visit the repositories of two packages that are merged to become `River`, including `scikit-multiflow` and `creme`:

* `scikit-multiflow`: [https://scikit-multiflow.github.io/](https://scikit-multiflow.github.io/)
* `creme`: [https://github.com/MaxHalford/creme](https://github.com/MaxHalford/creme)

In order to cite `scikit-multiflow` or `creme`, you can refer to the associated JMLR paper and the Github repository, as follows:

```bibtex
@article{skmultiflow,
  author  = {Jacob Montiel and Jesse Read and Albert Bifet and Talel Abdessalem},
  title   = {Scikit-Multiflow: A Multi-output Streaming Framework },
  journal = {Journal of Machine Learning Research},
  year    = {2018},
  volume  = {19},
  number  = {72},
  pages   = {1-5},
  url     = {http://jmlr.org/papers/v19/18-251.html}
}
```

and

```bibtex
@software{creme,
  title = {creme, a Python library for online machine learning},
  author = {Halford, Max and Bolmier, Geoffrey and Sourty, Raphael and Vaysse, Robin and Zouitine, Adil},
  url = {https://github.com/MaxHalford/creme},
  version = {0.6.1},
  date = {2020-06-10},
  year = {2019}
}
```

# Source code and demos

The source code for the demo of `River` can be found [here](https://github.com/hoanganhngo610/river-clustering-demo-2022).

The benchmarking of `River` clustering algorithms are conducted locally, and can be executed using [this repository](https://github.com/hoanganhngo610/river-clustering-benchmark).

# Presentation slides and videos

The complete slide deck of Part 1 and 2 of the tutorial, in PDF, can be found [here](https://bit.ly/KDD2022-Tutorial-OnlineClustering-Slides).

The complete video of the on-site tutorial will be made available by the organizers, tentatively when the conference is officially over.

In September 2022, Hoang-Anh Ngo also gave an invited talk in a seminar organized at LIAAD, INSEC TEC, University of Porto related to `River` and the clustering module. The slides of the talk can be found [here](https://drive.google.com/file/d/1RWXdTxGzW6CkvY3TmBZuO8F8rIItUR_K/view?usp=sharing), or [within the GitHub repository for the demo of `River`](https://github.com/hoanganhngo610/river-clustering-demo-2022/tree/master/slides/INESC%20TEC%20-%20Hoang-Anh%20Ngo%20-%20September%202022).

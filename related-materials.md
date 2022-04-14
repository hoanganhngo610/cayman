---
layout: default
title: Related materials
description: Including presentation slides, demos, source code, related papers, etc.
---

# General information about River

`River` is a Python library for online machine learning. With `River`, as opposed to the batch setting, we encourage a different approach, which is to continuously learn a stream of data. This would allow any massive dataset to be learned, even when it does not fit in the memory. It has a lot of use cases, ranging from time series forecasting, spam filtering, recommender systems, CTR prediction and IoT applications.

The clustering module of `River` is currently the most complete among all open-source projects, with not only the highest number of already-available clustering algorithms, but also with the large number of internal and external metrics that supports online learning contexts.

The currentl available clustering algorithms include

* Online KMeans
* CluStream
* DenStream
* DBSTREAM
* STREAMKMeans
* EvoStream

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
  title = {{creme}, a {P}ython library for online machine learning},
  author = {Halford, Max and Bolmier, Geoffrey and Sourty, Raphael and Vaysse, Robin and Zouitine, Adil},
  url = {https://github.com/MaxHalford/creme},
  version = {0.6.1},
  date = {2020-06-10},
  year = {2019}
}
```

# Source code and demos

TBA

# Presentation slides and videos

TBA

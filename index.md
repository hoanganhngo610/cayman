---
layout: default
title: "Online clustering: algorithms, evaluation, metrics, application and benchmarking using River"
description: Tutorial presented at the 26<sup>th</sup> Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD), May 16<sup>th</sup> - 19<sup>th</sup>, 2022, Chengdu, China.
---

# Abstract

Online clustering algorithms play a critical role in data science, especially with the advantages regarding time, memory usage and complexity, while maintaining a high performance compared to traditional clustering methods.

This tutorial serves, first, as a survey on online machine learning and, in particular, data stream clustering methods.

This introduction will be then put into the context with River, a go-to Python library merged between `Creme` and `scikit-multiflow`. We propose applications and settings for benchmarking, using real-world problems and datasets.

# Outline including a short summary of every section

The outline of the tutorial, which expands along the period of **3 hours** (half-day), is as follows:

* Introduction to data stream (online) machine learning (approximately **45 minutes**)

  - What is online machine learning, and why do we need online machine learning?
  - Differences, advantages and disadvantages of online machine learning compared to batch/traditional machine learning.
  - Introduction to River, a hands-on Python library for machine learning merged from `Creme` and `scikit-multiflow`.
  - Practical applications of `River` in classification, concept drifts, implementation of estimators, etc. and displaying real-time results using `holoviews`.

* Online clustering algorithms and evaluation metrics (approximately **1 hour and 30 minutes**):

  - A literature survey on existing clustering algorithms, the general concepts and their evolution.
  - Primary differences between clustering and classification evaluation metrics, which might lead to wrong interpretation of final results.
  - Real-world applications of online clustering algorithms and evaluation metrics in practical problems.

* Use cases and benchmarking (approximately **45 minutes**):

  - Comparison between online and traditional/batch clustering algorithms.
  - Motivation, setting and system requirements for conducting benchmarking.
  - Tutorial on benchmarking using the `River` package and the associated available `git` repository and `terminal`.

## Introduction to data stream (online) machine learning

This part is intended to provide the motivation and necessity of online stream learning. As a matter of fact, traditional machine learning methods can not deal with an extremely large amount of data with limited resources and time constrains, which means that there is an urgent need for specific data stream machine learning methods. Besides providing insights on advantages and disadvantages of online machine learning, we will also provide an introduction to `River`, a Python library aimed to become a go-to toolkit for this purpose.

## A literature survey on online clustering algorithms and metrics

This part will first start with an extensive survey on online clustering algorithms. First, we will start with the development from the first algorithms (`BIRCH`/`CluStream`), then to the evolution based on different approaches. These approaches include either distance-based, grid-based, model-based or projected, two-phase, type of time windows (damped, sliding, landmark or pyramidal), or the use of medoids/centroids.

Moreover, one aspect of online clustering algorithms that are usually neglected are the usages of validation metrics. Usually, classification metrics are used as a replacement, which may lead to the wrong interpretation of final results and the choice of hyperparameters. As such, in this part, we will also focus on the construction of these metrics, and also how to apply them in analyzing clustering algorithms' performances when put into practice.

## Practical applications and benchmarking using the clustering module of River

The final part serves as a practical tutorial on the usage of River and the associated clustering module in real-life problems. First, online clustering algorithms will be put into comparison with traditional/batch methods in terms of performance, memory and time usage to prove that although online methods takes up less resources, they have the ability to obtain a similar accuracy. Then, the setting, system requirement and method of benchmarking and choosing the appropriate hyperparameter sets are discussed.

# Specific goals and objectives

The specific goal of this tutorial is to act as a literature survey and an introduction to online clustering algorithms, metrics and their recent advances through `River` - an existing Python online machine learning library. Through that, it also provides all necessary tools and techniques, as a framework, to apply online clustering algorithms in real-world scenarios and to develop practical applications in line with its theoretical background.

* Present an introduction on online machine learning and its advantages compared to traditional/batch machine learning.
* Provide core theoretical background to understand how clustering algorithms and methods are designed.
* Introduce `River` as a new, go-to library/framework for building online machine learning algorithms.
* Give practical examples and insights on how to use River in real-life applications and benchmarking.
* Discuss the past, present, future challenges and future challenges and how researchers have been tackling those in their algorithms' development.

# Expected background of the audience

The target audience of this tutorial include any researchers and practitioners with interests on machine learning for big data/evolving data streams and/or IoT applications. There will be no special requirement on previous experience on data stream learning; however, either experience with traditional machine learning concepts and frameworks (`scikit-learn`, `keras`, `pytorch`, etc.) or previous interactions with `scikit-multiflow`, `Creme` or `River` (the merge of the two) is a plus.

# Related materials

For all related materials, including presentation slides, demos, source code, related papers and any other piece of information, please visit [this page](./related-materials.html).

# References

1. Jacob Montiel, Max Halford, Saulo Martiello Mastelini, Geoffrey Bolmier, Raphael Sourty, Robin Vaysse, Adil Zouitine, Heitor Murilo Gomes, Jesse Read, Talel Abdessalem, and Albert Bifet. 2021. River: machine learning for streaming data in Python. *Journal of Machine Learning Research* 22 (April 2021), 1–8. [http://jmlr.org/papers/v22/20-1380.html](http://jmlr.org/papers/v22/20-1380.html)

1. Matthias Carnein and Heike Trautmann. 2019. Optimizing Data Stream Representation: An Extensive Survey on Stream Clustering Algorithms. *Business & Information Systems Engineering* 61 (2019), 277–297. [https://doi.org/10.1007/s12599-019-00576-5](https://doi.org/10.1007/s12599-019-00576-5)

1. Mohammed Ghesmoune, Mustapha Lebbah, and Hanene Azzag. 2016. State-of-the-art on clustering data streams. *Big Data Analytics* 1, 1 (2016), 13. [https://doi.org/10.1186/s41044-016-0011-3](https://doi.org/10.1186/s41044-016-0011-3)

1. Amineh Amini, Teh Ying Wah, and Hadi Saboohi. 2014. On Density-Based Data Streams Clustering Algorithms: A Survey. *Journal of Computer Science and Technology* 29, 1 (Jan. 2014), 116–141. [https://doi.org/10.1007/s11390-013-1416-3](https://doi.org/10.1007/s11390-013-1416-3)

1. Ali Javed, Byung Suk Lee, and Donna M. Rizzo. 2020. A benchmark study on time series clustering. *Machine Learning with Applications* 1 (Sept. 2020), 100001. [https://doi.org/10.1016/j.mlwa.2020.100001](https://doi.org/10.1016/j.mlwa.2020.100001)

1. Matthias Carnein, Assenmacher Dennis, and Heike Trautmann. 2017. An Empirical Comparison of Stream Clustering Algorithms. In *Proceedings of the Computing Frontiers Conference (CF’17)*. Association for Computing Machinery, New York, NY, USA, 361––366. [https://doi.org/10.1145/3075564.3078887](https://doi.org/10.1145/3075564.3078887)

1. Leonardo Enzo Brito Da Silva, Niklas Max Melton, and Donald C. Wunsch. 2020. Incremental Cluster Validity Indices for Online Learning of Hard Partitions: Extensions and Comparative Study. *IEEE Access* 8 (Jan. 2020), 22025–22047. [https://doi.org/10.1109/ACCESS.2020.2969849](https://doi.org/10.1109/ACCESS.2020.2969849)

1. Albert Bifet, Ricard Gavaldà, Geoff Holmes, and Bernhard Pfahringer. 2018. *Machine Learning for Data Streams: with Practical Examples in MOA*. The MIT Press, Cambridge, MA, USA. [https://doi.org/10.7551/mitpress/10654.001.0001](https://doi.org/10.7551/mitpress/10654.001.0001)

1. Max Halford, Geoffrey Bolmier, Raphael Sourty, Robin Vaysse, and Adil Zouitine. 2019. creme, a Python library for online machine learning. [https://github.com/MaxHalford/creme](https://github.com/MaxHalford/creme)

1. Jacob Montiel, Jesse Read, Albert Bifet, and Talel Abdessalem. 2018. Scikit-Multiflow: A Multi-output Streaming Framework. *Journal of Machine Learning Research* 19, 72 (2018), 1–5. [http://jmlr.org/papers/v19/18-251.html](http://jmlr.org/papers/v19/18-251.html)

1. Stratos Mansalis, Eirini Ntoutsi, Nikos Pelekis, and Yannis Theodoridis. 2018. An evaluation of data stream clustering algorithm. *Statistical Analysis and Data Mining: The ASA Data Science Journal* 11 (2018), 167–187. [https://doi.org/10.1002/sam.11380](https://doi.org/10.1002/sam.11380)

1. Charu C. Aggarwal, Jiawei Han, Jianyong Wang, and Phillip S. Yu. 2003. A Framework for Clustering Evolving Data Streams. *In Proceedings of the 29th International Conference on Very Large Data Bases - Volume 29* (Berlin, Germany) *(VLDB ’03)*. VLDB Endowment, Berlin, Germany, 81–92. [https://doi.org/10.5555/1315451.1315460](https://doi.org/10.5555/1315451.1315460)

1. Feng Cao, Martin Estert, Weining Qian, and Aoying Zhou. 2006. Density-Based Clustering over an Evolving Data Stream with Noise. In *Proceedings of the 2006 SIAM International Conference on Data Mining (SDM)*. Society for Industrial and Applied Mathematics (SIAM), Philadelphia, PA, USA, 328–339. [https://doi.org/10.1137/1.9781611972764.29](https://doi.org/10.1137/1.9781611972764.29)

1. Marcel R. Ackermann, Marcus Martens, Christoph Raupach, Kamil Swierkot, Christiane Lammersen, and Christian Sohler. 2012. StreamKM++: A Clustering Algorithm for Data Streams. *ACM J. Exp. Algorithmics* 17, Article 2.4 (May 2012), 30 pages. [https://doi.org/10.1145/2133803.2184450](https://doi.org/10.1145/2133803.2184450)

1. L. O’Callaghan, N. Mishra, A. Meyerson, S. Guha, and R. Motwani. 2002. Streaming-data algorithms for high-quality clustering. In *Proceedings 18th International Conference on Data Engineering*. IEEE, San Jose, CA, USA, 685–694. [https://doi.org/10.1109/ICDE.2002.994785](https://doi.org/10.1109/ICDE.2002.994785)

1. Michael Hashler and Matthew Bolaños. 2016. Clustering Data Streams Based on Shared Density between Micro-Clusters. *IEEE Transactions on Knowledge and Data Engineering* 28, 6 (2016), 1449–1461. [https://doi.org/10.1109/TKDE.2016.2522412](https://doi.org/10.1109/TKDE.2016.2522412)

1. Yixin Chen and Li Tu. 2007. Density-based clustering for real-time stream data. In *Proceedings of the 13th ACM SIGKKDD internaional conference on Knowledge discovery and data mining (KDD ’07)*. Association for Computing Machinery, New York, NY, USA, 133–142. [https://doi.org/10.1145/1281192.1281210](https://doi.org/10.1145/1281192.1281210)




This is a normal paragraph following a header. GitHub is a code hosting platform for version control and collaboration. It lets you and others work together on projects from anywhere.

## Header 2

> This is a blockquote following a header.
>
> When something is important enough, you do it even if the odds are not in your favor.

### Header 3

```js
// Javascript code with syntax highlighting.
var fun = function lang(l) {
  dateformat.i18n = require('./lang/' + l)
  return true;
}
```

```ruby
# Ruby code with syntax highlighting
GitHubPages::Dependencies.gems.each do |gem, version|
  s.add_dependency(gem, "= #{version}")
end
```

#### Header 4

*   This is an unordered list following a header.
*   This is an unordered list following a header.
*   This is an unordered list following a header.

##### Header 5

1.  This is an ordered list following a header.
2.  This is an ordered list following a header.
3.  This is an ordered list following a header.

###### Header 6

| head1        | head two          | three |
|:-------------|:------------------|:------|
| ok           | good swedish fish | nice  |
| out of stock | good and plenty   | nice  |
| ok           | good `oreos`      | hmm   |
| ok           | good `zoute` drop | yumm  |

### There's a horizontal rule below this.

* * *

### Here is an unordered list:

*   Item foo
*   Item bar
*   Item baz
*   Item zip

### And an ordered list:

1.  Item one
1.  Item two
1.  Item three
1.  Item four

### And a nested list:

- level 1 item
  - level 2 item
  - level 2 item
    - level 3 item
    - level 3 item
- level 1 item
  - level 2 item
  - level 2 item
  - level 2 item
- level 1 item
  - level 2 item
  - level 2 item
- level 1 item

### Small image

![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png)

### Large image

![Branching](https://guides.github.com/activities/hello-world/branching.png)


### Definition lists can be used with HTML syntax.

<dl>
<dt>Name</dt>
<dd>Godzilla</dd>
<dt>Born</dt>
<dd>1952</dd>
<dt>Birthplace</dt>
<dd>Japan</dd>
<dt>Color</dt>
<dd>Green</dd>
</dl>

```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```

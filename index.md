---
layout: default
title: "Online clustering: algorithms, evaluation, metrics, aplication and benchmarking using River"
description: Tutorial presented at the 26th Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD), May 16th - 19th, 2022, Chengdu, China.
---

# Abstract

Online clustering algorithms play a critical role in data science, especially with the advantages regarding time, memory usage and complexity, while maintaining a high performance compared to traditional clustering methods.

This tutorial serves, first, as a survey on online machine learning and, in particular, data stream clustering methods.

This introduction will be then put into the context with River, a go-to Python library merged between `Creme` and `scikit-multiflow`. We propose applications and settings for benchmarking, using real-world problems and datasets.

# Outline including a short summary of every section

# Specific goals and objectives

The specific goal of this tutorial is to act as a literature survey and an introduction to online clustering algorithms, metrics and their recent advances through `River` - an existing Python online machine learning library. Through that, it also provides all necessary tools and techniques, as a framework, to apply online clustering algorithms in real-world scenarios and to develop practical applications in line with its theoretical background.

* Present an introduction on online machine learning and its advantages compared to traditional/batch machine learning.
* Provide core theoretical background to understand how clustering algorithms and methods are designed.
* Introduce `River` as a new, go-to library/framework for building online machine learning algorithms.
* Give practical examples and insights on how to use River in real-life applications and benchmarking.
* Discuss the past, present, future challenges and future challenges and how researchers have been tackling those in their algorithms' development.

# Expected background of the audience

The target audience of this tutorial include any researchers and practitioners with interests on machine learning for big data/evolving data streams and/or IoT applications. There will be no special requirement on previous experience on data stream learning; however, either experience with traditional machine learning concepts and frameworks (`scikit-learn`, `keras`, `pytorch`, etc.) or previous interactions with `scikit-multiflow`, `Creme` or `River` (the merge of the two) is a plus.

# Header 1

[Link to another page](./another-page.html).

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

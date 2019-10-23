---
layout: post
---

> The workshop on Classifier Learning from Difficult Data is organized during the [International Conference on Computational Science ICCS 2020](https://www.iccs-meeting.org/iccs2020/) in Amsterdam, The Netherlands.

# About

Nowadays many practical decision task require to build models on the basis of data which included serious difficulties, as imbalanced class distributions, high number of classes, high-dimensional feature, small or extremely high number of learning examples, limited access to ground truth, data incompleteness, or data in motion, to enumerate only a few. Such characteristics may strongly deteriorate the final model performances. Therefore, the proposition of the new learning methods which can combat the mentioned above difficulties should be the focus of intense research.
The main aim of this workshop is to discuss the problems of data difficulties, to identify new issues, and to shape future directions for research.

# Topics of interest

- Learning from imbalanced data
- learning from data streams, including concept drift management
- learning with limited ground truth access
- learning from high dimensional data
- learning with a high number of classes
- learning from massive data, including instance and prototype selection
- learning on the basis of limited data sets, including one-shot learning
- learning from incomplete data
- case studies and real-world applications

# Key dates

| Milestone        | Date           |
| ------------- |:-------------:|
| Paper submission | 13 December 2019 |
| Notification of acceptance of papers | 24 January 2020|
| Camera-ready papers| 28 February 2020|
| Author registration| 24 January – 28 February 2020|
| Conference | 3-5 June 2020|


<!--
# Program

*To be announced.*
-->

<!--
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
-->

<!--
## Keynote speaker

<div class="picture">
  <img src="acano.jpg">
  <div>
  <h3>Alberto Cano</h3>
  <h5>High Performance Data Mining on GPUs, Hadoop, Spark, and beyond</h5>
  The ever-increasing dimensionality of data poses the main challenge to the scalability of data mining algorithms to run in reasonable time. Parallel and distributed architectures, particularly based on GPUs and the MapReduce model on Apache Hadoop or Spark, have become popular approaches to alleviate the prohibitive runtimes of machine learning algorithms on big data. Not only does the size of data increases the computational complexity but also the emergence of new data-level difficulties and calls for novel learning paradigms. Learning from imbalanced, high-dimensional, data streams with concept drift, or multi-label, to name a few, increase the complexity of algorithms to model such massive data accurately. Therefore, there is a need of new approaches to keep up with the increasing complexity and size of learning from difficult data. This talk reviews advances on the scalability of data mining in recent years and discusses the open issues and future lines of research.

  </div>
</div>

<div class='cleaner'></div>
-->

# Program committee

<ul>
{% assign sorted = (site.data.pc | sort: 'last') %}
{% for person in sorted %}
<li>
    {{ person.first }} {{person.last}}, <em>{{person.university}}, {{person.country}}</em>
</li>
{% endfor %}
</ul>


# Organization commitee

{% assign sorted = (site.data.oc) %}
{% for person in sorted %}
<div class="pictureoc">
  <img src="{{person.img}}.jpg">
  <div>
  {{ person.first }} {{person.last}}, <em>{{person.university}}, {{person.country}}</em>
  </div>
</div>
<div class='cleaner'></div>
{% endfor %}

<br><br>

<center>
<a href="https://kssk.pwr.edu.pl">
<img src="kssk.png">
</a>
</center>

<!--
---


Polar Bear supports GFM!
The following text has been taken from [this page](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet).

# H1
## H2
### H3
#### H4
##### H5
###### H6


Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~


1. First ordered list item
2. Another item
  * Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
  1. Ordered sub-list
4. And another item.

   Some text that should be aligned with the above item.

* Unordered list can use asterisks
- Or minuses
+ Or pluses


[I'm an inline-style link](https://www.google.com)

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com



Inline `code` has `back-ticks around` it.



```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```



Colons can be used to align columns.


The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3



> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
-->

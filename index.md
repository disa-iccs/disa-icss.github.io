---
layout: post
---

> The workshop on Computational methods for emerging problems in disinformation analysis is organized during the [International Conference on Computational Science ICCS 2020](https://www.iccs-meeting.org/iccs2020/) in Amsterdam, The Netherlands.

> The session will be technically endorsement by IEEE SMC TC on Big Data Computing http://www.ieeesmc.org/technical-activities/cybernetics/big-data-computing as well by SocialTruth project (Socialtruth.eu), which has received funding from the European Union’s Horizon 2020 research and innovation programme under grant agreement No. 825477.

# About

Information analysis is nowadays crucial for societies, single citizens in their everyday life (e.g. while travelling, shopping, browsing, communication etc.) as well for businesses and overall economy. The right to be informed is one of fundamental requirements allowing for taking right decisions in a small and large scale (e.g. elections).
However information spreading can be also used for disinformation. The problem of the fake news publication is not new and it already has been reported in ancient ages, but it has started having a huge impact especially on social media users or people watching media news (Internet, newspapers, tv etc.). Such false information should be detected as soon as possible to avoid its negative influence on the readers and in some cases on their decisions.

Another problem and emerging challenge is coming from using automated information analysis and decision support systems (based on Artificial Intelligence (AI) and Machine Learning (ML) advances) as black-box single truth providers. If those information analysis systems are misused, attacked or fooled, their results will also lead to (dis-) information.

The main aim of this workshop is to bring together researchers and scientists computational science who are pioneering (dis-)information analysis methods to discuss problems and solutions in this area, to identify new issues, and to shape future directions for research. Moreover, we invite prospective researchers to send papers concerning (dis-)information detection methods and architectures, explainability of information processing methods and decision support systems as well as their security.


# Topics of interest

+ detection fake news detection in social media
+ images and video manipulation recognition
+ architectural frameworks and design for fake news detection
+ learning how to detect the fake news in the presence of concept drift
+ learning how to detect the fake news with limited ground truth access and on the basis of limited data sets, including one-shot learning
+ feature selection and extraction methods for fake news detection
+ proposing how to compare and benchmark the fake news detectors
+ case studies and real-world applications
+ legal and societal aspects of fake news detection
+ data protection and GDPR in fake news detection challenge


# Key dates

| Milestone        | Date           |
| ------------- |:-------------:|
| Paper submission | 13 December 2019 |
| Notification of acceptance of papers | 24 January 2020|
| Camera-ready papers| 28 February 2020|
| Author registration| 24 January – 28 February 2020|
| Conference | 3-5 June 2020|

# Workshop chairs

<ul>
<li>
Prof. Michal Choras, UTP University of Science and Technology, Poland
e-mail: chorasm@utp.edu.pl
</li>
<li>
Dr. Konstantinos Demestichas
e-mail: cdemest@cn.ntua.gr
</li>
</ul>

# Program committee (tenatative)

<ul>
{% assign sorted = (site.data.pc | sort: 'last') %}
{% for person in sorted %}
<li>
    {{ person.first }} {{person.last}}, <em>{{person.university}}, {{person.country}}</em>
</li>
{% endfor %}
</ul>



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

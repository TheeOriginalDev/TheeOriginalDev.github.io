---
title: "What is Markdown?"
permalink: /projects/markdown/
date: 2020-01-04
excerpt: "A post featuring Markdown syntax and the use of Mathjax"
header:
  teaser: "/images/teaser/example.png"
mathjax: "true"
---

# H1 Heading

## H2 Heading

### H3 Heading

<p style="text-align: center;">Here's some basic ~~text~~.</p>

And here's some *italics*

Here's some **bold** text.

What about a [link](https://github.com/TheeOriginalDev)?

Here's a bulleted list:
* First item
+ Second item
- Third item

Here's a numbered list:
1. First
2. Second
3. Third

Python code block:
```python
    import numpy as np

    def test_function(x, y):
      z = np.sum(x,y)
      return z
```

R code block:
```r
library(tidyverse)
df <- read_csv("some_file.csv")
head(df)
```

Here's some inline code `x+y`

Here's an image:
<img src="{{ site.url }}{{ site.baseurl }}/images/markdownlearning/somedata.png" alt="Random Picture of some Data">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/markdownlearning/dashboard.jpg)

Here is a picture using the image url:
![alt text](https://cdn1.sph.harvard.edu/wp-content/uploads/sites/21/2018/07/fruitveg-454x313.jpeg "Fruits & Veggies")

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$

![alt]({{ site.url }}{{ site.baseurl }}/images/markdownlearning/giphy.gif)

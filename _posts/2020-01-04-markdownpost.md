---
title: "What is Markdown?"
date: 2020-01-04
tags: [Markdown, MD, fundamentals]
header:
  image: "/images/python_store/mystore.png"
excerpt: "Markdown Features, Adding Mathjax"
mathjax: "true"
---

# H1 Heading FEATURING "Markdown"

## H2 Heading

### H3 Heading

Here's some basic text.

And here's some *italics*

Here's some **bold** text.

What about a link?[link](https://github.com/TheeOriginalDev)

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
<img src="{{ site.url }}{{ site.baseurl }}/images/python_store/register.png" alt="Code for Python Store">

Here's another image using Kramdown:
![alt]({{ site.url }}{{ site.baseurl }}/images/python_store/register.png)

Here's some math:

$$z=x+y$$

You can also put it inline $$z=x+y$$

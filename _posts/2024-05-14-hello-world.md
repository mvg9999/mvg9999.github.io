---
layout: default 
title: "Hello World"
date: 2024-05-14
---

Hello, world! This is a simple Jekyll blog post with LaTeX.

This is a scratchpad to prove that both markdown and latex work. 

Here's some example latex, a basic convex optimization problem:

$$ \min_{x} f(x) $$

$$ \text{s.t. } g(x) \leq 0 $$

And now let's check inline latex: $\sum_{i=1}^n i^2 = \frac{n(n+1)(2n+1)}{6}$

Ok, now let's try some markdown. Here's a bullet list:

- Item 1
- Item 2
- Item 3

Here's a non-trivial code snippet:

```python
import numpy as np

x = np.linspace(0, 10, 100)
y = np.sin(x)

plt.plot(x, y)
plt.show()
```

Lastly, let's try to include an image:

![Image of Lucy]({{ site.url }}/assets/images/lucy.jpeg)


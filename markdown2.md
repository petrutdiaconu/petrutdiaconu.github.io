<script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>

![Text descriptiv imagine](https://metricop.com/cdn/shop/articles/trimble-total-station.jpg?v=1677673954&width=1100)

[HomePage](index.md)

# Elemente de Markdown - P2

## Inserarea codului de programre in Markdown si HTML

### Cod 'in linie'

**Markdown:**

Iata un fragment de cod scris pe aceeasi linie: `a = b**c`

**HTML:**

<code> a=b**c </code>

### Cod scris pe mai multe linii

**Markdown:**

```python
import pandas as pd
import numpy as np

a = 2
b = 3
```

**HTML:**

<pre>
import pandas as pd
import numpy as np

a = 2
b = 3
</pre>

## Inserarea elementelor evidentiate (blockquote)

> Acesta este un text evidentiat.

Acesta este un text ne-evidentiat.

**HMTL:**

<blockquote>
Acesta este un text evidentiat.
</blockquote>

## Avantajale HTML fata de Markdown

**Markdown**
![total station](images/mp.jpg)


**HTML:**

<img src=images/mp.jpg width=200px border=10px>

***

<hr size=2em>

<p> Acesta este un paragraf </p>

## Echivalentul unui link in HTML

[test link](https//:google.com)

<a src= "https//:google.com" alt="text link">

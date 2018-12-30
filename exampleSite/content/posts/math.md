---
title: "Rendering Math"
date: 2018-04-16
draft: false
categories: []
tags: ["HTML", "Markdown", "Math"]
include_math: true
---

## Inline math

To inline use `\$...\$`.

```
This formula $f(x) = x^2$ is an example.
```

This formula $f(x) = x^2$ is an example.

## Display math

To render math in display mode, use `\$\$...\$\$`.

```
$$
\frac{x^{2} + 1}{5} = 1 \\\\\
x^{2} = 5 - 1  \\\\\
x = \sqrt{4} \\\\\
x = \pm 2 \\\\\
$$
```

$$
\frac{x^{2} + 1}{5} = 1 \\\\\
x^{2} = 5 - 1  \\\\\
x = \sqrt{4} \\\\\
x = \pm 2 \\\\\
\\
x
$$

## Escaping the dollar sign

To escape the dollar sign, place a backslash in front of it.

```
\$
```

\$

---
layout: post
title: "Example: Writing Math Posts"
date: 2026-05-07
---

This is a sample post showing how math renders. Delete or replace it with your own work.

## Inline and Display Math

Inline math works with single dollar signs: the Cauchy-Schwarz inequality states that for $u, v \in \mathbb{R}^n$,

$$
\left| \sum_{i=1}^n u_i v_i \right|^2 \leq \left( \sum_{i=1}^n u_i^2 \right)\left( \sum_{i=1}^n v_i^2 \right).
$$

## A Slightly Longer Example

Let $(\mathcal{H}, \langle \cdot, \cdot \rangle)$ be a Hilbert space and $T : \mathcal{H} \to \mathcal{H}$ a bounded self-adjoint operator. The spectral theorem guarantees a projection-valued measure $E$ on $\mathbb{R}$ such that

$$
T = \int_{\sigma(T)} \lambda \, dE(\lambda),
$$

where $\sigma(T) \subset \mathbb{R}$ is the spectrum of $T$.

## Writing New Posts

Add a file to the `_posts/` directory with the naming convention

```
YYYY-MM-DD-your-title.md
```

and include the front matter at the top:

```
---
layout: post
title: "Your Title Here"
date: YYYY-MM-DD
---
```

Then write in Markdown with `$...$` for inline math and `$$...$$` for display math.

---
layout: post
date:   2018-04-17 12:00:00
title:  "Sparse reduced-rank regression for patch-seq"
excerpt_separator: <!--break-->
---

Schematic of the day:

![Sparse reduced-rank regression for exploratory visualization of single cell patch-seq recordings](/img/patch-seq-rrr.png)

$$\mathcal L = \lVert \mathbf Y - \mathbf X \mathbf W \mathbf V^\top\rVert^2 + \lambda_1 \sum_{i=1}^p\lVert \mathbf W_{i\cdot}\rVert_2 + \lambda_2 \lVert \mathbf W \rVert^2 \;\;\;\text{s.t.}\; \mathbf V^\top\mathbf V = \mathbf I.$$

See our preprint *Sparse reduced-rank regression for exploratory visualization of single cell patch-seq recordings* (<https://www.biorxiv.org/content/early/2018/04/16/302208>) for details. 

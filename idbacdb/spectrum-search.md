---
layout: default
title: Spectrum Search
parent: IDBacDB
nav_order: 1
---

### Spectrum Search Algorithm

The currently implementation of spectral searching is very simple:

Masses are split into bins of width 50 mass units over the range of 3000 - 20,000. 
Each spectrum is binary digitized into these bins and the [Jaccard similarity](https://en.wikipedia.org/wiki/Jaccard_index) is computed.
Score will range from 0 - 1. Only scores greater than 0.3 are returned.
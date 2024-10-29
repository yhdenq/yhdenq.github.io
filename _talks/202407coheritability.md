---
title: "Computationally efficient methods for estimating co-heritability of multivariate phenotypes using biobank data"
collection: talks
permalink: /talks/2024coheritability2
type: "Talk"
venue: "Joint Conference on Statistics and Data Science in China (JCSDS)"
date: 2023-07-16
location: "Kunming, China"
---

Slides not available

Biobank data provide a rich source for studying the coheritability of multiple disease phenotypes, which can provide information on shared genetic etiology. However, the large number and heterogeneous type of phenotypes (e.g., continuous, discrete, time-to-event) pose significant statistical and computational challenges for estimating coheritability. In this work, we propose a unified modeling framework with latent random effects that distinguish between genetic and family-shared environmental contributions to variation across multi-type phenotypes. To address computational challenges due to high-dimensional integrals, we develop a two-stage estimation procedure: first, we estimate the heritability for individual phenotype by maximizing its marginal likelihood; next, we estimate the coheritability between each pair of phenotypes using a pairwise pseudo-likelihood function. Our numerical approach involves, at most, five-dimensional integration, thus ensuring both computational efficiency and reliability even with a large number of phenotypes. We apply our method to analyze the heritability and coheritability of 290 phenotypes, including continuous, discrete and time-to-event types,  that are obtained from the UK Biobank. We find that a substantial number of phenotype pairs present statistically significant genetic coheritability.

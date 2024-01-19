# Introduction to Distance Sampling

**Analysis of Stratified Data**

**Outline Solutions**

Example analyses, which were used in getting these solutions, and which
are referred to below, are in the project file “Stratify solutions.dst”.

1.  Relevant results are in Analysis “Full geog stratification”.

The AICs are 127.90 for the southern stratum and 187.90 for the northern
stratum. Detection function model fits are adequate visually and by
goodness-of-fit test. Sample sizes are relatively small but not
alarmingly so. The southern stratum appears to have a much narrower
effective strip width.

2.  Relevant results are in Analysis “Pooled f(0)”.

The AIC for the pooled detection function fit is 318.72. The detection
function model fit is adequate visually and by goodness-of-fit test.
Because

318.72 \> (127.9+187.9=315.8)

estimation of separate detection function in each stratum is preferable.

3.  Relevant results are in Analysis “No stratification”.

The whale density estimate from the unstratified analysis is around 25%
larger than the corresponding estimates from 1. and 2. above. The reason
is that the survey design was geographically stratified, with less
survey effort in the north stratum, and this is being ignored in the
unstratified analysis.  
  
What is **not included in this project** are cluster sizes of the
observed minke whale groups (we didn’t want to clutter the analysis with
that detail). However, there is a bit of a story in geographic variation
in cluster sizes. Cluster densities are higher in the southern stratum,
but transects from both strata are being treated as if they are
representative of the whole survey region. This results in a positively
biased cluster density for the region as a whole. In addition, cluster
sizes are higher in the South stratum. The estimate of E(s) from the
unstratified analysis is a positively biased estimate of E(s) for the
North stratum and a negatively biased estimate of E(s) for the South
stratum. When it is applied to both strata, it results in a positively
biased estimate of whale abundance because the North stratum is much
larger and contains roughly twice as many whales as the south stratum.

> **Moral**: Don’t perform analyses without taking the survey design
> into account!

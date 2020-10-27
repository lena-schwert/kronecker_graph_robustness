# Analyzing the robustness of Kronecker graphs of different sizes when inducing different error mechanisms

## About the project

This university group project builds on Martin & Niemeyer (2019) who introduced the notion of robustness of different centrality measures (e.g. degree, PageRank) when errors (e.g. edges missing uniformly at random) are introduced to networks. This measure can then be used to determine how much a network is changed by the errors when considering a specific centrality measure.

Our project analyzed Kronecker graphs based on the Jazz and Dolphin networks of varying sizes to find out whether the robustness changes with the network size using the four different error mechanisms introduced by Martin & Niemeyer (2019). 

## Context of the project

This group project (see contributors) was conducted as part of the coursework of my Masters degree (Management & Data Science) in the summer term 2019. The task was to extend the Martin & Niemeyer (2019) paper by conducting the analysis described above.

## References

Martin, C. and P. Niemeyer (2019). Influence of measurement errors on networks: Estimating the robustness of centrality measures. Network Science 7.2, pp. 180-195

Implementation used for calculating the robustness by [crsqq/EstimatingCentralityRobustness](https://github.com/crsqq/EstimatingCentralityRobustness)

Implementation used for generating the Kronecker graphs: [kronfit](https://github.com/snap-stanford/snap/tree/master/examples/kronfit), [krongen](https://github.com/snap-stanford/snap/tree/master/examples/krongen)

![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)

# Computation of Large Spatial Datasets with the M function

  Increasing access to large geo-referenced datasets, coupled with the development of computing power, has encouraged the search for suitable spatial statistical tools.
  Distance-based methods have been extensively developed in several scientific fields to detect spatial concentration, dispersion or independence of entities at any distance and without any bias.
  Recently, Tidu et al. (2024) highlighted the qualities of Marcon and Puech's *M* function, a relative distance-based measure, and also expressed reservations about the computation time required.
  Herein, we propose a methodology that specifies the processing of large spatialized datasets with the *M* function using R software.
  The computational performance of *M* was conducted using two methods: (i) a precise evaluation of the computational time and memory requirements for geo-referenced data was conducted using the *dbmss* package in R via performance tests, and (ii) based on Tidu et al. (2024), we considered an approximation of the geographical positions of the entities.
  The deterioration extent of the *M* results was estimated and discussed as the gains it provides in computation time.
  We provided evidence that the individual location approximation generated information loss at substantially small distances, implying a trade-off between the smallest distance at which spatial interactions could be detected and computing performance. 
  The R code used in the article is given for the reproducibility of our results.

Formats:

- [HTML](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.html) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.html) 
- [PDF](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.pdf) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.pdf) 

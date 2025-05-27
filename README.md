![stability-wip](https://img.shields.io/badge/stability-work_in_progress-lightgrey.svg)

# On the computation of large spatial datasets with M

  Increasing access to large geo-referenced datasets, coupled with the development of computing power, has encouraged the search for suitable spatial statistic tools. 
  In this line, distance-based methods have been largely developed in many scientific fields to detect spatial concentration, dispersion or independence of entities at any distance and without bias. 
  In a recent article, Tidu et al. (2024) highlight the qualities of the *M* function (Marcon and Puech, 2010), a relative distance-based measure, but they also express reservations for the computation times required. 
  In our article, we propose a methodological work that seeks to specify the processing of large spatialised datasets with the *M* function by using R software. We appraise the computational performance of *M* into two ways. 
  At first, a precise evaluation of the computational time and memory requirements for geo-referenced data is carried out using the *dbmss* package in R by means of performance tests. 
  Then, as suggested by Tidu et al. (2024), we consider an approximation of the geographical positions of the entities. 
  The extent of the deterioration in the estimate of *M* is estimated and discussed, as are gains in computation time. 
  We give evidence that the individual location approximation generates information loss at small distances, implying a trade-off between the smallest distance at which spatial interactions can be detected and computing performance. 
  We recommend designing the analysis of large datasets taking it into account. 
  The R code used in the article is given for the reproducibility of our results

Formats:

- [HTML](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.html) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.html) 
- [PDF](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.pdf) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.pdf) 

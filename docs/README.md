# On the computation of large spatial datasets with M

  Increasing access to large individual geolocalised datasets, coupled with the development of computing power, has encouraged the search for suitable spatial statistic tools.
  In this line, distance-based methods have been largely developed in different scientific fields to detect spatial concentration, dispersion or independence of entities at any distance and without any bias. 
  In a recent article, Tidu et al. (2024) highlight the qualities of the *M* function [@Marcon2010], a relative distance-based measure.
  Tidu et al. (2024) also express reservations about *M* for the computation times required.
  In our article, we propose a methodological work that seeks to specify the processing of large spatialized datasets with the *M* function by using R software.
  Two avenues are being explored to determine the computational performance of *M*.
  A precise evaluation of the computational time and memory requirements for geolocalised data is at first carried out using the *dbmss* package in R [@Marcon2014] by means of performance tests. 
  Then, as suggested by Tidu et al. (2024), approximating the geographical positions of the entities analysed is considered.
  The extent of the deterioration in the estimate of *M* induced by this approach is estimated and discussed, as the gains in computation time made possible by the spatial approximation of locations.
  We give evidence that the individual location approximation generates information loss at small distances, implying a trade-off between the smallest distance at which spatial interactions can be detected and computing performance.
  We recommend designing the analysis of big datasets taking it into account.
  The R code is given for the reproducibility of our results.


Formats:

- [HTML](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.html) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.html) 
- [PDF](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.pdf) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.pdf) 

# On the computation of large spatial datasets with M

  Increasing access to large individual and spatial datasets, coupled with the development of computing power, has encouraged the search for suitable statistical tools to best analyse such data. 
  In a recent article published in this journal, @Tidu2023 highlight the qualities of the *M* function [@Marcon2010], a measure of spatial concentration in continuous space. 
  They also express reservations about the computation times required.
  Our methodological work seeks to specify the processing of large spatialized data sets with *M* using R software.
  Two avenues are being explored to determine the computational performance of *M*.
  Firstly, a precise evaluation of the computational time and memory requirements for geo-localised data is carried out using the dbmss package in R by means of performance tests. 
  Then, as suggested by @Tidu2023, we also consider the possibility of approximating the geographical positions of the entities analysed.
  The extent of the deterioration in the estimate of *M* that this approach creates can thus be estimated, as can the gains in computation time made possible by the spatial approximation of locations. 
  The complete R code is given for the reproducibility of the results.


Formats:

- [HTML](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.html) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.html) 
- [PDF](https://EricMarcon.github.io/MLargeDataSets/MLargeDataSets.pdf) with [appendix](https://EricMarcon.github.io/MLargeDataSets/Appendix.pdf) 

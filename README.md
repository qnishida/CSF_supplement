# A centroid single force catalog of P-wave microseisms

## Description
A centroid single force (CSF) catalog of P-wave microseism from 2004 to 2020. The locations and the CSFs were estimated by the auto-focussing method. We analyzed vertical components of Hi-net data from 0.1 to 0.25 Hz.

* Data: vertical components velocity meters of Hi-net 
* Frequency: 0.1-0.25 Hz
* Period: 2004 to 2020
* Centdoids were located approximately every 6 hours:
* The time of the catalog is in JST (= UT + 9h). We inferred CSF locations every 21904 s (about 6 hours), and the time of the catalog represents the starting time of the 6-hour window. 

<dl>
  <dt> The catalog in text format</dt><dd>catalog_0.1-0.25Hz_2004-2020_6hours.dat</dd>
  <dt> The catalog in pickle format</dt><dd>catalog_0.1-0.25Hz_2004-2020_6hours.pickle</dd>
</dl>

## Sample Codes

* Read_catalog_pickle.ipynb:  A sample script for reading the catalog in pickle format is available
* Test code of auto-focusing method for synthetic data
  * Array_test.ipynb: Test code of the auto-focusing method
  * stations.pickle: station locations for the synthetic test

## Reference
When you use this data, please cite the following reference.

* Nishida, K., & Takagi, R. (2022). A global centroid single force catalog of P-wave microseisms. Journal of Geophysical Research: Solid Earth, 127, e2021JB023484. https://doi.org/10.1029/2021JB023484

# Geostatistics Lessons Notebooks

Companion notebooks for [Geostatistics Lessons](https://geostatisticslessons.com),
prepared by lesson authors and contributors. Saved figures and results let you
browse each notebook directly on GitHub without running it.

## Lessons

Notebooks follow the [lesson catalog](https://geostatisticslessons.com/all):
grouped by primary topic, with titles alphabetized within each topic
(ignoring an initial “A”, “An”, or “The”). Topics without notebooks are omitted.

### Methodology

* An Application of Bayes Theorem to Geostatistical Mapping ([notebook](bayesmapping.ipynb) and [lesson](https://geostatisticslessons.com/lessons/bayesmapping)), Jared Deutsch and Clayton Deutsch, 2018
* The Nugget Effect ([notebook](nuggeteffect.ipynb) and [lesson](https://geostatisticslessons.com/lessons/nuggeteffect)), Eric Daniels and Diogo Silva, 2024

### Data Management

* Angle Specification ([notebook](anglespecification.ipynb) and [lesson](https://geostatisticslessons.com/lessons/anglespecification)), Ben Harding and Matthew Deutsch, 2025

### Data Transformation

* Transforming Data to a Gaussian Distribution ([notebook](gaussiantransform.ipynb) and [lesson](https://geostatisticslessons.com/lessons/normalscore)), Haoze Zhang, Ben Harding, and Ryan Barnett, 2025
* Trend Modeling and Modeling with a Trend ([notebook](trendmodeling.ipynb) and [lesson](https://geostatisticslessons.com/lessons/trendmodeling)), Sebastian Sanchez, Ben Harding, and Ryan Barnett, 2024

### Multivariate Statistics

* Cokriging with Unequally Sampled Data ([notebook](cokriging.ipynb) and [lesson](https://geostatisticslessons.com/lessons/cokrigingunequal)), Luis Davila and Ryan Barnett, 2025
* Multidimensional Scaling ([notebook](mds.ipynb) and [lesson](https://geostatisticslessons.com/lessons/mds)), Steven Mancell and Clayton Deutsch, 2019
* Projection Pursuit Multivariate Transform ([notebook](ppmt.ipynb) and [lesson](https://geostatisticslessons.com/lessons/ppmt)), Luis Davila and Ryan Barnett, 2025

### Variograms

* Calculation and Modeling of Variogram Anisotropy ([notebook](variogramanisotropy.ipynb) and [lesson](https://geostatisticslessons.com/lessons/variogramanisotropy)), Haoze Zhang, Luis Davila, and Ryan Barnett, 2025
* The Pairwise Relative Variogram ([notebook](pairwiserelative.ipynb) and [lesson](https://geostatisticslessons.com/lessons/pairwiserelative)), Haoze Zhang and Ryan Barnett, 2024

### Estimation

* Choosing the Discretization Level for Block Property Estimation ([notebook](blockdiscretization.ipynb) and [lesson](https://geostatisticslessons.com/lessons/discretization)), Haoze Zhang and Ryan Barnett, 2025
* Collocated Cokriging ([notebook](collocatedcokriging.ipynb) and [lesson](https://geostatisticslessons.com/lessons/collocatedcokriging)), Matthew Samson and Clayton Deutsch, 2020
* Introduction to Choosing a Kriging Plan ([notebook](introkrigingplan.ipynb) and [lesson](https://geostatisticslessons.com/lessons/introkrigingplan)), James Eke and Ryan Barnett, 2024

### Mining Applications

* Change of Support and the Volume Variance Relation ([notebook](changeofsupport.ipynb) and [lesson](https://geostatisticslessons.com/lessons/changeofsupport)), Haoze Zhang and Ryan Barnett, 2024

## Data and environment

Run notebooks from the repository root. Shared input files are in `data/`,
with lowercase filenames prefixed by the lesson name.

The notebooks were run with Python 3.12 and RMSP 1.18.2. Bayes mapping, MDS,
and collocated cokriging use open-source Python packages; the other notebooks
require licensed RMSP to rerun. Contact Resource Modeling Solutions Ltd for information on RMSP. Package versions are listed in
[`requirements.txt`](requirements.txt).

## License

The notebooks are distributed under the [MIT license](LICENSE).

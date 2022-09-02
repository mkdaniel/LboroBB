This zip file contains the following Jupyter Notebooks
- ExtractData.ipynb: contains routines for converting year long csv file of pyranometer readings and splitting in to per day files. Also contains example of how to clean the out of range weather field values
- BayesianBlock_v2.ipynb: calculate the Bayesian blocks for pyranometer day files and the clear atmosphere pvlib model simulations
- FitTurbidity.ipynb: examples of how to apply the method to fit Linke turbidity factor from Bayesian block change points of pyranometer measurements.
- [YYYY]-SunRiseSetTimes.txt: series of files containing sun rise and set times for days of the year. Needed for clipping the pyranometer day measurements.
in Data folder
-- 2018-06-26.csv - pyranometer measurements for a day
-- clear.txt: list of days with clearness index >0.85 in 2018
-- mixed.txt: list of days with 0.2 < clearness index < 0.85 in 2018
-- overcast.txt: list of days with clearness index <0.2 in 2018
-- Timeseries_52.762_-1.241_SA2_0deg_-179deg_2018_2018.csv: PVGIS daily (15m sampling) measurements for Loughborough in 2018


Michael Daniel <mkdaniel.loughborough@gmail.com> Sep. 2022
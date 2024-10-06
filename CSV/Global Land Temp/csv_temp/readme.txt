% This file contains a detailed summary of the changes in Earth's global average
% surface temperature estimated by combining the Berkeley Earth land-surface
% temperature field with a reinterpolated version of the HadSST ocean temperature 
% field.  
% The current citation for this dataset is: 
% 
%    Rohde, R. A. and Hausfather, Z.: The Berkeley Earth Land/Ocean Temperature
%    Record, Earth Syst. Sci. Data, 12, 3469�3479, 
%    https://doi.org/10.5194/essd-12-3469-2020, 2020.
% 
% The dataset differs slightly from the dataset as described in the citation as 
% HadSST3 has been replaced with the newer HadSST4, and associated interpolation 
% parameters have been refit accordingly.  No other changes in methods were needed 
% when moving to the new version of HadSST. 
% 
% Two versions of this average are reported.  These differ in how they treat 
% locations with sea ice.  In the first version, temperature anomalies in the 
% presence of sea ice are extrapolated from land-surface air temperature anomalies.  
% In the second version, temperature anomalies in the presence of sea ice are
% extrapolated from sea-surface water temperature anomalies (usually collected 
% from open water areas on the periphery of the sea ice).  For most of the 
% ocean, sea-surface temperatures are similar to near-surface air temperatures; 
% however, air temperatures above sea ice can differ substantially from the water 
% below the sea ice.  The air temperature version of this average shows larger 
% changes in the recent period, in part this is because water temperature changes 
% are limited by the freezing point of ocean water.  We believe that the use of air
% temperatures above sea ice provides a more natural means of describing changes in 
% Earth's surface temperature.  
% 
% The percent coverage of sea ice was taken from the HadISST v2 dataset and varies 
% by month and location.  In the typical month, between 3.5% and 5.5% of the 
% Earth's surface is covered with sea ice. For more information on the processing 
% and use of HadISST and HadSST refer to the description file for the combined 
% gridded data product. 
% 
% Temperatures are in Celsius and reported as anomalies 
% relative to the Jan 1951-Dec 1980 average. Uncertainties represent the 95% confidence 
% interval for statistical and spatial undersampling effects as well as ocean biases.
% 
% 
% The land analysis was run on 08-Jul-2024 10:18:28
% The ocean analysis was published on 16-Jun-2024 08:23:06
% 
% The land component is based on 40532 time series 
%   with 18975001 monthly data points
% 
% The ocean component is based on 474367961 instantaneous 
%   water temperature observations
%
% Estimated Jan 1951-Dec 1980 global mean temperature (C)
%   Using air temperature above sea ice:   14.089 +/- 0.039
%   Using water temperature below sea ice: 14.695 +/- 0.039
% 
% As Earth's land is not distributed symmetrically about the equator, there
% exists a mean seasonality to the global average temperature.  
% 
%   Using air temperature above sea ice:
% 
% Estimated Jan 1951-Dec 1980 monthly absolute temperature:
%      Jan   Feb   Mar   Apr   May   Jun   Jul   Aug   Sep   Oct   Nov   Dec
%     12.21 12.43 13.06 13.98 14.94 15.65 15.92 15.75 15.18 14.25 13.23 12.48
% +/-  0.05  0.05  0.05  0.05  0.05  0.05  0.05  0.05  0.05  0.05  0.05  0.05
% 
%   Using water temperature below sea ice:
% 
% Estimated Jan 1951-Dec 1980 monthly absolute temperature:
%      Jan   Feb   Mar   Apr   May   Jun   Jul   Aug   Sep   Oct   Nov   Dec
%     12.92 13.20 13.83 14.66 15.47 16.08 16.40 16.31 15.74 14.80 13.80 13.12
% +/-  0.05  0.04  0.04  0.04  0.04  0.04  0.04  0.04  0.04  0.04  0.04  0.05
% 
% The reported data is broken into two sections.  The first section reports 
% values where air temperatures were used in the presence of sea ice.  This 
% is followed by section using sea-surface temperatures in the presence of sea 
% ice.
% 
% For each month, we report the estimated global surface temperature anomaly 
% for that month and its uncertainty.  We also report the corresponding values 
% for year, five-year, ten-year, and twenty-year moving averages CENTERED about 
% that month (rounding down if the center is in between months).  For example, 
% the annual average from January to December 1950 is reported at June 1950. 
% 
% Global Average Temperature Anomaly with Sea Ice Temperature Inferred from Air Temperatures
%

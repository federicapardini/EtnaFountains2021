
Supplementary for: Forecast from VONA_20210228_0811Z
====================================================

Contents
========

* [Input data](#input-data)
	* [Meteorological data](#meteorological-data)
	* [Volcanological data](#volcanological-data)
	* [Computational domain](#computational-domain)
	* [HYSPLIT setting](#hysplit-setting)
* [Ensemble definition](#ensemble-definition)

# Input data

## Meteorological data
  

|Parameters|Values|
| :--- | :--- |
|Data source|ARPA-SIM Mesoscale Model|
|Data type|Forecast|
|Temporal resolution|3 h|
|Grid resolution|0.05°|

## Volcanological data
  

|Parameters|Values|
| :--- | :--- |
|Volcano|Mt. Etna|
|Vent height|3300 m|
|Vent lat|37.73°|
|Vent lon|15.00°|
|Total Grain Size Distribution|Lognormal|
|Mixture temperature|[1300] K|
|Water vapour content|[0.03]|
|Particle density|[900] [2500]|
|Particle sphericity|[0.4] [0.9]|
|Particle specific heat|[1100] J/KgK|

## Computational domain
  

|Parameters|Values|
| :--- | :--- |
|Grid center lat|37.73°|
|Grid center lon|15.0°|
|Number of Hysplit grids|2|
|Grid1||
|Extension lat|1.2°|
|Extension lon|1.2°|
|Resolution lat|0.02°|
|Resolution lon|0.02°|
|Grid2||
|Extension lat|4°|
|Extension lon|7°|
|Resolution lat|0.2°|
|Resolution lon|0.2°|
|Atmospheric levels|0 5000 10000 20000 m|

## HYSPLIT setting
  

|Parameters|Values|
| :--- | :--- |
|Pollutant type|Puff|
|Integration time step φ ≤ 0 |2 min|
|Integration time step φ > 0 |10 min|
|Output resolution|10 min|

# Ensemble definition
  

|Parameters|Values|Type of distribution|
| :--- | :--- | :--- |
|Number of perturbed meteo data|21||
|Perturbation on horizontal wind direction |0 ± 20°|Gaussian|
|Perturbation on horizontal wind intensity|1 ± 0.5m/s|Gaussian|
|Number of eruptive scenarios|1||
|Number of perturbed ESP per scenario|21||
|Column height|4500.0 ± 500 - from VONA|Gaussian|
|Total Grain Size Distribution|μ = [-1.5 φ, 2 φ], σ = [0.8 φ, 3.6 φ]|Uniform|
|Number of ensemble members per scenario|21||
  
Go to [Main page](https://github.com/federicapardini/Real_time_ash_forecast/tree/main/FORECAST_RESULTS/20210228_0811Z)  
Go to [Main directory](https://github.com/federicapardini/Real_time_ash_forecast)
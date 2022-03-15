# Real-time tephra fallout and dispersal assessment at Mt. Etna (Italy) <br/> Numerical results for three lava fountain episodes of the 2021 paroxysmale cycle

<p align="center">
  <img src="./logo_dir/Logo_INGV.png" width=150pt />
</p>


This repository provides probabilistic volcanic hazard maps for tephra fallout and dispersal of three paroxysmal episodes at the summit craters of Mt. Etna. The investigated lava fountain episodes occurred on:

* 16 February 2021 
* 28 February 2021 
* 4 March    2021 


Numerical forecasts areproduced by an automated workflow which is activated in real-time when explosive eruptions with tephra emission occur. The workflow is informed about the state of the volcano by the Volcano Observatory Notifications for Aviation (VONAs) issued by the Italian National Institute of Geophysics and Volcanology-Osservatorio Etneo (INGV-OE), which is the reference institute for the monitoring of Mt. Etna. The numerical procedure has been developed and tested at the Italian National Institute of Geophysics and Volcanology-Sezione di Pisa (INGV-Sezione di Pisa), with the contribution of colleagues from the INGV-OE.

The main features of the workflow are:

* Meteo data source: ARPA-SIM Mesoscale Model
* Numerical models used: eruptive column model PLUME-MoM-TSM (de'Michieli Vitturi, M., & Pardini, F. 2021) coupled with the Tephra Transport Dispersal Model HYSPLIT (Stein et al., 2015)
* Ensemble of simulations are performed and probabilistic hazard maps are produced

### Forecast products

|Type of product|Description|
| :--- | :--- |
|MER, total mass of tephra in the air, total mass of tephra deposited on the ground|Tables showing the 5th, 50th and 95th percentiles of MER [kg/s¹], total mass in the air [kg], total mass on the ground [kg]|
|Ground load at strategic locations|Tables showing the ground load in kg/m² at a number of locations. For each location, we report the 5th, 50th and 95th percentiles of the ground load distribution resulting from the simulations forming the ensemble|
|Ground hazard maps|Probability in % that deposit load exceeds 0.5 kg/m² and 5 kg/m²|
|Atmospheric hazard maps|Probability in % that ash concentration between different atmospheric levels exceeds 0.2 g/m³, 2 g/m³ and 4 g/m³|

### How to display the results
* Go to the FORECAST_RESULTS directory
* Select the directory of interest (each directory is named according to the time of issue of the first red VONA of the event)
    * The main results are automatically displayed by selecting the directory of interest
    * Additional information are in *Supplementaty_page*
    * All the figures shown in the main page and more are collected in the directory *figures*. Additional files reporting the eruptive source parameters used in the simulations are in the directory *input_data*

## References

Andronico, D., Cannata, A., Di Grazia, G., & Ferrari, F. (2021). The 1986–2021 paroxysmal episodes at the summit craters of Mt. Etna: Insights into volcano dynamics and hazard. Earth-Science Reviews, 220, 103686.

Corradini, S., Guerrieri, L., Lombardo, V., Merucci, L., Musacchio, M., Prestifilippo, M., ... & Stelitano, D. (2018). Proximal monitoring of the 2011–2015 Etna lava fountains using MSG-SEVIRI data. Geosciences, 8(4), 140.

de'Michieli Vitturi, M., & Pardini, F. (2021). PLUME-MoM-TSM 1.0. 0: a volcanic column and umbrella cloud spreading model. Geoscientific Model Development, 14(3), 1345-1377.

Pardini, F., Corradini, S., Costa, A., Esposti Ongaro, T., Merucci, L., Neri, A., ... & de’Michieli Vitturi, M. (2020). Ensemble-Based Data Assimilation of Volcanic Ash Clouds from Satellite Observations: Application to the 24 December 2018 Mt. Etna Explosive Eruption. Atmosphere, 11(4), 359.

Scollo, S., Prestifilippo, M., Bonadonna, C., Cioni, R., Corradini, S., Degruyter, W., ... & Pecora, E. (2019). Near-real-time tephra fallout assessment at Mt. Etna, Italy. Remote Sensing, 11(24), 2987.

Stein, A. F., Draxler, R. R., Rolph, G. D., Stunder, B. J., Cohen, M. D., & Ngan, F. (2015). NOAA’s HYSPLIT atmospheric transport and dispersion modeling system. Bulletin of the American Meteorological Society, 96(12), 2059-2077.

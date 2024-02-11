# Electricity Price Prediction

The goal of this project is to model the daily price variation of electricity futures contracts in France and Germany from exploratory riables such as weather, energy and commercial data. We will be comparing a range of ensemble models to achieve this goal.

The input datasets have 35 columns, including:
- ID: Unique row identifier, associated with a day and a country.
<<<<<<< Updated upstream
- DAY ID: Day identifier.
=======
- DAY ID: Day identifier.(Both FR and DE starts from 0 - 1215)
>>>>>>> Stashed changes
- COUNTRY: Country identifier - DE = Germany, FR = France.
- Weather measures: Temperature, Rainfall, Wind, etc.
- Energy production measures: Natural gas, Hard coal, Hydro reservoir, etc.
- Electricity use metrics: Total electricity consumption, Residual load, Net import/export, etc

The output dataset is composed of two columns:
- ID: Unique row identifier - corresponding to the input identifiers.
- TARGET: Daily price variation for futures of 24H electricity baseload.

The data can be found here: [ENS Data Challenge website](https://challengedata.ens.fr/challenges/97).

This project is part of the Ensemble Learning course at CentraleSupélec from January to March 2024. Completed by Xiao Qing Wang, Rhianne Gonsalves, Gabriele Genovese and Alix Vermeulen.

Interesting side of the data:

FR/DE_IMPORT = - FR/DE_EXPORT

DE_FR_EXCHANGE = - FR_DE_EXCHANGE

Empty data:
- For FR, there is missing data
        DE_FR_EXCHANGE = FR_DE_EXCHANGE 25
        DE_NET_EXPORT = DE_NET_IMPORT 124
        FR_NET_EXPORT = FR_NET_IMPORT 70
- To put every value equals to 0.




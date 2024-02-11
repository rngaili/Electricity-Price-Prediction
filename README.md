# Electricity Price Prediction

The goal of this project is to model the daily price variation of electricity futures contracts in France and Germany from exploratory riables such as weather, energy and commercial data. We will be comparing a range of ensemble models to achieve this goal.

The input datasets have 35 columns, including:
- ID: Unique row identifier, associated with a day and a country.
<<<<<<< Updated upstream
- DAY ID: Day identifier.
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



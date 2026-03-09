---
title: Predicting Drifting Buoys
start_date: '2019-04-01'
end_date: '2019-07-01'
description: Lagrangian forecasting of drifting FAD trajectories using ocean-current models.
category: maritime
customer: "Satlink"
---

## Overview
Satlink is one of the largest world manufacturers of smart buoys for the tuna fishing industry.  They approached me while I was working at University of Cádiz with an initial project that involved predicting the drifting trajectory of a FAD (Fish Aggregating Device) to which their buoys are attached. Besides other sensors, these smart buoys contain an echosounder that measures biomass and detect tuna presence, and they send this information every hour to a satellite. The buoys are deployed by ships that drop them in the ocean, and once released they drift with the ocean currents. The company found that, despite having an operation life of 6-12 months,  many buoys were lost within 2-3 weeks by collision with the coast. They wanted to identify the best spots to drop the buoys so that the drift would keep them circulating in the ocean.

Satlink provided us with a very valuable dataset: the daily positions of more than 40.000 drifting buoys in the Indian Ocean.

We developed a Lagrangian numerical integration scheme which used the ocean currents predictions from an European provider (Copernicus) and an American one (HYCOM).

As a side project, we used their data to validate predictions from these models, comparing the true trajectories of the buoys with those predicted by the Lagrangian model.  This is an example of a synergistic and positive by-product between industry and research. The largest publicly funded program to gather data from drifting buoys is the NOAA [Global Drifter Program](https://www.aoml.noaa.gov/global-drifter-program/), which contains around 1000 buoys from a collaboration between 19 countries. By way of contrast, we had access to a proprietary dataset of more than 20 years of operation for ca. 40.000 buoys in the three major oceans, providing daily (sometimes hourly) positions. Of course these buoys were deployed for fishing purposes, but the data they gathered can be used for many other scientific purposes, in this case, validation of Ocean General Circulation Models.

My role in this project was Principal Investigator and responsible for the contract. It was a good opportunity to work with Karan Bedi, a visiting MSc student from IIT Roorkee (India), who visited UCA Datalab in Cádiz during that period.

### Projects and Contracts

- Prediction of drifting objects in the ocean. Contract Art. 83 between Satlink SL and Universidad de Cádiz. PI: David Gómez-Ullate (UCA), 01/04/2019 – 01/07/2019, Sum: 70.000 EUR.

---
title: Non-Intrusive Load Monitoring
start_date: '2019-01-01'
end_date: '2023-12-31'
description: Data-driven methods to infer appliance-level electricity use from smart-meter signals.
category: energy
---

Non-Intrusive Load Monitoring (NILM) identifies the activity of individual appliances, such as fridges, washing machines, and dishwashers, from total household electricity demand measured by a smart meter. This avoids dedicated sensors per device and enables scalable energy analytics for demand response, feedback, and efficiency programs.

This project examined a key modeling issue in NILM, how to define ON and OFF appliance states from continuous power signals. Different thresholding rules can change the learning problem and significantly alter model performance. We compared thresholding strategies systematically and proposed objective criteria based on reconstruction error.

The work also explored multi-task learning to jointly estimate appliance state and power consumption. Results were presented at BIDAS 4 and IEEE PowerTech Madrid 2021 and led to publications in The Journal of Supercomputing (2023) and IEEE PowerTech proceedings.
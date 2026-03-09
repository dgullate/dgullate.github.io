---
title: Non-Intrusive Load Monitoring
start_date: '2019-01-01'
end_date: '2023-12-31'
description: Data-driven methods to infer appliance-level electricity use from smart-meter signals.
category: energy
---

This work addresses a fundamental but often overlooked modeling choice in NILM: how to define when an appliance is considered ON or OFF. Since real datasets usually provide power consumption but not appliance states, this requires introducing thresholding rules that transform a regression problem into a classification task. We show that different thresholding methods lead to substantially different learning problems and performance outcomes, even when using the same deep learning architectures. By systematically comparing thresholding strategies and proposing objective criteria based on signal reconstruction error, the paper highlights the importance of problem formulation in NILM. In addition, a multi-task learning approach is explored, showing that jointly learning appliance status and power consumption can improve performance for certain types of devices through transfer learning between regression and classification tasks. 

This was the first paper we wrote with Daniel Precioso when he joined UCA Datalab at University of Cádiz to start his industrial PhD. He was already interested in this topic because he had done an internship at Foqum analytics. We extended his work and addressed a relevant conceptual problem in how NILM problems are usually framed. The work was presented in a few conferences , among which:

BIDAS 4 - Fourth Bilbao Data Science Workshop BCAM (Nov 7-10 2019)

IEEE Powertech Madrid 2021, (Jun 28-Jul 2 2021)

It also led to the publication of these papers:

 Thresholding Methods in Non-Intrusive Load Monitoring. The Journal of Supercomputing 

79 14039–14062, (2023)

 Non-Intrusive Load Monitoring Using Multi-Output CNNs. 2021 IEEE Madrid PowerTech, Madrid, Spain, 2021, 


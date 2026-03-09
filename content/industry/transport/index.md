---
title: Green Navigation
start_date: '2022-09-01'
end_date: '2025-06-30'
description: Weather-routing optimization for safer, lower-emission maritime transport.
category: transport
customer: "Navantia"
---

## Overview
### Projects and Contracts

Mathematical optimization for a more efficient, safer and decarbonized maritime transport Fundación BBVA - Matemáticas 2021, 01/09/2022 – 30/06/2025 PI: David Gómez-Ullate (IE University), Team: 23 researchers, Sum: 150.000 EUR
Optimización de rutas marítimas con información oceanográfica en tiempo real AEI Transición Ecológica y Digital (TED2021-129455B-I00), 01/12/2022 – 30/11/2024 PI: David Gómez-Ullate (IE University), Team: 12 researchers, Sum: 116.380 EUR
### Publications

J. Jiménez, D. Precioso, L. Bu, M.V. Redondo, R. Mison. R. Ballester and D. Gómez-Ullate, HADAD: Hexagonal A-Star with Differential Algorithm Designed for weather routing, Ocean Engineering 319 (2025) https://doi.org/10.1016/j.oceaneng.2024.120050
D. Precioso, R. Milson, L. Bu, and D. Gómez-Ullate, Hybrid search method for Zermelo’s navigation problem, Computational and Applied Mathematics, 43(4) (2024) 250.
### Presentations

Mathematical optimization for a more efficient, safer and decarbonized maritime transport, Royal Academy of Sciences, Madrid, Jul 7, 2023 [video]
Smart Shipping: weather routing and WASP simulation, Session on Wind Propulsion at Sea Tech Week, Brest, France, Sep 26-30, 2022.

Mathematical optimization of maritime shipping routes, IE-RSME Workshop on Applied Mathematics in Sustainability and Climate Change, IE Tower (Madrid) May 30, 2023 [link].

### Technical Overview

Maritime transport accounts for more than 80% of global trade, yet it faces growing regulatory and environmental pressure to reduce fuel consumption and greenhouse gas emissions. At the same time, the increasing availability of high‑resolution oceanographic and meteorological data has opened new opportunities for smarter, data‑driven navigation.

The Green Navigation project was born at this intersection: how can rigorous mathematical optimization transform real‑time weather and ocean data into safer, more efficient, and lower‑emission shipping routes?

Funded by Fundación BBVA and the Spanish Ministry of Science, and developed in collaboration with Navantia and multiple academic partners, the project aimed to design a next‑generation weather routing system capable of integrating ocean currents, wind forecasts, fuel consumption models, vessel dynamics, and regulatory constraints into a unified optimization framework.

The result is a fully operational routing platform that combines advanced mathematical theory with industrial‑grade software. The system computes optimized maritime routes based on departure date, vessel characteristics, cruise speed, and meteorological forecasts. It has been validated in real pilot studies with Boluda Shipping achieving average fuel savings of approximately 5-10% while maintaining operational constraints. These reductions translate directly into lower CO₂ emissions, improved economic performance, and enhanced navigational safety.

From a methodological perspective, Green Navigation integrates multiple layers of applied mathematics, optimization, and computational science:

Variational methods and geometric integration extend the classical Zermelo navigation problem using structure‑preserving discretizations with proven convergence properties. Parallel GPU implementations ensure scalability for large‑scale computations.

Graph‑based optimization reformulates maritime routing as a time‑dependent shortest‑path problem. The HADAD algorithm (Hexagonal A‑Star with Differential refinement) introduces a hierarchical hexagonal spatial discretization, enabling multi‑scale exploration of the ocean surface while maintaining computational efficiency.

Hybrid global–local search strategies combine fast heuristic exploration with variational refinement, ensuring both near‑global optimality and local numerical accuracy.

Robust optimization under uncertainty incorporates ensemble weather forecasts and sensitivity analyses to quantify the impact of meteorological prediction errors on route performance.

Data‑driven consumption and emissions models link vessel characteristics and sea‑state conditions to fuel consumption and pollutant emissions. Artificial neural networks trained on thousands of simulated hull geometries enable rapid prediction of hydrodynamic loads and seakeeping behavior with high accuracy.

A key contribution of the project is the creation of Weather Routing Bench 1.0, the first open benchmark for maritime weather routing. By providing standardized datasets, evaluation metrics, and reference implementations, this platform promotes reproducibility, objective comparison, and cumulative progress in a field that previously lacked a common evaluation framework.

The technological maturity and industrial validation of the project ultimately led to the creation of a spin‑off company, Green Navigation (https://greenavigation.com). The startup builds on the algorithms, software architecture, and optimization methodologies developed during the research project, translating them into scalable commercial solutions for the maritime sector.

This transition from academic research to entrepreneurial initiative reflects the project’s dual ambition: advancing frontier mathematical research while delivering measurable environmental and economic impact in real shipping operations.


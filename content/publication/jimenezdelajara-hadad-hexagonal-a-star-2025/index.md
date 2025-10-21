---
title: 'HADAD: Hexagonal A-Star with Differential Algorithm Designed for Weather Routing'
authors:
- Javier Jiménez De La Jara
- Daniel Precioso
- Louis Bu
- M. Victoria Redondo-Neble
- Robert Milson
- Rafael Ballester-Ripoll
- David Gómez-Ullate
date: '2025-03-01'
publishDate: '2025-10-21T14:54:43.549228Z'
publication_types:
- article-journal
publication: '*Ocean Engineering*'
doi: 10.1016/j.oceaneng.2024.120050
abstract: We present HADAD (Hexagonal A-Star with Differential Algorithm Designed
  for weather routing), a novel optimization algorithm for weather routing. HADAD
  conducts a global exploration using an A  search on a hexagonal grid with higher-order
  neighbors, enhancing directional flexibility and overcoming limitations of traditional
  graph searches that constrain vessel movements. It then refines the solution using
  a discrete Newton--Jacobi variational method, ensuring convergence to a locally
  optimal, smooth route in continuous space. To evaluate the effectiveness of HADAD,
  we developed a benchmark comprising 1,560 instances over a full year, varying in
  origin--destination pairs, vessel speeds and oceanographic conditions. Our results
  show that HADAD outperforms pure A*  graph search methods by an extra 4% savings
  with respect to the shortest-distance route, thanks to more flexible smoother trajectories
  obtained by gradient descent. In our seasonal study we observe that the savings
  distribution shows large seasonal variations (double savings on average in winter
  with respect to summer) and contains a significant number of outliers. Savings reach
  27% in these cases of extreme weather events. Validation of the algorithm performed
  with synthetic vector fields has been conducted. In this setting, the algorithm
  has been adapted to handle fuel consumption optimization for Just-in-Time arrival.
  By integrating global search and local optimization, HADAD effectively balances
  computational efficiency with route optimality, offering a practical and adaptable
  solution for real-world weather routing applications.
---

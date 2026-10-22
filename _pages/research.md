---
permalink: /research/
title: "Research"
author_profile: true
---

My work follows one line, from predicting flights, to repairing incomplete flight data, to generating new flights that can be priced and compared for operational decisions. The next step is to optimize and control these trajectories.

Generative trajectory modeling for decision support
------
For my M.Sc. thesis at the University of Washington, with Dr. Don MacKenzie, I developed a conditional variational autoencoder with a VampPrior that generates new flight trajectories for a requested route, departure time, and cruise condition. The encoder separates the spatial and the temporal features of a flight, the decoder is a temporal convolutional network, and physics-informed terms in the training keep the generated flights within the limits of aircraft. Each generated flight is then priced for its fuel and emissions with the BADA aircraft performance model, and the trade-off between the airline cost and the external cost is shown as a Pareto frontier, which a dispatcher can use to compare the alternatives of a flight before it takes place.

[INFORMS Annual Meeting 2026 talk](/talks/2026-11-01-informs-annual-meeting)

ADS-B data imputation and 3-D emissions mapping
------
ADS-B data is open and detailed, but many flights have missing segments, and in the January 2025 data of Seattle, San Francisco, and Los Angeles, more than half of the flights had a gap. We developed an autoencoder that fills these gaps, and it reconstructed the altitude and the vertical rate more accurately than interpolation. Then, we estimated the fuel burn and the emissions along each flight with BADA and mapped the emissions and their social cost by location and altitude.

[3-D Emissions Mapping and Social Cost Estimation for US Domestic Aviation at West Coast Hubs (arXiv)](https://arxiv.org/abs/2609.31686)

4D flight trajectory prediction
------
At the University of California, Irvine, with Dr. Amelia Regan, I worked on predicting 4D flight trajectories from ADS-B data at Hartsfield–Jackson Atlanta International Airport. We proposed CG3D, a hybrid model in which a CNN extracts the spatial features, a GRU extracts the temporal features, and a 3D-CNN extracts both of them together, and we showed that separating the spatial and the temporal features improves the prediction.

[Transportation Research Part C (2022)](https://www.sciencedirect.com/science/article/pii/S0968090X22002911) · [IEEE Aerospace Conference (2022)](https://ieeexplore.ieee.org/abstract/document/9843822/)

Freight electrification and traffic simulation
------
At the Urban Freight Lab of the University of Washington, I worked on the electrification and the emissions of heavy- and medium-duty delivery vehicles, which is a part of the report [The State of Zero-Emissions Delivery in the US](https://digital.lib.washington.edu/researchworks/items/756c7377-3abc-4ce1-9508-bbbd940d89e4/full). Earlier, in Iran, I used microscopic traffic simulation (AIMSUN) to study the traffic and environmental effects of pedestrian and public transportation infrastructure.

Next steps
------
The generative model gives a set of plausible alternatives for a flight, but it does not choose the best one. The direction I want to follow in my PhD is to optimize and control these trajectories, with an objective that includes both the airline cost and the external cost, and under the uncertainty of the wind and the weather. I am also interested in applying the same approach to UAVs, delivery drones, and eVTOL aircraft, where the airspace is shared, the vehicles are new, and the operating rules are still being defined.

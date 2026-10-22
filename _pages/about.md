---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am an M.Sc. student in Transportation Engineering in the Department of Civil and Environmental Engineering at the University of Washington, where I work with Dr. Don MacKenzie. Before coming to UW, I received an M.Sc. in Transportation Engineering from Islamic Azad University, Science and Research Branch, in Tehran, and a B.Sc. in Civil Engineering from Ilam University. I am looking for a PhD position in aerospace or transportation engineering.

Research interests
------
My research interest is in optimization, control, and decision making for operations research problems in transportation, and in particular for air traffic systems, including commercial aircraft, unmanned aerial vehicles (UAVs), and vertical take-off and landing (VTOL and eVTOL) aircraft. The main question for me is how a vehicle should be operated, for example which trajectory, altitude, and speed a flight should take, when the decision has to consider the cost to the operator, the cost to society, and the uncertainty of the conditions. In other words, I want to build methods that support these decisions, and not only describe the system.

Such decisions depend on data, and real data is rarely clean. For this reason, a part of my work is about learning from incomplete and noisy trajectory data, so that the optimization and control models have a realistic picture of the system to work with.

What I have worked on
------
* **Flight trajectory prediction.** At the University of California, Irvine, with Dr. Amelia Regan, I developed a hybrid deep learning model, CG3D, which combines a CNN, a GRU, and a 3D-CNN to predict 4D flight trajectories from ADS-B data at Hartsfield-Jackson Atlanta International Airport. This work was published in *Transportation Research Part C* (2022) and at the *IEEE Aerospace Conference* (2022).
* **Data imputation and emissions mapping.** ADS-B data has many gaps, and in the January 2025 data of Seattle, San Francisco, and Los Angeles, more than half of the flights had a missing segment. I developed an autoencoder that fills these gaps, and then I estimated the fuel burn and the emissions along each flight with the BADA aircraft performance model to map the emissions and their social cost in three dimensions.
* **Generative trajectory modeling.** For my M.Sc. thesis, I developed a conditional variational autoencoder with a VampPrior that generates new flight trajectories for a requested route, departure time, and cruise condition. The generated flights are priced for the airline cost and the external cost, and the trade-off between the two is shown as a Pareto frontier. I present this work at the 2026 INFORMS Annual Meeting.
* **Earlier work.** I worked on the electrification and emissions of heavy- and medium-duty delivery vehicles at the Urban Freight Lab at UW, and on microscopic traffic simulation of pedestrian and public transportation infrastructure with AIMSUN in Iran.

What I want to do next
------
The generative model gives a set of plausible alternatives for a flight, but it does not choose the best one. The next step, and the direction I want to follow in my PhD, is to optimize and control these trajectories, with an objective that includes both the airline cost and the external cost, and under the uncertainty of the wind and the weather. I am also interested in applying the same approach to UAVs, delivery drones, and eVTOL aircraft, where the airspace is shared, the vehicles are new, and the operating rules are still being defined.

I am happy to hear from you about PhD positions, collaborations, or questions about my work. You can reach me at [hesamsh@uw.edu](mailto:hesamsh@uw.edu), and my [CV](/files/Hesam_Shafiei_Nia_CV.pdf) and [resume](/files/Hesam_Shafiei_Nia_Resume.pdf) are available on this site.

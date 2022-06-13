# Numerical investigation of airflow involved in a person-to-person interaction wearing Personal Protective Equipment
## Overview
As the spread of COVID is likely airborne transmission [1], characterising likely airflow nearby person's faces using Computational Fluid Dynamics allows us to compare differing parameters of Personal Protective Equipment (PPE) quickly, thus potentially improving their effectiveness (of preventing transmission of airborne viruses) efficiently.

## Background
The fluid dynamics of airflow involved in a person-to-person interaction, where one person is assumed to have a virus, comprises a combination of turbulent jet flow and potentially two-phase flow.

A turbulent jet normally appears emanating from the person speaking, which is carried forwards [2]. Droplets, also present in speaking, tend to fall towards the ground increasingly quickly with higher mass, while increasingly smaller masses tend to follow the airflow pattern more.

If a face mask is worn by the infected person while speaking the jet momentum may be reduced, however the breakup of droplets may cause the other person to inhale more of the virus, due to the smaller droplet sizes. If a face shield is worn by the infected person the transmission to the other person has been shown to be decreased [3].

## Scope
The inhalation of such droplets may be reduced significantly if a face shield is worn by the virus-free person [4], however depending on the orientation of person A relative to person B we assert this mitigation may not be effective. It's this assertion that we aim to check within this investigation.

## Methodology
Computational Fluid Dynamics (CFD) will be used to investigated a number of numerical experiments where the parameters of the PPE are varied. Specifically the OpenFOAM software will be used to run parallel simulations on cloud-based infrastructure.

This finite-volume approach will introduce turbulence modelling of the airflow created due to speaking, which includes the appropriate modelling of flow around the shield towards the nose of the person assumed to be inhaling the virus.

## Validation of methodology
However, due to the non-empirical experimental method employed, certain activities such as validation and verification should be also undertaken to provide confidence numerical experiments (such as CFD) are accurate reflections of the 'real-world', while also ensuring error introduced by the numerical methods are non-significant.

## Disclosure
Note all applicable intellectual property (IP) we generate is made available under an Open COVID License (OCL). Specifically, IP is released under their Patent and Copyright version 1.1 license. See the [OCL-PC v1.1 license](https://opencovidpledge.org/v1-1-ocl-pc/) for more specific details.

### References  
1. https://en.wikipedia.org/wiki/Transmission_of_COVID-19  
2. Speech can produce jet-like transport relevant to asymptomatic spreading of virus: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7568291/  
3. Visualizing droplet dispersal for face shields and masks with exhalation valves: https://aip.scitation.org/doi/10.1063/5.0022968  
4. An Experimental Investigation of the Flow Structure on a Face Mannequin With / Without a Face Shield: https://dergipark.org.tr/en/download/article-file/1675241  

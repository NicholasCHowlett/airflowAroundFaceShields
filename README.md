# Numerical investigation of airflow involved in a person-to-person interaction wearing Personal Protective Equipment
## Overview
As the spread of COVID is likely airborne transmission [1], characterising likely airflow nearby person's faces using Computational Fluid Dynamics allows us to compare differing parameters of Personal Protective Equipment (PPE) quickly, thus potentially improving their effectiveness (of preventing transmission of airborne viruses) efficiently.

## Background
The fluid dynamics of airflow involved in a person-to-person interaction, where one person is assumed to have a virus, comprises a combination of turbulent jet flow and potentially two-phase flow.

A turbulent jet normally appears emanating from the person speaking, which is carried forwards [2]. Droplets, also present in speaking, tend to fall towards the ground at increasingly shorter distances for higher sizes, while increasingly smaller-sized ones tend to follow the airflow pattern more closely.

If a face mask is worn by the infected person while speaking the jet momentum may be reduced, however the breakup of droplets may cause the other person to inhale more of the virus, due to the smaller droplet sizes. If a face shield is worn by the infected person the transmission to the other person has been shown to be decreased [3].

## Scope
The inhalation of droplets may be reduced significantly if a face shield is worn by the virus-free person [4], however depending on the orientation of this person relative to the person assumed to have a virus we assert this mitigation effect may not be completely effective, particularly for smaller-sized droplets that essentially follow the flow patterns of the air.

It's this orientation of the person speaking to the other person that we aim to primarily check within this investigation. We also plan to check the mitigation effect of the shield if the speaking person projects the turbulent jet at differing angles relative to their mouth position, as inherent variant of this angle is expected in 'real-world' scenarios.

These scenarios will both be investigated with the assumption that the person not speaking will be inhaling at their maximum volumetric rate, and inhaling fully thru their nose. The distance from person-to-person will be 0.75 [m]. The speaking person's jet characteristics will be idealised, based on experimental data. The face shield dimensional characteristics will be averaged from common, commercially-available products [5, 6, 7].

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

#### Face shields considered
5. https://www.medcart.com.au/a/face-shields-surgical-visors/werkomed/face-shield-with-clear-visor/100041747?variant_id=114178  
6. https://www.medcart.com.au/a/face-shields-surgical-visors/hlp-medical-supplies/act/kaleen/double-side-anti-fog-coated-face-shield-face-protection-1-shield/100043782?variant_id=117564  
7. https://www.medcart.com.au/a/face-shields-surgical-visors/ethical-pharmacy-supplies/nsw/yagoona/disposable-full-face-shield/100042218?variant_id=115725  

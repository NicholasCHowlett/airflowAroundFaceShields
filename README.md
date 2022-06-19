# Numerical investigation of speech-driven airflow between two people: comparison of face shields' effectiveness against airborne transmission of viruses
## Summary
We use Computational Fluid Dynamics to assess the airflow between a person speaking and another person in close proximity. We consider this flow in the context of possible transmission of airborne viruses, assuming the non-speaking person is wearing a face shield. Once confident our modelling accurately reflects reality, we then propose a potentially improved shield design, and assess it's effectiveness as compared to the former product.

## Impact
As relatively severe negative health impacts from having COVID have been documented in certain cases, such as 'long COVID', we believe such investigations as ours - seeking effective preventative measures for higher-risk cases - is reason enough given the financial impact on the sufferer from these conditions.

## Introduction
The spread of COVID is likely dominated by airborne transmission [1], thus we aim to investigate the fluid dynamics [2] of an interaction between two people in higher-risk settings such as when speaking in low-velocity surrounding airflow environments (such as potentially indoors).

As indoor environments such as schools, universities, and offices are normally associated with significant levels of speaking (usually within closer proximity to another person than if they were just breathing), we will concentrate on exhalation of air from the mouth [F1].

The fluid dynamics of airflow involved, where one person is assumed to have a virus, comprises a combination of likely turbulent jet flow and potentially two-phase flow. A turbulent jet normally appears emanating from the person speaking, which is carried forwards [3]. Droplets, also present in speaking, tend to fall towards the ground at increasingly shorter distances for higher sizes, while increasingly smaller-sized ones tend to follow the airflow pattern more closely.

If a face mask is worn by the infected person while speaking the overall jet momentum may be reduced, however the breakup of droplets may cause the other person to inhale more of the virus, due to the smaller droplet sizes (which reach further than droplets). If a face shield is worn by the infected person the transmission of particles (representing a virus) to the other person has been shown to be decreased [4].

## Scope
The inhalation of droplets may be reduced significantly if a face shield is worn by the virus-free person [4], however we assert this mitigation effect may be dramatically improved if we redesign this shield, particularly for smaller-sized droplets that follow the flow patterns of the air more.

We first aim to check the effectiveness of face shields that are currently commercially available. Then we will investigate the effectiveness of a proposed novel face shield, and compare the results.

Our investigation will include varying variables of interest including:
- Horizontal orientation angle of the person speaking relative to the other person.
- Turbulent jet angle relative to the speaker's head position, as inherent variant of this angle is apparent during different words produced when speaking [3].
- Depth of face shield relative to it's front.

These scenarios will both be investigated with the assumption that the person not speaking will be inhaling at their maximum volumetric rate, and inhaling fully thru their nose. The distance from person-to-person will be assumed to be a constant of 0.75 [m]. The speaking person's jet characteristics will be idealised, based on experimental data [5]. The face shield's dimensional characteristics will be averaged from common, commercially-available products [F2].

## Methodology
Computational Fluid Dynamics (CFD) will be used to conduct a number of numerical experiments where various parameters are varied. To achieve this within an adequate timeframe the OpenFOAM software will be used to run numerous, parallel simulations on cloud-based infrastructure.

This finite-volume approach will include turbulence modelling of the airflow created due to speaking, which includes appropriate modelling of flow around the shield towards the nose of the person assumed to be inhaling the virus. The person inhaling will be represented as a simplified geometry, created & generously released by [Atharva Wagh](https://grabcad.com/atharva.wagh-1).

Due to the non-empirical experimental method employed, certain activities such as validation and verification should be also undertaken to provide confidence our numerical experiments are accurate reflections of the 'real-world', while also ensuring error introduced by the numerical methods are non-significant.

Specifically our numerical results will be validated against experimental results, including airflow visualisations similar to some already experimentally investigated [9]. We will also verify the insensitivity of numerical results to differing numerically-based parameters used to generate these results.

## Disclosure
All applicable intellectual property (IP) we generate is made available under an Open COVID License (OCL). Specifically, our IP is released under their Patent and Copyright version 1.1 license. See the [OCL-PC v1.1 license](https://opencovidpledge.org/v1-1-ocl-pc/) for more specific details.

## References  
1. https://en.wikipedia.org/wiki/Transmission_of_COVID-19  

2. The Fluid Dynamics of Disease Transmission: https://www.annualreviews.org/doi/10.1146/annurev-fluid-060220-113712  
3. Speech can produce jet-like transport relevant to asymptomatic spreading of virus: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7568291/  
4. An Experimental Investigation of the Flow Structure on a Face Mannequin With / Without a Face Shield: https://dergipark.org.tr/en/download/article-file/1675241  
5. Characterizing exhaled airflow from breathing and talking: https://onlinelibrary.wiley.com/doi/full/10.1111/j.1600-0668.2009.00623.x
6. Breathing, virus transmission, and social distancing — An experimental visualization study: https://aip.scitation.org/doi/full/10.1063/5.0045582  

## Footnotes
1. We believe that more complex computational models taking into consideration both breathing and speaking could be warranted as areas of research & development at a later time, especially as an aid for more personalised guidance. This approach is argued as more accurate and hence more appropriate than broader policy generated by health authorities with presumed limited understanding of the fluid dynamics and the associated significant airflow variations and intricacies that can occur in public health-related settings [10].

2. a) https://www.medcart.com.au/a/face-shields-surgical-visors/werkomed/face-shield-with-clear-visor/100041747?variant_id=114178  
b) https://www.medcart.com.au/a/face-shields-surgical-visors/hlp-medical-supplies/act/kaleen/double-side-anti-fog-coated-face-shield-face-protection-1-shield/100043782?variant_id=117564  
c) https://www.medcart.com.au/a/face-shields-surgical-visors/ethical-pharmacy-supplies/nsw/yagoona/disposable-full-face-shield/100042218?variant_id=115725  

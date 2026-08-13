---
layout: page
title: cGENIE
permalink: /cGENIE/
nav: false
---

## cGENIE Earth system model

**cGENIE**  is a flexible, intermediate-complexity Earth system model. Its relatively fast runtime makes it possible to run large ensembles and simulations over tens of thousands to millions of years, while still representing the major physical and biogeochemical components of the Earth system.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/cGENIE/cGENIE_Schematic.png"
       alt="Schematic of the cGENIE Earth-system modelling framework, representing interactions between the ocean, atmosphere, marine biogeochemistry, weathering, and sediments."
       style="width:100%; max-width:550px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    The cGENIE Earth-system modelling framework represents interactions between the ocean, atmosphere, marine biogeochemistry, weathering, and sediments. 
  </div>
</div>


### Exploring different Earth system states

One of the things I particularly like about cGENIE is its flexibility. The model can be configured for very different periods of Earth's history, allowing us to explore how the same processes and feedbacks operate under very different continental configurations, climates, atmospheric compositions, and ocean nutrient inventories.


<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/cGENIE/Bathymetry_cGENIE_Pohl_ea_2022.png"
       alt="Bathymetric reconstructions used in cGENIE spanning the Phanerozoic."
       style="width:100%; max-width:550px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    Examples of cGENIE continental configurations spanning the Phanerozoic. Adapted from [Pohl et al. (2022)](https://www.nature.com/articles/s41586-022-05018-z).
  </div>
</div>

---

## Applications

I use cGENIE to investigate how interactions between climate, marine biogeochemistry, ecosystems, and sediments shape the Earth system, from major environmental perturbations to long-term climate stability.

### Organic carbon burial and ocean anoxic events

We coupled OMEN-SED to cGENIE to explore how changes in organic carbon burial feed back on ocean chemistry and climate. For Ocean Anoxic Event 2, we investigated how sulfurization - the reaction of hydrogen sulfide (H<sub>2</sub>S) with labile organic matter - could increase the preservation of organic matter in marine sediments. Our simulations showed that this process can substantially increase organic carbon burial, helping accelerate climate cooling and ocean reoxygenation and, hence, recovery from the event.

<div style="text-align:center; margin: 25px 0 40px 0;">
  <img src="/assets/img/cGENIE/cGENIE_OAE2_Appl.png"
       alt="cGENIE simulations of Ocean Anoxic Event 2 showing simulated sediment organic carbon compared with geological observations, and zonally averaged ocean oxygen concentrations without and with organic matter sulfurization."
       style="width:100%; max-width:1200px;"
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    <b>cGENIE simulations of Ocean Anoxic Event 2. Simulated sediment organic carbon is compared with geological observations (left), while model experiments show how rapid organic matter sulfurization can substantially reduce the extent of ocean anoxia (middle and right). Percentages indicate the fraction of the ocean that is anoxic. Adapted from [Hülse et al. (2019)](https://doi.org/10.1029/2018PA003470).
  </div>
</div>


### Ocean anoxia and mass extinction

cGENIE also allows us to combine spatially distributed geological observations of redox consitions with simulations of past ocean conditions. For the end-Permian mass extinction, we used observations of seafloor anoxia and photic-zone euxinia (i.e., the presence of H<sub>2</sub>S) to constrain the model and investigate how warming, nutrient recycling, and ocean oxygenation interacted. Our simulations showed how warming increased microbial activity and nutrient recycling, intensifying oxygen loss and expanding toxic, sulfidic waters onto continental shelves and contributing to the marine extinction.

<div style="text-align:center; margin: 25px 0 40px 0;">
  <img src="/assets/img/cGENIE/cGENIE_EndPermian_Appl.png"
       alt="cGENIE simulations of end-Permian ocean redox conditions showing increased photic-zone hydrogen sulfide and lower seafloor oxygen during the main extinction compared with Late Permian background conditions, together with geological proxy observations."
       style="width:100%; max-width:1200px;"
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    <b>cGENIE simulations of ocean redox conditions across the end-Permian mass extinction. Simulations constrained by geological observations show how warming and enhanced nutrient recycling intensified ocean anoxia and expanded euxinic waters onto continental shelves. Adapted from [Hülse et al. (2021)](https://doi.org/10.1038/s41561-021-00829-7).
  </div>
</div>

### Sediment–ocean feedbacks

OMEN-SED can also be used to quantify the exchange of carbon, nutrients, oxygen, and other compounds across the sediment–water interface. Mapping these fluxes globally helps us understand how processes below the seafloor feed back on ocean biogeochemistry.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/OMEN-SED/Global_SWI_fluxes.png"
       alt="Global maps of oxygen, nitrate, and dissolved iron fluxes across the sediment-water interface simulated with OMEN-SED"
       style="width:100%; max-width:1200px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    OMEN-SED simulations of the global exchange of oxygen, nitrate, and dissolved iron between marine sediments and the overlying ocean.
  </div>
</div>


### Coupling sediments to the Earth system

A major goal of OMEN-SED has always been to bring sediment biogeochemistry into global Earth system models. We have already coupled OMEN-SED to cGENIE, allowing organic carbon burial and phosphorus recycling to respond dynamically to changes in the ocean and climate. Starting in September 2026, I will extend this approach by coupling OMEN-SED to the UVic Earth System Climate Model, opening up new applications to modern and future environmental change.

---

## Publications

**The original description and development of OMEN-SED:**

**Hülse, D.**, Arndt, S., Daines, S. J., Regnier, P. & Ridgwell, A. (2018). OMEN-SED 0.1: a novel, numerically efficient organic matter sediment diagenesis module for coupling to Earth system models. *Geoscientific Model Development*, **11**, 2649–2689. [DOI](https://doi.org/10.5194/gmd-11-2649-2018)  


**Further selected publication:**

**Hülse, D.**, Arndt, S., and Ridgwell, A. (2019). Mitigation of extreme Ocean Anoxic Event conditions by organic matter sulfurization. *Paleoceanography and Paleoclimatology*, 34(4), 476–489. [DOI](https://doi.org/10.1029/2018PA003470)  
*Coupling OMEN-SED to cGENIE to investigate sediment–ocean feedbacks during ocean anoxic events.*

Pika, P., **Hülse, D.**, and Arndt, S. (2021). OMEN-SED(-RCM)(v1.1): A pseudo reactive continuum representation of organic matter degradation dynamics for OMEN-SED. *Geoscientific Model Development*. [DOI](https://doi.org/10.5194/gmd-14-7155-2021)  
*Extending OMEN-SED to represent organic matter degradation as a continuous spectrum of reactivities.*

\*Bradley, J. A., \* **Hülse, D.**, LaRowe, D. E., and Arndt, S. (2022). Transfer efficiency of organic carbon in marine sediments. *Nature Communications*, 13, 7297. [DOI](https://doi.org/10.1038/s41467-022-35112-9)  
*Applying OMEN-SED globally to show large spatialial variabilitzy in organic carbon transfer through marine sediments.*

Pika, P., **Hülse, D.**, Eglinton, T. I., and Arndt, S. (2023). Regional patterns of apparent organic matter reactivity in marine sediments. *Global Biogeochemical Cycles*. [DOI](https://doi.org/10.1029/2022GB007636)  
*Mapping spatial patterns in organic matter reactivity across the global seafloor.*

\* **Hülse, D.** and \*Ridgwell, A. (2025). Instability in the geological regulation of Earth’s climate. *Science*. [DOI](https://doi.org/10.1126/science.adh7730)  
*Using coupled sediment–Earth-system simulations to reveal how organic carbon burial and phosphorus recycling can affect long-term climate stability.*


\* These authors contributed equally.


---
layout: page
title: OMEN-SED
permalink: /omen-sed/
nav: false
---

## Organic Matter ENabled SEDiment model

**OMEN-SED** is a vertically resolved 1D early diagenetic model that simulates the main processes related to organic matter degradation in the (marine) sediments. Because it assumes steady-state conditions, the underlying equations can be solved analytically, making the model very fast to run while still capturing much of what more complex sediment models can do. This means we can run OMEN-SED at thousands of locations across the global seafloor or couple it to Earth system models to study how sediments interact with the ocean and global biogeochemical cycles.


<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/OMEN-SED_Website.png"
       alt="Schematic representation of the OMEN-SED sediment model"
       style="width:100%; max-width:550px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    Schematic representation of biogeochemical processes and transport pathways represented in OMEN-SED (cf., Hülse et al., 2018). 
  </div>
</div>


### What does OMEN-SED simulate?

OMEN-SED simulates what happens to organic matter in the seafloor. As organic matter is degraded, the model simulates the main reactions involved in early diagenesis and how they affect the cycling of carbon, oxygen, nutrients, and other elements within the sediment.


The model includes:

- Organic matter degradation through aerobic and anaerobic pathways
- Transport of dissolved and solid species through the sediment
- Bioturbation and bioirrigation
- Exchange of dissolved compounds between the sediment and overlying ocean
- Organic carbon preservation and burial
- Nutrient regeneration, including redox-dependent phosphorus cycling

Its analytical/semi-analytical formulation makes OMEN-SED computationally efficient enough to be applied across thousands of locations and incorporated into global Earth system simulations.

---

## Applications

I use OMEN-SED to investigate how environmental conditions regulate carbon preservation and nutrient recycling in marine sediments, from individual sediment sites to the global ocean.

### From observations to model simulations

OMEN-SED can be applied to individual sediment sites using locally observed environmental conditions. Comparing simulated pore-water and solid-phase profiles with measurements allows us to test how well the model captures organic matter degradation and the resulting biogeochemical dynamics in the sediment.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/OMEN-SED/OMEN_profiles.png"
       alt="Depth profiles of organic carbon, oxygen, nitrate, ammonium, and phosphate at two marine sediment sites, showing OMEN-SED model results as blue lines and observations as black dots"
       style="width:100%; max-width:900px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    OMEN-SED simulations compared with observations at two marine sediment sites. Model results (blue lines) capture changes in organic carbon, oxygen, and nutrient concentrations with sediment depth.
  </div>
</div>

### Global organic carbon burial

The computational efficiency of OMEN-SED allows us to run the model at thousands of locations across the global seafloor. By combining the model with global observations, we can estimate where and how much organic carbon is buried in marine sediments and identify regions that are particularly important for long-term carbon storage.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/OMEN-SED/MAP_Corg_fluxes.png"
       alt="Global organic carbon burial in coastal margin sediments simulated with OMEN-SED."
       style="width:100%; max-width:750px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    Global organic carbon burial in coastal margin sediments simulated with OMEN-SED.
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


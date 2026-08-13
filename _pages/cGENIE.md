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
    The cGENIE Earth-system modelling framework represents interactions between the ocean, atmosphere, marine biogeochemistry, weathering, and sediments. Adapted from an earlier version of Andy Ridgwell (UCR).
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

### Earth-system recovery and climate stability

We used transient cGENIE simulations to investigate how interactions between organic carbon burial, ocean oxygen, nutrient cycling, and climate control Earth-system recovery following massive CO<sub>2</sub> release. As the climate warms, more nutrients enter the ocean, stimulating marine productivity and organic carbon burial. At the same time, ocean oxygen declines due to lower oxygen solubility and increased oxygen demand from organic matter degradation. Reduced ocean oxygen increases phosphorus recycling from marine sediments, making even more nutrients available and strengthening the feedback. Our simulations showed that this can greatly accelerate CO<sub>2</sub> removal and climate recovery. Under some conditions, the feedback becomes so strong that the climate overshoots its initial state and temporarily enters a colder climate. This provides a possible mechanism for some of the extreme cooling events seen in Earth's geological history.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/cGENIE/cGENIE_Science_PRESS_2.png"
       alt="Modeled Earth-system trajectory following a massive carbon dioxide release, showing initial warming followed by a long recovery associated with changing ocean nutrient levels and an overshoot into a cooler climate state."
       style="width:100%; max-width:1200px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
    Sequence of Earth-system changes following a massive CO<sub>2</sub> release. The trajectory traces the modeled evolution of global mean surface temperature (vertical axis and color) and ocean phosphate inventory (horizontal axis) as the Earth system warms and subsequently recovers (Andy Ridgwell/UCR).
  </div>
</div>


---


## Selected publications using cGENIE

**Xu et al. (in revision, Geobiology)**  
*Using idealized cGENIE model worlds to explore how atmospheric oxygen, climate, marine nutrients, organic matter export, and continental configuration interact to control seafloor oxygenation.*

[**Vervoort et al. (2026, *Paleoceanography & Paleoclimatology*)**](https://doi.org/10.1029/2025PA005181) 
*Investigating how astronomical forcing is transformed by carbon-cycle feedbacks and recorded in marine sediments.*

[**Carrapa et al. (2026, *Communications Earth & Environment*)**] (https://doi.org/10.1038/s43247-026-03457-4)
*Exploring how volcanic ash fertilization of the ocean may have influenced marine productivity, ecosystems, and global climate during the Late Miocene.*

[**\* Hülse & \*Ridgwell (2025, Science)**](https://doi.org/10.1126/science.adh7730)  
*Using transient Earth-system simulations to reveal how organic carbon burial and phosphorus recycling can accelerate climate recovery and lead to unexpected climate instability.*

[**Pohl et al. (2023, *Science Advances*)**](https://doi.org/10.1126/sciadv.adg767)  
*Combining cGENIE with an animal physiological model to show how climate and continental configuration restricted marine organisms' geographic ranges, increasing extinction susceptibility during the Early Paleozoic.*

[**Hülse et al. (2021, Nature Geoscience)**](https://doi.org/10.1038/s41561-021-00829-7)  
*Combining cGENIE simulations with geological observations to show how warming, enhanced nutrient recycling, and expanding ocean euxinia contributed to the end-Permian mass extinction.*

[**Hülse et al. (2019, Paleoceanography and Paleoclimatology)**](https://doi.org/10.1029/2018PA003470)  
*Coupling OMEN-SED to cGENIE to investigate how organic matter sulfurization affects carbon burial, ocean oxygenation, and recovery from Ocean Anoxic Event 2.*


See my [Publications](/publications/) page for the full publication list.

\* These authors contributed equally.

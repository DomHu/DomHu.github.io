---
layout: page
title: Other models
permalink: /other-models/
nav: false
---


Beside OMEN-SED and cGENIE, I have contributed to the development and application of other numerical modelling tools for marine sediments and biogeochemistry.

### IMP — Implicit model of Multiple Particles and diagenesis

**IMP** is a 1D sediment model developed by Yoshi Kanzaki to investigate how environmental signals recorded in marine carbonates are altered during burial. The model tracks how signals are mixed or lost near the sediment surface and how they deteriorate deeper in the sediment column.

Unlike models that treat all carbonates in a sediment layer in the same way, IMP can track different groups of carbonate particles with their own properties, such as isotopic composition, solubility, and particle size. This makes it possible to investigate how different styles of sediment mixing and chemical erosion affect the geological record.

My main contribution to IMP was translating the original Fortran model developed by Yoshi into MATLAB [Kanzaki et al. (2021, *GMD*)](https://doi.org/10.5194/gmd-14-5999-2021). The IMP source codes are available on [GitHub](https://github.com/imuds/iMP) under the MIT License.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/IMP_Schematic.png"
       alt="Schematic of the IMP sediment model showing how sedimentary signals are mixed or lost near the sediment surface, deteriorate during burial, and are tracked through successive sediment layers."
       style="width:100%; max-width:550px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
     <b>Tracking sedimentary signals with IMP.</b> The model tracks the preservation of sediment layers through time while accounting for signal mixing, loss, and deterioration during burial. Figure from <a href="https://doi.org/10.5194/gmd-14-5999-2021">Kanzaki et al. (2021)</a>.
  </div>
</div>


### iTURBO2

**iTURBO2** is an updated version of the TURBO/TURBO2 model originally developed by Martin Trauth ([Trauth (1998)](https://www.sciencedirect.com/science/article/pii/S0098300498000193) and [Trauth (2013)](https://www.sciencedirect.com/science/article/pii/S0098300413001350)). iTURBO2 simulates how bioturbation mixes individual sediment particles and alters stratigraphic signals, such as δ<sup>13</sup>C, δ<sup>18</sup>O, or <sup>14</sup>C records preserved in foraminifera. I (re-)introduced an approach to simulate different types and intensities of sediment mixing and to run repeated simulations with randomly generated mixing patterns. This makes it possible to explore how bioturbation and sampling can distort sedimentary records and to estimate the uncertainty associated with these effects. 

The updated MATLAB version is easy to use with input data from Excel files and is openly available from my [github repository](https://github.com/DomHu/iTURBO2) under the MIT License.

<div style="text-align:center; margin: 25px 0 45px 0;">
  <img src="/assets/img/iTURBO2_Schematic.png"
       alt="Schematic of the iTURBO2 model showing the deposition of signal-carrying particles and their mixing by bioturbation within the upper sediment layer."
       style="width:100%; max-width:400px;">
  <div style="font-size:0.9em; margin-top:8px; text-align:center;">
     <b>Simulating sediment mixing with iTURBO2.</b> The model tracks individual signal-carrying particles as they are deposited and mixed by bioturbation, allowing us to explore how sediment mixing alters geochemical and isotope records. Figure from <a href="https://doi.org/10.1016/j.earscirev.2022.104213">Hülse et al. (2022)</a>.
  </div>
</div>



# mango-pipeline

Builds the MANGO dataset — spacecraft observations of Earth's magnetosphere classified by region
(magnetosphere, magnetosheath, solar wind), paired with upstream solar-wind conditions, and
spatially normalised between boundary models — from public archives (CDAWeb, ESA CSA, SSCWeb)
accessed through [speasy](https://github.com/SciQLop/speasy).

The datasets it produces are the ones served by the MANGO server
([space-mango](https://github.com/LaboratoryOfPlasmaPhysics/mango)) and archived on Zenodo.
This package is standalone: it does not depend on `space-mango`.

Status: design phase, no code yet.

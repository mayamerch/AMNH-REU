# AMNH-REU
REU at the American Museum of Natural History, supervised by Dr. Aleksandra Kuznetsova (2021).

We calculated synthetic observations of steady-state and dynamical protoplanetary disk models to discuss the effects of disk substructure on emitted specific radiative intensity, then compared to physical parameters such as surface density and temperature as a metric for disk structure.

**Steady-state models**:
- `powerlaw_model.ipynb`: protoplanetary disk model with of radius 100 AU and gaps between 10-40 AU which deplete the dust density by factor of $10^{-5}$; characterized by power law in surface density profile 
- `cutoff_model.ipynb`: identical to above with added an exponential cutoff at 60 AU
- `surface_density.ipynb`: calculating surface density as a function of disk radius for each steady-state model

**Dynamical models**:
- `dynamical_models.ipynb`: initializing physically motivated disks modeled after the protoplanetary disk that surrounds the star GM Auriga
- `planetary_model.ipynb`: simulates the disk response in the presence of Jupiter-mass planet at 60 AU; processed at t = 5 kyr
- `infall_model.ipynb`: shows the development of substructure due to the impact of infalling cloud material at a radius of 40 AU; processed at t = 25 kyr

**Demo**:
- `continuum_model.ipynb`: continuum model tutorial (regular grid) from `radmc3dPy`

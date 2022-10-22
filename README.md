# Thermodynamic framework for EVo

This is a thermodynamic framework developed by Kilbride et al. (2016) and refined by Yip et al. (2022). 

In this version, we incorporate pre-eruptive exsolved volatile segregation into the thermodynamic model.

This notebook processes output from EVo thermodynamic model (Liggins et al., 2020, 2022) to: 
- visualise magma properties as a function of depth (e.g., volatile content in melt, gas volume fraction, density) 
- calculate observable parameters (e.g., SO₂, volume change and displacement, all normalised by per unit volume erupted)
- *NEW!* simulate pre-eruptive gas accumulation/ loss

To simulate pre-eruptive exsolve volatile segregation, please modify the value of constant k to a number greater than -1 in L424 of dgs_classes.py file in the EVo thermodynamic model.

EVo thermodynamic model: https://github.com/pipliggins/EVo

References:

- Liggins, P., Shorttle, O., & Rimmer, P. B. (2020). Can volcanism build hydrogen-rich early atmospheres?. Earth and Planetary Science Letters, 550, 116546. https://doi.org/10.1016/j.epsl.2020.116546
- Liggins, P., Jordan, S., Rimmer, P. B., & Shorttle, O. (2021). Growth and evolution of secondary volcanic atmospheres: I. Identifying the geological character of warm rocky planets. arXiv preprint arXiv:2111.05161. https://doi.org/10.48550/arXiv.2111.05161
- Yip, S. T. H., Biggs, J., Edmonds, M., Liggins, P., & Shorttle, O. (2022). Contrasting volcanic deformation in arc and ocean island settings due to exsolution of magmatic water. Geochemistry, Geophysics, Geosystems, 23(7), e2022GC010387. https://doi.org/10.1029/2022GC010387
- Yip, S. T. H., Biggs, J., Edmonds, M., Liggins, P., & Shorttle, O. (in submission; this work). The role of pre-eruptive exsolved volatile segregation on volcanic deformation and degassing. 

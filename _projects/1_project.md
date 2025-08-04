---
layout: page
title: Shaping dark photon spectral distortions
description:
img: assets/img/publication_preview/constraints.jpg
importance: 1
category: work
math: true
---


The dark photon \$A'\$ is a hypothetical particle that opens one of the few renormalizable portals between the Standard Model (SM) and the dark sector. There is a significant research effort to detect dark photons with mass \$m\_{A'} \lesssim 10^{-3},\text{eV}\$. While terrestrial experiments, helioscopes, and astrophysical probes have constrained portions of the dark photon parameter space, spectral distortions in the cosmic microwave background (CMB) provide one of the most sensitive tests in the \$m\_{A'} \lesssim 10^{-4},\text{eV}\$ range.

In the early universe, CMB photons were in chemical equilibrium with baryons and followed a blackbody distribution with zero chemical potential. According to \$\Lambda\$CDM, this distribution is largely preserved until today. COBE-FIRAS confirmed this with a deviation no larger than one part in \$10^4\$. Next-generation missions such as PIXIE, PRISM, Voyage 2050, and SPECTER aim to detect distortions as small as \$10^{-10}\$ to \$10^{-8}\$ of the blackbody intensity.

Any exotic process that injects or removes energy after photon decoupling can lead to measurable distortions. In the case of kinetically mixed dark photons, a key process is \$\gamma \rightarrow A'\$ conversion. This occurs most efficiently when the effective plasma mass of the SM photon, set by the free electron density, matches the mass \$m\_{A'}\$ of the dark photon. These resonant conversions dominate the distortion signal.

The effect of \$\gamma \rightarrow A'\$ on the CMB spectrum can be divided into two regimes:

1. \$m\_{A'} \lesssim 10^{-9},\text{eV}\$: Conversion happens after recombination during the free-streaming era. Distortions redshift passively.
2. \$m\_{A'} \gtrsim 10^{-9},\text{eV}\$: Conversion occurs before recombination. In this case, Compton scattering can redistribute the resulting distortion.

Previous treatments assumed that distortions simply redshift after being generated, which underestimates the complexity of thermalization in the pre-recombination era. A more accurate method is to model the distortion using Green’s function techniques tailored to photon injection or removal. This approach accounts for redistribution due to Compton scattering and avoids the simplifying assumption that distortions are purely of \$\mu\$ or \$y\$ type.

We applied the Green’s function formalism to compute the full spectral distortion arising from \$\gamma \rightarrow A'\$ conversions across the \$\mu\$-era, \$y\$-era, and the intermediate \$\mu\$–\$y\$ transition region. In the \$\mu\$-era, corresponding roughly to \$3 \times 10^{-6},\text{eV} \lesssim m\_{A'} \lesssim 5 \times 10^{-5},\text{eV}\$, Compton scattering efficiently redistributes energy. In the \$y\$-era (\$10^{-9},\text{eV} \lesssim m\_{A'} \lesssim 2 \times 10^{-8},\text{eV}\$), redistribution is inefficient. In the transition region (\$2 \times 10^{-8},\text{eV} \lesssim m\_{A'} \lesssim 3 \times 10^{-6},\text{eV}\$), we estimate the distortion conservatively.

Our new bounds on the kinetic mixing parameter \$\epsilon\$ strengthen previous limits by up to a factor of 3. These results are crucial benchmarks for upcoming experiments like DarkSRF, which will test similar mass ranges through complementary methods. Our analysis improves on earlier treatments by incorporating realistic spectral shapes of the distortions—important for future missions with enhanced sensitivity. This spectral signature could serve as a smoking gun for photon-to-dark-photon oscillations, potentially revealing new physics in otherwise inaccessible regions of parameter space.





<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/constraints.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Dark photon constraints from CMB spectral distortions. Solid lines show current COBE-FIRAS bounds (95% CL); dashed lines show future PIXIE projections (assuming perfect foreground removal). Color coding represents different CMB epochs: free-streaming (purple), $y$-era (blue, red), $\mu$-era (orange), and $\mu$-$y$ transition (green). Gray regions show existing constraints from experiments like DarkSRF, XENON1T, and solar/Jupiter/Earth-based bounds. Dotted lines indicate theoretical limitations of the method.
</div>





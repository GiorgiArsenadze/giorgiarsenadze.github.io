---
layout: page
title: Cannibal Dark matter
description:
img: assets/img/candm_constraint.JPG
importance: 3
category: work
math: true
---


One of the more interesting beyond-CDM models is dark matter that undergoes “cannibalistic” number-changing \$3 \rightarrow 2\$ interactions. These models are referred to as Cannibal Dark Matter (CanDM). To illustrate the phenomenology of CanDM, we use a toy model with the following Lagrangian:

$$
\mathcal{L}_\text{CanDM} = \frac{1}{2}(\partial_\mu \phi)(\partial^\mu \phi) - \frac{1}{2}m^2 \phi^2 - \frac{m \kappa}{3!} \phi^3 - \frac{\lambda^2}{4!} \phi^4
$$

This allows for \$2 \leftrightarrow 2\$ interactions (\$\phi\phi \leftrightarrow \phi\phi\$) governed by \$\lambda^2\$ or \$\kappa^2\$, and \$3 \leftrightarrow 2\$ interactions (\$\phi\phi\phi \leftrightarrow \phi\phi\$) governed by \$\kappa\lambda^2\$ or \$\kappa^3\$, ensuring chemical and thermal equilibrium. The specific production mechanism is unimportant for this analysis, as long as it occurs before the era relevant for CMB and large-scale structure formation, and the species is decoupled from other particles thereafter.

As in earlier treatments, we parametrize the thermally averaged \$3 \rightarrow 2\$ cross-section in the nonrelativistic limit with a dimensionless coupling \$\alpha\$. Assuming temperature independence for simplicity:

$$
\langle \sigma_{3 \rightarrow 2} v^2 \rangle \approx \frac{\alpha^3}{m^5} \quad \Rightarrow \quad \Gamma_{3 \rightarrow 2} \approx \frac{\alpha^3}{m^5} n_\text{NR}^2
$$

In this bosonic toy model, the unperturbed phase-space distribution is:

$$
f_\text{NR}(p, \mu, T) \approx \frac{1}{\exp\left(\frac{\sqrt{p^2 + m^2} - \mu}{T}\right)}
$$

In the non-relativistic regime, the number density, energy density, and pressure are given by:

$$
n_\text{NR} = \frac{m^3 e^\zeta}{2\pi^2} \frac{K_2(x)}{x}
$$

$$
\rho_\text{NR} = \frac{m^4 e^\zeta}{2\pi^2} \left( \frac{3K_2(x)}{x^2} + \frac{K_1(x)}{x} \right)
$$

$$
P_\text{NR} = \frac{m^4 e^\zeta}{2\pi^2} \frac{K_2(x)}{x^2} = T n_\text{NR}
$$

with \$x = m/T\$ and \$\zeta = \mu/T\$.

The evolution of \$\zeta\$ and \$x\$ comes from the first two moments of the Boltzmann equation:

$$
\frac{d\zeta}{d \log a} = -3\left(1 + \frac{P}{\rho}\right) - \frac{d \log(\rho e^{-\zeta})}{dx} \frac{dx}{d \log a}
$$

$$
\frac{dx}{d \log a} = - \left( e^{-\zeta} - 1 \right) \frac{\Gamma_{3 \rightarrow 2}}{H} + \frac{3P}{\rho} \frac{d \log(\rho/nm)}{dx}
$$

Solving these gives the background evolution (as shown in Fig. 3a and 3b of the original document). This background evolution can be used to solve matter perturbation equations and examine the effects of CanDM on the matter power spectrum. Compared to CDM, CanDM suppresses the power spectrum at small scales:

$$
\delta' + (1 + w)(\theta - 3\phi') + 3H(c_s^2 - w)\delta = 0
$$

$$
\theta' + H(1 - 3c_a^2)\theta - k^2\left( \psi + \frac{c_s^2}{1 + w} \delta - \sigma \right) = 0
$$

We implemented CanDM into the CLASS Einstein-Boltzmann solver to integrate these equations. After solving and applying existing constraints from Lyman-alpha forest and subhalo mass function data, we extract limits on CanDM parameter space. This constraint is the key result of the study.






<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/candm_constraint.JPG" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Shaded regions show excluded parameter space based on structure formation bounds. The blue and green areas represent updated constraints from the Lyman-𝛼 forest and the subhalo mass function (SHMF). These improve upon earlier bounds (purple region). The red region is excluded by galaxy cluster observations requiring $\sigma/m > 1,\mathrm{cm}^2/\mathrm{g}$.
</div>





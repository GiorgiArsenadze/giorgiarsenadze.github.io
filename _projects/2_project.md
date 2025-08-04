---
layout: page
title: project 2
description: Anomalous Coarsening of Coalescing Nucleoli in Human Cells
img: assets/img/nuleoli_hela.jpg
importance: 2
category: work
giscus_comments: true
math: true
---

Particle coarsening—the process by which small particles become larger—has been studied across many physical and biological systems, ranging from colloids to droplets, and from protein aggregates to liquid condensates. Such studies are critical to understanding a broad set of real-world phenomena. The kinetics of the particle coarsening, aggregation for solid particles and coalescence for liquid droplets, can vary from passive diffusion-limited process, collision-free Ostwald ripening to driven chemically reactive coarsening.

In particular, coarsening in thermal systems has been extensively studied with experiments, theory, and simulations. The time evolution of the particle volume distribution $P(V)$, one of the principal experimental measurables, can be described by the Smoluchowski equation. It relates rates of particle aggregation and dissociation, yielding a characteristic scaling for the given coarsening process. In general, $P(V)$ is transient, as the material supply is finite. However, with a constant injection of material, volume conservation of particles pre/post coarsening, and diffusive dynamics, it has been shown that the system follows the scaling solution $P(V) \propto V^{-1.5}$.

The biggest intracellular liquid droplet is the nucleolus, which resides inside the cell nucleus. The nucleolus is composed of RNA and proteins, and is involved in ribosome biogenesis, cell-cycle regulation, as well as cellular stress response. Nucleoli form at the nucleolar organizing regions (NORs) of the genome, which contain rDNA that is transcribed within the nucleolus. Since there are 10 NORs present in the human diploid genome, human somatic cells contain 10 nucleoli at the beginning of the cell cycle. The nucleoli coalesce over time—leading to droplet coarsening—until they dissolve shortly before mitosis.

Kinetics of nucleolar coalescence is governed by the viscosity of the surrounding chromatin solution. In addition, the nucleolar volume distribution in human cells was found to follow $P(V) \propto V^{-1}$. This differs from $P(V) \propto V^{-1.5}$ for diffusion-limited coalescence with a constant material injection, which was observed in passive droplet systems as well as for nucleoli in X. laevis oocytes. The different scaling of $P(V)$ for nucleoli in human cells suggests a deviation from a diffusion-limited behavior, hinting at a possible role of chromatin in aiding or hampering the nucleolar coalescence. Indeed, such an effect would not be surprising, as human nucleoli remain tethered to chromatin fiber during their lifetime, in contrast to nucleoli in X. laevis oocytes, which are free to diffuse.

When freely moving optogenetic droplets were introduced into human nuclei, they were found to exhibit subdiffusive dynamics due to the surrounding chromatin, with their growth following $r(t) \propto t^{0.12}$. Simulations of freely moving droplets in chromatin network suggest that chromatin arrests droplet growth and coalescence, thus stabilizing the multi-droplet state. Taken together, chromatin clearly impacts both nucleolar dynamics and kinetics of nucleolar coalescence in human cells—yet—its effect on the nucleolar coarsening remains unknown.

The goal of this work is to investigate possible physical mechanism(s) behind the anomalous nucleolar coarsening in human cells. Specifically, we examine the contributions of chromatin, its dynamics and density distribution, to the nucleolar coalescence. To this end, we measure the nucleolar coarsening as a function of the cell cycle in live human cells. Moreover, we simultaneously monitor nucleolar motions as well as dynamics and reorganization of chromatin around the nucleoli before their coalescence. Our data reveal that nucleolar coarsening maintains the anomalous scaling of $P(V) \propto V^{-1}$ during the entire cell cycle. We find a decrease in chromatin concentration in the space between two nucleoli before they coalesce, while at the same time the nucleoli move faster toward each other.

We hypothesize that such a chromatin depletion leads to an effective attractive interaction between the nucleoli. To test this hypothesis, we perform computational simulations of nucleolar coalescence with and without an attractive interaction. We find that an effective attractive force between nucleoli can indeed lead to the anomalous nucleolar coarsening observed in experiments. For simplicity, I will leave out details of these procedures from this report. One can see all of the above in detail in our paper, published in Biophysical Journal.


<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gr1_lrg.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Fluorescent imaging of HeLa cells shows chromatin (green, H2B-GFP) and nucleoli (red, NPM-mApple) during the cell cycle. Nucleoli progressively coarsen over time. Coalescence events show nucleoli approaching and fusing, with volume distributions measured across eight time points. The distribution follows a characteristic scaling of $p(V) \propto V^{-1}$. Volumes were calculated for 141 nucleoli from 35 cells. Analysis distinguishes between fusing (N = 38) and non-fusing (N = 103) nucleoli, normalized to their size at 3 h post-mitosis. Schematics illustrate nucleolar coalescence and chromatin arrangement. Shaded areas represent standard error.
</div>





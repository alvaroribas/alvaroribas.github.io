---
layout: default
title: "Research — Álvaro Ribas"
nav: research
---
Research
{:.eyebrow}

# Protoplanetary disks and planet formation

Planets form in the disks of gas and dust that surround young stars. Their structure — where the material sits, how large the dust grains are, where gaps open up — reflects the physical processes at work. I study these disks across a range of wavelengths and compare the observations with physical models to understand how they evolve and how they form planets.
{:.lead}

Some of the main topics I work on are summarised below. They share a common approach: extracting physical insight from observations, whether for one disk imaged in detail or a large sample at once.

## Planet formation and disk substructures {#planet-formation}

Planets that are still forming are rarely observed directly, but they leave imprints on their disks. In [Ribas et al. 2025 (*Nature Astronomy*)](https://www.nature.com/articles/s41550-025-02576-w) we studied MP&nbsp;Mus, a disk previously thought to be smooth and featureless. New ALMA observations at longer wavelengths, where the disk becomes more transparent, revealed a previously hidden inner cavity and a ring. Combined with a subtle wobble in the star's motion measured by Gaia, this suggested the presence of a young gas giant orbiting close in. The broader message is that substructures may be more common than we thought, often hidden under optically thick emission. In [Ribas et al. 2023](https://ui.adsabs.harvard.edu/abs/2023A%26A...673A..77R/abstract) we had mapped the same disk down to 4&nbsp;au scales at shorter wavelengths, which became the groundwork for that result.

<figure class="figure right">
  <a href="images/mp_mus.png" target="_blank" rel="noopener"><img src="images/mp_mus.png" alt="ALMA continuum images of the MP Mus disk at 3 mm and 1.3 mm"></a>
  <figcaption>ALMA continuum images of MP&nbsp;Mus at 3&nbsp;mm and 1.3&nbsp;mm. A ring and inner cavity (marked) stand out at the longer wavelength, where the disk is more transparent. From Ribas et&nbsp;al. 2025.</figcaption>
</figure>

Not every bright feature is a gap or a trapped clump of dust, though. In [Ribas et al. 2024](https://ui.adsabs.harvard.edu/abs/2024MNRAS.532.1752R/abstract) we looked at the crescent-shaped asymmetries seen in many disks and asked whether they really trace dust overdensities (for instance, dust trapped in a giant vortex) or if they may simply result from the bright, directly illuminated inner wall of a cavity. Our results strongly suggest that many of these asymmetries could in fact be the inner wall.

<figure class="figure left">
  <a href="images/ry_tau_wall.png" target="_blank" rel="noopener"><img src="images/ry_tau_wall.png" alt="ALMA image of the RY Tau disk and a disk-plus-wall model"></a>
  <figcaption>The RY&nbsp;Tau disk seen with ALMA (left) and a disk-plus-wall model (right): the bright arc is reproduced by the directly illuminated inner wall of the cavity. From Ribas et&nbsp;al. 2024.</figcaption>
</figure>

## Machine learning and statistical methods {#machine-learning}

Fitting a physical disk model to data can be very slow: a single radiative-transfer model can take from minutes to hours to compute, and inferring a disk's properties needs thousands of them — which does not scale to the large samples we now have. In [Ribas et al. 2020](https://ui.adsabs.harvard.edu/abs/2020A%26A...642A.171R/abstract) (an *A&A* Highlight) we trained an artificial neural network to emulate those models, turning an hour-long calculation into a fraction of a second. That made it possible to fit disk emission for large samples within a Bayesian framework, and to revisit — and revise — how disk masses are estimated. The same emulator has since been used in other disk studies (for example Rilinger et al. 2023, Xin et al. 2023, and Zamudio-Ruvalcaba et al. 2025).

<figure class="figure right">
  <a href="images/ann_scheme.png" target="_blank" rel="noopener"><img src="images/ann_scheme.png" alt="Diagram of the artificial neural network used to emulate disk model spectra"></a>
  <figcaption>The neural network developed in Ribas et&nbsp;al. 2020: stellar, disk, and dust parameters in, a full spectrum out — fast enough to fit large samples.</figcaption>
</figure>

## The evolution of protoplanetary disks {#evolution}

Disks live for millions of years, so we cannot watch a single one evolve. Instead we compare populations of different ages. The difficulty is that samples assembled from many separate studies are heterogeneous, and that inhomogeneity can masquerade as real evolution. In [Ribas et al. 2014](https://ui.adsabs.harvard.edu/abs/2014A%26A...561A..54R/abstract) we built a large, uniformly analysed sample of young stars across 22 nearby regions, from the optical to the mid-infrared, and confirmed that disks disperse within ~10&nbsp;Myr, with signs of inside-out clearing.

That same sample let us ask whether stellar mass matters. It does: disks around more massive stars disperse faster ([Ribas et al. 2015](https://ui.adsabs.harvard.edu/abs/2015A%26A...576A..52R/abstract)), which could leave planets around high- and low-mass stars looking rather different. Extending the sample to millimetre wavelengths, we later found that dust grains have already begun to grow — the first step toward planets — in most disks by an age of just ~1&nbsp;Myr ([Ribas et al. 2017](https://ui.adsabs.harvard.edu/abs/2017ApJ...849...63R/abstract)).

<figure class="figure left">
  <a href="images/disk_massevolution.jpeg" target="_blank" rel="noopener"><img src="images/disk_massevolution.jpeg" alt="Disk dispersal as a function of stellar mass and age"></a>
  <figcaption>Disk dispersal as a function of stellar mass and age. From Ribas et&nbsp;al. 2015.</figcaption>
</figure>


## Disks in multiple systems {#circumbinary}

Many stars form in pairs or in larger multiple systems, where a stellar companion can strongly perturb the disk and disperse it before planets have time to form. Even so, some disks in multiple systems are surprisingly long-lived. HD&nbsp;98800 is a good example: four stars arranged as two binaries orbiting one another, where one of the pairs still retains its disk at an age of ~10&nbsp;million years.

In [Ribas et al. 2018](https://ui.adsabs.harvard.edu/abs/2018ApJ...865...77R/abstract) we used the VLA to resolve this disk for the first time and found it to be really compact — only ~5&nbsp;au across — with a central gap ~3&nbsp;au wide carved by the binary. More recently, in [Ribas et al. 2026](https://doi.org/10.1093/mnras/stag641) we found evidence for large dust grains and a possible dust trap. I have studied related circumbinary and multiple systems too, including V892&nbsp;Tau and the TWA&nbsp;3 triple.

<figure class="figure left">
  <a href="images/hd98800b.png" target="_blank" rel="noopener"><img src="images/hd98800b.png" alt="ALMA/VLA observations and model of the disk around HD 98800B"></a>
  <figcaption>The disk around HD&nbsp;98800B (left) and our model (right); a gap ~3&nbsp;au wide has been carved by the central binary. From Ribas et&nbsp;al. 2018.</figcaption>
</figure>

## Transitional and debris disks {#transitional-debris}

I often work on *transitional* disks — disks with large inner holes and gaps that can be signposts of forming planets. Using the Herschel Space Observatory to probe their cold outer regions, we showed how far-infrared data can pin down their structure and mass ([Ribas et al. 2013](https://ui.adsabs.harvard.edu/abs/2013A%26A...552A.115R/abstract), [2016](https://ui.adsabs.harvard.edu/abs/2016MNRAS.458.1029R/abstract)).

<figure class="figure right">
  <a href="images/chamaeleon.jpg" target="_blank" rel="noopener"><img src="images/chamaeleon.jpg" alt="Herschel Space Observatory view of the Chamaeleon I star-forming region"></a>
  <figcaption>The Chamaeleon&nbsp;I star-forming region seen by the Herschel Space Observatory. From Ribas et&nbsp;al. 2013.</figcaption>
</figure>

I am also interested in what comes next: *debris* disks, the dusty remnants of planet formation. In [Ribas et al. 2012](https://ui.adsabs.harvard.edu/abs/2012A%26A...541A..38R/abstract) we searched for warm debris around stars with transiting planets, where collisions in an inner asteroid belt — possibly stirred by the planets themselves — could produce detectable dust. More recently I have been involved in resolving the large exo-Kuiper belt of HD&nbsp;126062 with ALMA (Miley et al. 2025) and in detecting gas in the debris disk of HD&nbsp;36546 (Rebollido et al. 2022).

<hr>

A full, up-to-date list is on my [publications page](publications.html) and on [NASA ADS](https://ui.adsabs.harvard.edu/search/q=orcid%3A0000-0003-3133-3580&sort=date%20desc).
{:.small .muted}

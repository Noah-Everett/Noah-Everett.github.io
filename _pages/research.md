---
layout: archive
title: ""
permalink: /research/
author_profile: true
redirect_from:
  - /reserch
---

<!-- ####################################################################### -->
<!-- ####################################################################### -->
<!-- ####################################################################### -->
<!-- ### --> # Radon Mitiagtion For Rare Event Searches
<!-- ### --> -----
<!-- ### --> <img src="/images/decayChains_2.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
<!-- ### --> Radon stands as a predominant source of background signals in particle physics experiments like LUX-ZEPLIN, XENONnT, SuperCDMS, and nEXO due to the diverse particles and energies yielded by its progeny.
<!-- ### --> While radon is not abundant in many materials, its parent isotopes (radium and thorium) prevail widely due to their significantly longer half-lives.
<!-- ### --> When radium decays, the daughter radon atom can emanate out of materials and reach the detector. 
<!-- ### --> Minimizing radon-induced backgrounds necessitates selecting ultra-clean materials which is done in part using a radon assay system.
<!-- ### --> The data collected from radon assay systems informs the choice of materials and components, but also allows us to make a good estimate of background rates in the detector which is later used to inform physics analyses.
<!-- ### --> 
<!-- ### --> <details markdown="1"><summary><b>Projects</b></summary>
<!-- ### --> {: .notice}
<!-- ### --> 
<!-- ####################################################################### -->
<!-- ### --> 
<!-- ### --> ### Improving Radon Assay Data Analysis With Complete Decay History Fitting 
<!-- ### --> <!-- for [nEXO](https://nexo.llnl.gov) -->
<!-- ### --> <img src="/images/radonEmanationSystem.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
<!-- ### --> **Abstract:**
<!-- ### --> The radon assay system at SLAC employs an electrostatic chamber (ESC) which is biased to drift charged ions to a silicon diode where subsequent alpha decays in the chain are measured and identified by their energies. 
<!-- ### --> Analysis software is used to convert the measured alpha decay rates and energies to initial populations of atoms supporting the emanation of radon.
<!-- ### --> The focus of my work was to develop a new analysis method for the radon assay system at SLAC.
<!-- ### --> This new fitting method makes use of the full history of the assay run, which significantly reduces the required assay time, allowing SLAC to assay nEXO’s components faster leading to a reduction in nEXO’s development and assembly time.
<!-- ### --> To achieve this, I developed a Monte Carlo simulation of the radon assay system to test the new fitting method.
<!-- ### --> <br><br>
<!-- ### --> Advisor: Brian Mong, SLAC National Accelerator Laboratory
<!-- ### --> {: .notice}
<!-- ### --> 
<!-- ####################################################################### -->
<!-- ### --> 
<!-- ### --> ### Environmental Monitoring System for Cleanrooms [Repository](https://github.com/Noah-Everett/Cleanroom-Monitoring-System){: .btn .btn--info .btn--small}{: .align-right}
<!-- ### --> <!-- ### Radon Assay for [LZ](https://lz.lbl.gov) and [SuperCDMS](https://supercdms.slac.stanford.edu) -->
<!-- ### --> <img src="/images/Cleanroom Environmental Monitoring System.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
<!-- ### --> **Abstract:**
<!-- ### --> The Radon Group at South Dakota Mines is actively engaged in radon assay services for LZ and SuperCDMS, all while pioneering a cutting-edge radon mitigation system.
<!-- ### --> As part of this endeavor, the group has developed an ultra-low-radon cleanroom.
<!-- ### --> In support of this initiative, I designed an environmental monitoring system tailored for the ultra-low-radon cleanroom. 
<!-- ### --> This system is responsible for tracking parameters such as temperature, humidity, volatile organic compounds, and dust levels inside the cleanroom.
<!-- ### --> The system uses a Raspberry Pi and an array of four sensors to monitor these parameters.
<!-- ### --> This project allowed me to write all the system code, assemble the system, and install it within the cleanroom where it has been in continuous operation since.
<!-- ### --> <br><br>
<!-- ### --> Advisor: Richard Schnee, South Dakota Mines, Physics Department
<!-- ### --> {: .notice}
<!-- ### --> 
<!-- ### --> </details>
<!-- ####################################################################### -->
<!-- ####################################################################### -->
<!-- ####################################################################### -->

# Accelerator Neutrino Neutron Interaction Experiment ([ANNIE](https://annie.fnal.gov))
-----
<img src="/images/ANNIE_P2.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
ANNIE is a 26-ton gadolinium-doped water Cherenkov detector on the Booster Neutrino Beam (BNB) at Fermilab. 
The primary physics goal of ANNIE is to make precision measurements of the number of final state neutrons from neutrino interactions in water to improve the systematic uncertainties of next-generation long-baseline neutrino experiments. 
In addition, ANNIE is also doing detector R&D on new Large Area Picosecond PhotoDetectors (LAPPDs) and Water-based Liquid Scintillator (WbLS) detector medium.
The ANNIE collaboration consists of more than 40 collaborators from 19 institutions and 2 national labs in 5 countries.

<details markdown="1"><summary><b>Projects</b></summary>
{: .notice}

### Likelihood-based Charged Lepton Track Reconstruction for ANNIE [Unpublished Note](https://drive.google.com/file/d/1gJ4Q9nf95HFrh1kvbQ8kRs_wbEg4qGYq/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right}[Conference Talk](https://drive.google.com/file/d/1wrQdlk9Nq2UBFrWUvCNwEko1KyvNWf5g/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/Screenshot 2023-07-23 at 12.21.03 AM.png" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract:** 
To achieve ANNIE’s ambitious physics goals, while fully accommodating its unique R&D campaign, a new reconstruction method is needed.
To this end, I am developing a new likelihood-based reconstruction method for charged lepton tracks in ANNIE.
This reconstruction method will also allow for detailed studies of the current ANNIE detector itself, along with future detector configurations.
<br><br>
Advisor: Jingbo Wang, South Dakota Mines, Physics Department
{: .notice}

### Feasibility Study For Neutrino-Argon Interaction Measurement in ANNIE
<img src="/images/Ev-nfn_v06.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract:**
The Deep Underground Neutrino Experiment (DUNE) aims to measure the neutrino CP-violating phase and determine the mass ordering, using the Liquid Argon Time Projection Chamber (LArTPC) technology. 
These measurements rely on the precise reconstruction of the incoming neutrino energy. 
However, the nuclear effects on neutrino-nucleus interactions are not well understood in argon, which could affect the precision of the experiment. 
Of particular interest, the measurement of the number of final-state neutrons from neutrino interactions can help constrain the theoretical neutrino-nucleus interaction models. 
To study neutrino-argon interactions, we propose to use the currently existing Accelerator Neutrino Neutron Interaction Experiment (ANNIE) at the Booster Neutrino Beam (BNB) at Fermilab. 
ANNIE is a water-based neutrino detector but can be modified to study neutrino-argon interactions such as those in DUNE. 
A feasible experimental strategy is to deploy a liquid argon target at ANNIE's fiducial volume location.
To this end, I am performing a simulation-based feasibility study to determine the potential of ANNIE to measure neutrino-argon interactions.
<br><br>
Advisor: Jingbo Wang, South Dakota Mines, Physics Department
{: .notice}

</details>

# Isomorphisms For Projective Plane/Space Constructions
-----
<img src="/images/IRL-PP-Example copy.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
Projective geometry is a non-Euclidean form of geometry in which the parallel postulate does not hold such that parallel lines do not exist.
While less utilized beyond pure mathematics due to the dominance of Euclidean space's familiarity, projective geometry possesses a subtle resonance with reality.
Consider parallel train tracks that seemingly converge at an infinitely distant point on the horizon. 
This optical illusion mirrors projective geometry's essence—a convergence of elements towards a distant, conceptual infinity. 
This abstraction not only offers insight into the real world but also provides a geometric meaning to infinity.

<details markdown="1"><summary><b>Projects</b></summary>
{: .notice}

### Isomorphisms for Real Projective Plane Constructions [Colloquium Talk](https://drive.google.com/file/d/1mbCr02dh0jQaNMz0tAHfIq6IUzCV5Bcz/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right} [Preprint](https://arxiv.org/pdf/2403.01049.pdf){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/plots2_constructs2.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract:** 
The real projective plane ($\mathbb{R}\mathbb{P}^2$) has three well known isomorphic constructions:
the extended Euclidean plane, unit (hemi)sphere, and $\mathbb{R}^3$ vector space.
Isomorphisms that map between these descriptions of $\mathbb{R}\mathbb{P}^2$ are not commonly known.
Thus, we find isomorphisms that map between these three constructions.
Additionally, we propose several interesting uses of these constructions and their isomorphisms in classical physics and optical detectors commonly used in particle physics.
<br><br>
Advisor: Patrick Fleming, South Dakota Mines, Mathematics Department
{: .notice}

</details>

# Optical Detector Design
-----
<img src="/images/exampleLens-7.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
Within the field of particle physics, optical-based detectors find extensive utility in collision experiments, neutrino detection, and dark matter investigations. 
This preference for optical detectors is driven by the ubiquitous generation of photons in particle physics processes, rendering them a natural fit for particle identification. 
Furthermore, leveraging our comprehensive understanding of light's behavior and manipulation, derived from our visual reliance on light, holds promise for synergizing optical science with particle physics. 
The potential amalgamation of furthera optical insights with particle physics could potentially lead to enhanced sensitivity in both present and future experimental pursuits.

<details markdown="1"><summary><b>Projects</b></summary>
{: .notice}

### Using Direction Sensitive Photosenors for Detailed Topological Reconstruction in Unsegmented Scintillation Detectors Without Drift Field [Repository](https://github.com/Noah-Everett/G4-DSPD-Detector-Sim){: .btn .btn--info .btn--small}{: .align-right} [Colloquium Talk](https://drive.google.com/file/d/1w_vbpNVOP2iSmlIQktngJjMJIWB8cnNv/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/Screenshot 2023-08-06 at 11.01.07 PM.png" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract:**
Monolithic scintillation detectors are a common choice for particle physics experiments due to their high light yield and scalability.
However, without the use of electric drift fields these detectors lack the fine-grained topological reconstruction capabilities of segmented detectors.
In this work, I propose a novel method for fine-grained topological reconstruction in homogeneous, unsegmented scintillation detectors without the use of large electric fields used to drift charged particles such as those in NEXT, MicroBooNE, DUNE, etc.
This is made possible using a combination of traditional photosensors combined with a lens system which converts the direction of the incident photon into a physical position measurable by a photosensor.
I call this system a Direction Sensitive PhotoDetector (DSPD).
To test this idea, I have developed a Geant4 simulation of a XLZD-sized detector ($\sim40$ tonnes) outfitted with DSPDs.
I have also developed several reconstruction algorithms to give a preliminary estimate of the performance of this system.
{: .notice}

### Analytical Meridional, Non-Paraxial Ray Tracing [Preprint](https://inspirehep.net/files/2b5cca16499156c122d1ac1970bfcded){: .btn .btn--info .btn--small}{: .align-right} [Repository](https://github.com/Noah-Everett/Analytical-Meridional-Non-Paraxial-Ray-Propagation){: .btn .btn--info .btn--small}{: .align-right}

<img src="/images/fig.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left> 
**Abstract:**
The study of light propagation in optical systems is crucial for various scientific and technological applications.
The paraxial (small angle) approximation is widely used and is easily accessible both online and through introductory optics textbooks owing to it providing an elegant ray propagation method in the form of matrices. 
However, the paraxial approximation fails to accurately describe light behavior at non-small angles or with surfaces (lenses or mirrors) which are not approximately linear and perpendicular to the optical axis.
To this end, I present an analytical method for non-paraxial, meridional ray tracing through a system of basic geometric surfaces derivable from a generalized ellipse; 
i.e. the most general ray tracing method for a meridional (2-dimensional) system comprised of elliptical, circular, and linear surfaces. 
This work is meant as a non-small angle generalization of standard ray tracing for geometric optics.
{: .notice}

</details>

# Beyond The Standard Model Theory
-----
<img src="/images/A'.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
Beyond the Standard Model (BSM) Theory is a term used for theoretical developments needed to explain the deficiencies of the Standard Model, such as the origin of mass, the strong CP problem, neutrino oscillations, matter-antimatter asymmetry, and dark matter. 
BSM Theory seeks to extend the Standard Model to address these issues, often introducing new particles, interactions, or principles in the process.
Phenomenology is a crucial aspect of BSM Theory, focusing on the application of theoretical physics to experimental observations. 
It involves making predictions based on BSM theories and then testing these predictions through experiments. 
This iterative process between theory and experiment is key to advancing our understanding of the universe.

<details markdown="1"><summary><b>Projects</b></summary>
{: .notice}

### Search for Visible Dark Photon Decay in SciBooNE and ANNIE [Preprint](https://drive.google.com/file/d/1UrEw_G6NfJ7BibyNFTMybaOp0IchKtGg/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right} [Poster](https://drive.google.com/file/d/1G_gsscAJoJ-tWmHJFQT10guxsALL04WL/view?usp=sharing){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/reach+exp_sensativity-15.pdf" style="max-height: 250px; max-width: 100%; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract:**
Dark photons ($A'$) are a theorized extension to the Standard Model (SM) which could help explain the mystery of dark matter.
Dark photons acquire small couplings to SM fermions through kinetic mixing with the SM $U(1)$ hypercharge group.
In this work, I investigate using the SciBooNE (Scintillator Booster Neutrino Experiment) and ANNIE (Accelerator Neutrino Neutron Interaction Experiment) to search for dark photons.
Due to the relatively low energy of the Booster Neutrino Beam, we limit our study to dark photons produced via $\pi^0\to\gamma A'$ requiring $m_{A'}\leq m_{\pi^0}/2$.
This subsequently limits the dark photons decay modes to only $A'\to e^+e^-$ as we assume $m_{A'} < 2m_\chi$.
We present the expected sensitivity of SciBooNE to dark photons with these constraints and find that it does not probe any unexcluded parameter space.
While SciBooNE may not be useful for probing this specific model for beyond the standard model (BSM) physics, we should strive to make full use of all experiments, both current and past, to further advance physics.
<br><br>
Advisor: Patrick Fox, Fermi National Accelerator Laboratory, Theoretical Physics Department
{: .notice}

</details>
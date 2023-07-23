---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /reserch
---

<!-- <img src="/images/IMG_3566.png" alt="SLAC's nEXO Group" width="300">
<img src="/images/CRM_diagram_complete.pdf" alt="Cleanroom Environmental Monitoring System" width="300"> -->

### Search for Dark Photon Decay Via $A'\to\ell^+\ell^-$ in SciBooNE and ANNIE
<img scr="/images/TOF_LAB.pdf" style="max-height: 250px; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract** here
{: .notice--info}

### Analytical Meridional, Non-Paraxial Ray Tracing
<img scr="/images/exampleLens-7.pdf" style="max-height: 250px; margin-right: 16px; margin-bottom: 10px" align=left>
**Abstract** here
{: .notice--info}


<!-- ### Multifidelity Monte Carlo Estimation for Efficient Uncertainty Quantification in Climate-Related Modeling  [Preprint](http://arxiv.org/abs/...#){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/ice_mfmc.png" style="max-height: 250px; max-width: 250px; margin-right: 16px; margin-bottom: 10px" align=left>  **Abstract:** Uncertainties in an output of interest that depends on the solution of a complex system (e.g., of partial differential equations with random inputs) are often, if not nearly ubiquitously, determined in practice using Monte Carlo (MC) estimation.  While simple to implement, MC estimation fails to provide reliable information about statistical quantities (such as the expected value of the output of interest) in application settings such as climate modeling for which obtaining a single realization of the output of interest is a costly endeavor.  Specifically, the dilemma encountered is that many samples of the output of interest have to be collected in order to obtain an MC estimator having sufficient accuracy; so many, in fact, that the available computational budget is not large enough to effect the number of samples needed. To circumvent this dilemma, we consider using multifidelity Monte Carlo (MFMC) estimation which leverages the use of less costly and less accurate surrogate models (such as coarser grids, reduced-order models, simplified physics, interpolants, etc.) to achieve, for the same computational budget, higher accuracy compared to that obtained by an MC estimator or, looking at it another way, an MFMC estimator obtains the same accuracy as the MC estimator at lower computational cost.  The key to the efficacy of MFMC estimation is the fact that most of the required computational budget is loaded onto the less costly surrogate models, so that very few samples are taken of the more expensive model of interest.  We first provide a more detailed discussion about the need to consider an alternate to MC estimation for uncertainty quantification.  Subsequently, we present a review, in an abstract setting, of the MFMC approach along with its application to three climate-related benchmark problems as a proof-of-concept exercise.
<br><br>
(Joint with [Max Gunzburger](https://people.sc.fsu.edu/~mgunzburger/), [Lili Ju](https://people.math.sc.edu/ju/), [Rihui Lan](https://scholar.google.com/citations?user=qkMD9tsAAAAJ&hl=en), and [Zhu Wang](https://people.math.sc.edu/wangzhu/).)
{: .notice--info}

### A Multifidelity Monte Carlo Method for Realistic Computational Budgets  [Preprint](http://arxiv.org/abs/2206.07572#){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/mfmc_alg_pic.png" style="max-height: 250px; max-width: 250px; margin-right: 16px; margin-bottom: 10px" align=left>  **Abstract:** A method for the multifidelity Monte Carlo (MFMC) estimation of statistical quantities is proposed which is applicable to computational budgets of any size.  Based on a sequence of optimization problems each with a globally minimizing closed-form solution, this method extends the usability of a well known MFMC algorithm, recovering it when the computational budget is large enough. Theoretical results verify that the proposed approach is at least as optimal as its namesake and retains the benefits of multifidelity estimation with minimal assumptions on the budget or amount of available data, providing a notable reduction in variance over simple Monte Carlo estimation.
<br><br>
(Joint with [Max Gunzburger](https://people.sc.fsu.edu/~mgunzburger/), [Lili Ju](https://people.math.sc.edu/ju/), and [Zhu Wang](https://people.math.sc.edu/wangzhu/).)
{: .notice--info}

### Energetically Consistent Model Reduction for Metriplectic Systems  [Preprint](https://arxiv.org/abs/2204.08049#){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/gas_containers_FOMs.png" style="max-height: 250px; max-width: 250px; margin-right: 16px; margin-bottom: 10px" align=left>  **Abstract:** The metriplectic formalism is useful for describing complete dynamical systems which conserve energy and produce entropy.  This creates challenges for model reduction, as the elimination of high-frequency information will generally not preserve the metriplectic structure which governs long-term stability of the system.  Based on proper orthogonal decomposition, a provably convergent metriplectic reduced-order model is formulated which is guaranteed to maintain the algebraic structure necessary for energy conservation and entropy formation.  Numerical results on benchmark problems show that the proposed method is remarkably stable, leading to improved accuracy over long time scales at a moderate increase in cost over naive methods.  
<br>
(Joint with [Max Gunzburger](https://people.sc.fsu.edu/~mgunzburger/), [Lili Ju](https://people.math.sc.edu/ju/), and [Zhu Wang](https://people.math.sc.edu/wangzhu/).)
{: .notice--info}

### Comparing Neural Architectures for Reduced-Order Modeling  [Preprint](https://arxiv.org/abs/2110.03442#){: .btn .btn--info .btn--small}{: .align-right} [Read More](/autoencoder-rom/){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/gcnnRom.pdf" style="max-height: 250px; max-width: 250px; margin-right: 16px" align=left>  **Abstract:** The popularity of deep convolutional autoencoders (CAEs) has engendered new and effective reduced-order models (ROMs) for the simulation of large-scale dynamical systems.  Despite this, it is still unknown whether deep CAEs provide superior performance over established linear techniques or other network-based methods in all modeling scenarios.  To elucidate this, the effect of autoencoder architecture on its associated ROM is studied through the comparison of deep CAEs against two alternatives: a simple fully connected autoencoder, and a novel graph convolutional autoencoder.  Through benchmark experiments, it is shown that the superior autoencoder architecture for a given ROM application is highly dependent on the size of the latent space and the structure of the snapshot data, with the proposed architecture demonstrating benefits on data with irregular connectivity when the latent space is sufficiently large.
<br><br>
(Joint with [Max Gunzburger](https://people.sc.fsu.edu/~mgunzburger/), [Lili Ju](https://people.math.sc.edu/ju/), and [Zhu Wang](https://people.math.sc.edu/wangzhu/).)<br>
{: .notice--info}

### Learning the Structure of Level Sets from Sparse Data  [Preprint](https://arxiv.org/abs/2104.14072#){: .btn .btn--info .btn--small}{: .align-right} [Read More](/nll/){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/levset_cartoon.pdf" style="max-height: 250px; width: 250px; margin-right: 16px; margin-bottom: 10px" align=left>  **Abstract:** A dimension reduction method based on the ``Nonlinear Level set Learning'' (NLL) approach is presented for the pointwise prediction of functions which have been sparsely sampled.  Leveraging geometric information provided by the Implicit Function Theorem, the proposed algorithm effectively reduces the input dimension to the theoretical lower bound with minor accuracy loss, providing a one-dimensional representation of the function which can be used for regression and sensitivity analysis.  Experiments and applications are presented which compare this modified NLL with the original NLL and the Active Subspaces (AS) method.  While accommodating sparse input data, the proposed algorithm is shown to train quickly and provide a much more accurate and informative reduction than either AS or the original NLL on two example functions with high-dimensional domains, as well as two state-dependent quantities depending on the solutions to parametric differential equations. 
<br><br>
(Joint with [Max Gunzburger](https://people.sc.fsu.edu/~mgunzburger/), [Lili Ju](https://people.math.sc.edu/ju/), [Yuankai Teng](https://slooowtyk.github.io/), and [Zhu Wang](https://people.math.sc.edu/wangzhu/).)
{: .notice--info}

### Pseudo-Reversible Neural Networks  [Preprint](https://arxiv.org/abs/2112.01438#){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/prnn.png" style="max-height: 250px; max-width: 250px; margin-right: 16px" align=left>  **Abstract:** Due to the curse of dimensionality and limitations on training data, approximating high-dimensional functions is a very challenging task even for powerful deep neural networks. Inspired by the Nonlinear Level set Learning (NLL) method that uses the reversible residual network (RevNet), in this paper we propose a new method for function approximation called Dimension Reduction via Learning Level Sets (DRiLLS). Our method contains two major components: one is the pseudo-reversible neural network (PRNN) module that effectively transforms high-dimensional input variables to low-dimensional active variables, and the other is the synthesized regression module for approximating function values based on the transformed data in the low-dimensional space.  Extensive experimental results demonstrate that DRiLLS outperforms both the NLL and Active Subspace methods, especially when the target function possesses critical points in the interior of its input domain.
<br><br>
(Joint with [Lili Ju](https://people.math.sc.edu/ju/), [Yuankai Teng](https://slooowtyk.github.io/), [Zhu Wang](https://people.math.sc.edu/wangzhu/), and [Guannan Zhang](https://sites.google.com/view/guannan-zhang/home).)
{: .notice--info}

### Active Manifolds: Geometric Data Analysis for Dimension Reduction  [Here](http://proceedings.mlr.press/v97/bridges19a/bridges19a.pdf){: .btn .btn--info .btn--small}{: .align-right} [Read More.](/am/){: .btn .btn--info .btn--small}{: .align-right}
<img src="/images/AMstuff.png" style="max-height: 250px; max-width: 250px; margin-right: 16px" align=left>  **Abstract:** We present an approach to analyze $$C^1(\mathbb{R}^m)$$ functions that addresses limitations present in the Active Subspaces (AS) method of Constantine et al.  Under appropriate hypotheses, our Active Manifolds (AM) method identifies a 1-D curve in the domain (the active manifold) on which nearly all values of the unknown function are attained, and which can be exploited for approximation or analysis, especially when $$m$$ is large (high-dimensional input space).  We provide theorems justifying our AM technique and an algorithm permitting functional approximation and sensitivity analysis. 
Using accessible, low-dimensional functions as initial examples, we show AM reduces approximation error by an order of magnitude compared to AS, at the expense of more computation.  Following this, we revisit the sensitivity analysis by Glaws et al. who apply AS to analyze a magnetohydrodynamic power generator model, and compare the performance of AM on the same data.  Our analysis provides detailed information not captured by AS, exhibiting the influence of each parameter individually along an active manifold.  Overall, AM represents a novel technique for analyzing functional models with benefits including: reducing $$m$$-dimensional analysis to a 1-D analogue, permitting more accurate regression than AS (at more computational expense), enabling more informative sensitivity analysis, and granting accessible visualizations (2-D plots) of parameter sensitivity along the AM. 
<br><br>
(Joint with [Robert Bridges](https://sites.google.com/site/robertbridgeshomepage/), [Christopher Felder](https://www.math.wustl.edu/~cfelder/), and [Miki Verma](https://scholar.google.com/citations?user=1jUa6nwAAAAJ&hl=en).) <br>
{: .notice--info} -->

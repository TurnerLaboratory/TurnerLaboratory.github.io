---
title: Resources
nav:
  order: 3
  tooltip: Data, code, and reagents
---

# Resources
## Software
### Stimpack
*With Minseung Choi, Josh Melander, and Steven Herbst**

[Stimpack on GitHub](https://github.com/ClandininLab/stimpack)

__Stimpack__ is a Python library for visual stimulus presentation and experimental acquisition. It uses ModernGL to render visual scenes that can be composed of many virtual objects, including those for standard visual stimulus classes (e.g. gratings, small spots, bars, spatiotemporal white noise etc.) as well as more "realistic" virtual reality-type stimuli. Stimpack can incorporate inputs and outputs for complex neuroscience experiments, including analog outputs (e.g. for optogenetic activation) and behavioral inputs (e.g. for closed-loop stimulus presentation). If you would like to use Stimpack feel free to try out the examples and reach out to me to discuss deploying it for your experiments.


### Visanalysis
[Visanalysis on GitHub](https://github.com/ClandininLab/visanalysis)

__Visanalysis__ establishes an analysis pipeline and common imaging analysis tools for __Stimpack__ data, allowing biologists to quickly analyze their imaging data without designing analysis pipelines from scratch, with just a little bit of Python knowledge.

***
## Datasets

### *Drosophila* whole-brain structural and functional connectivity
*With Kevin Mann*

From: \*__Turner, M.H.__, \*Mann, K., and Clandinin, T.R. [2021]. The connectome predicts resting state functional connectivity across the Drosophila brain. *Current Biology*. 31 (11), 2386-2394. \*Co-first authors. [PDF](/files/Turner_CurrBio_2021.pdf)

<iframe src="https://widgets.figshare.com/articles/13349282/embed?show_title=1" width="568" height="351" allowfullscreen frameborder="0"></iframe>

This dataset contains whole-brain calcium imaging data of flies in a "resting state" [i.e. not performing some behavior and not being presented with any controlled stimuli], which we can use to measure functional correlations among brain regions. We compared this "functional connectivity" to the structural connectivity present in the *Drosophila* hemibrain connectome (see the excellent Janelia Hemibrain paper [here](https://elifesciences.org/articles/57443) and browse hemibrain connectivity yourself [here](https://www.janelia.org/project-team/flyem/hemibrain)).


### Population imaging of visual responses in optic glomeruli

From: __Turner, M.H.__, Krieger, A., Pang, M.M., and Clandinin, T.R. [2022]. Visual and motor signatures of locomotion dynamically shape a population code for feature detection in Drosophila. *eLife* 11:e82587. [PDF](/files/Turner_eLife_2022.pdf)


[Link to Dryad repository](https://doi.org/10.5061/dryad.h44j0zpp8) / [Code repository on GitHub](https://github.com/mhturner/glom_pop)

This dataset contains pan-glomerulus imaging data of flies presented with various visual stimuli, including panels of synthetic stimuli as well as more naturalistic visual stimuli associated with natural fly walking behavior.

***
## Reagents
### Presynaptically localized GCaMP: syt1-GCaMP6f
From: __Turner, M.H.__, Krieger, A., Pang, M.M., and Clandinin, T.R. [2022]. Visual and motor signatures of locomotion dynamically shape a population code for feature detection in Drosophila. *eLife* 11:e82587. [PDF](/files/Turner_eLife_2022.pdf)

This is a version of the calcium sensor GCaMP6f fused to synaptotagmin 1, which is a presynaptic active zone protein. syt1-GCaMP6f is localized in presynaptic terminals.


__Plasmid__<br>
- pJFRC7-syt1-GCaMP6f ([#190896 on Addgene](https://www.addgene.org/190896/))

__Flies__<br>
- w[*]; P{y[+t7.7] w[+mC]=20xUAS-syt1GCaMP6f}attP40/CyO  ([Stock 95322 at BDSC](https://bdsc.indiana.edu))

- w[*]; PBac{y[+mDint2] w[+mC]=20xUAS-syt1GCaMP6f}VK00005/TM3, Sb[1]  ([Stock 95323 at BDSC](https://bdsc.indiana.edu))
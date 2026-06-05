# renders
A collection of renders I did for scientific and non-scientific purposes with several tools, mostly [Blender](https://www.blender.org/), [ChimeraX](https://www.rbvi.ucsf.edu/chimerax/), [VMD](https://www.ks.uiuc.edu/Research/vmd/), and [python](https://www.python.org/).

## Folding of TRP-cage
The animations here are are related to [this](https://doi.org/10.1021/acs.jpclett.5c02079) publication, where we explored the free energy landscape of folding of small proteins with [OneOPES](https://doi.org/10.1021/acs.jctc.3c00254). Done with Blender and ChimeraX.

<div align="center">
  <kbd>
    <img src="./gifs/video_TRP_FES.gif" width="600">
  </kbd>
  <br>
  <em>Representation of the free energy landscape of TRP-cage, a mini-protein, and the main structures found in the corresponding minima.</em>
</div>
<br>
<div align="center">
  <kbd>
    <img src="./gifs/video_TRP_machine.gif" width="600"> 
  </kbd>
  <br>
  <em>Representation of OneOPES sampling protein conformations, the enhanced sampling method used to explore the free energy landscape of TRP-cage.</em>
</div>

## Activation of ADRB1 in path space
The animation is related to [this](https://doi.org/10.1021/acs.jpclett.5c03834) publication, where we explored the free energy landscape of activation of class A GPCRs with a path-like method.

<div align="center">
  <kbd>
    <img src="./gifs/video_TRP_FES.gif" width="600">
  </kbd>
  <br>
  <em>Representation of the free energy landscape of the mu-opioid receptor sampled with a path CV.</em>
</div>

## Sampling of MEK1/ERK2 kinase complex

These are two videos on the MEK1/ERK2 kinase complex, a work we are now [publishing](https://doi.org/10.64898/2026.01.19.700303). These are two snippets of a set of very long simulations that I did for the thesis defense of the first author of the manuscript. Done with ChimeraX.

<div align="center">
  <kbd>
    <img src="./gifs/video_MEKERK_HIS.gif" width="600">
  </kbd>
  <br>  
  <em>Dynamics of the MEK1/ERK2 complex with a focus on the HIS-HIS interaction at the interface.</em>
</div>
<br>
<div align="center">
  <kbd>
    <img src="./gifs/video_MEKERK_phospho.gif" width="600"> 
  </kbd>
  <br>
  <em>Dynamics of the MEK1/ERK2 complex with a focus on a phosphorylation-compatible distance of the TxY motiv in ERK2 from the ATP in the binding site of MEK1.</em>
</div>

## Host-Guest system

A short animation I did on a host-guest system sampled by OneOPES (represented by the concentric rings) for a coworker of mine, from [this](https://doi.org/10.1021/acs.jctc.4c01112) work. Done with Blender.

<div align="center">
  <kbd>
    <img src="./gifs/video_hostguest.gif" width="400"> 
  </kbd>
  <br>
  <em>Host-Guest system in a bound state. Simple animation of short dynamics.</em>
</div>

## Beta-adrenergic-1 GPCR activation

This animation comes from [this](https://doi.org/10.1021/acs.jpclett.5c02079) publication, where we explored the free energy landscape of activation of a class A GPCR with [OneOPES](https://doi.org/10.1021/acs.jctc.3c00254). Done with Blender.

<div align="center">
  <kbd>
    <img src="./gifs/video_ADRB1.gif" width="500"> 
  </kbd>
  <br>
  <em>Activation of ADRB1, a class A GPCR, a family of membrane protein that transduce signals across membrane. The light moving is a sodium ion reaching a sodium binding spot.</em>
</div>

## Point mutations representation

Tests on how to represent a (cancer-inducing) point mutation in the kinase domain of the epidermal growth factor receptor. The idea was to go for a "morphing" effect. Done with Blender.

<div align="center">
  <kbd>
    <img src="./gifs/video_mutation_simple.gif" width="600">
  </kbd>
  <br>  
  <em>Point mutation, simple.</em>
</div>
<br>
<div align="center">
  <kbd>
    <img src="./gifs/video_mutation_complex.gif" width="600"> 
  </kbd>
  <br>
  <em>Point mutation, bouncy and more detaily.</em>
</div>

## Opening pores

A collection of animations of both dynamics and analysis of a set of simulations where we were dynamically opening a toroidal membrane pore for protein embedding. The idea was to embed BAX, a pro-apoptotic pore ind Done mostly with python (by iteratively printing plots and combining them in a video) and VMD (for real dynamics). MD simulations were run with the great [GROMACS chain coordinate](https://gitlab.com/cbjh/gromacs-chain-coordinate).

<div align="center" style="display:flex; justify-content:center; gap:10px;">
  <kbd>
    <img src="./gifs/video_pore_densities.gif" width="300"> 
    <img src="./gifs/video_pore_side.gif" width="330">
    <img src="./gifs/video_pore_top.gif" width="330">
  </kbd>
  <br>  
  <em>Dynamic opening of a toroidal membrane pore. On the left, density of lipids and solvent as a function of time. Middle and left show the dynamics as the pore opens.</em>
</div>
<br>
<div align="center">
  <kbd>
    <img src="./gifs/video_BAX_3Ddensities.gif" width="800"> 
  </kbd>
  <br>
  <em>Density of lipid heads, lipid tails, and protein projected in 3D for the BAX/toroidal pore system.</em>
</div>
<br>
<div align="center">
  <kbd>
    <img src="./gifs/video_BAX_2Ddensities.gif" width="800"> 
  </kbd>
  <br>
  <em>2D density map of lipids and BAX protein as a hexamer embedded in the bilayer with estimate of minimum diameter of protein and lipid pores and their distribution.</em>
</div>

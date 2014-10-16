# MODEL7817907010: Wang2008_Rilusole_SkeletalMuscleCells

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL7817907010.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL7817907010.git@20140916`

## Usage

Importing the model package.

`import MODEL7817907010 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Riluzole-induced block of voltage-gated Na+ current and activation of BKCa channels in cultured differentiated human skeletal muscle cells.**   
Wang YJ, Lin MW, Lin AA, Wu SN. _Life Sci._ (2008) 82(1-2) pp 11-20; Pubmed
ID: [18068197](http://www.ncbi.nlm.nih.gov/pubmed/18068197) ,  
**Abstract:**   
Riluzole is known to be of therapeutic use in the management of amyotrophic
lateral sclerosis. In this study, we investigated the effects of riluzole on
ion currents in cultured differentiated human skeletal muscle cells (dHSkMCs).
Western blotting revealed the protein expression of alpha-subunits for both
large-conductance Ca2+-activated K+ (BK(Ca)) channel and Na+ channel
(Na(v)1.5) in these cells. Riluzole could reduce the frequency of spontaneous
beating in dHSkMCs. In whole-cell configuration, riluzole suppressed voltage-
gated Na+ current (I(Na)) in a concentration-dependent manner with an IC50
value of 2.3 microM. Riluzole (10 microM) also effectively increased
Ca2+-activated K+ current (I(K(Ca))) which could be reversed by iberiotoxin
(200 nM) and paxilline (1 microM), but not by apamin (200 nM). In inside-out
patches, when applied to the inside of the cell membrane, riluzole (10 microM)
increased BK(Ca)-channel activity with a decrease in mean closed time.
Simulation studies also unraveled that both decreased conductance of I(Na) and
increased conductance of I(K(Ca)) utilized to mimic riluzole actions in
skeletal muscle cells could combine to decrease the amplitude of action
potentials and increase the repolarization of action potentials. Taken
together, inhibition of I(Na) and stimulation of BK(Ca)-channel activity
caused by this drug are partly, if not entirely, responsible for its muscle
relaxant actions in clinical setting.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Wang_Lin_Lin_Wu, 1999, version02**
](http://www.cellml.org/models/wang_lin_lin_wu_2008_version02)  
The original CellML model was created by:  
**Nunns, Geoffrey, Rogan**   
gnunns1(at)jhem.jhu.edu  
The University of Auckland  
Auckland Bioengineering Institute  

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



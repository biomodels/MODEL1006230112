# MODEL1006230112: Vinnakotta2010_TranscientAnoxia_SOLmuscle

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1006230112.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1006230112.git@20140916`

## Usage

Importing the model package.

`import MODEL1006230112 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This a model from the article:  
**Common phenotype of resting mouse extensor digitorum longus and soleus muscles: equal ATPase and glycolytic flux during transient anoxia.**   
Vinnakota KC, Rusk J, Palmer L, Shankland E, Kushmerick MJ. _J Physiol_ 2010
Jun 1;588(Pt 11):1961-83
[20308252](http://www.ncbi.nlm.nih.gov/pubmed/20308252) ,  
**Abstract:**   
Rates of ATPase and glycolysis are several times faster in actively
contracting mouse extensor digitorum longus muscle (EDL) than soleus (SOL),
but we find these rates are not distinguishable at rest. We used a transient
anoxic perturbation of steady state energy balance to decrease phosphocreatine
(PCr) reversibly and to measure the rates of ATPase and of lactate production
without muscle activation or contraction. The rate of glycolytic ATP synthesis
is less than the ATPase rate, accounting for the continual PCr decrease during
anoxia in both muscles. We fitted a mathematical model validated with
properties of enzymes and solutes measured in vitro and appropriate for the
transient perturbation of these muscles to experimental data to test whether
the model accounts for the results. Simulations showed equal rates of ATPase
and lactate production in both muscles. ATPase controls glycolytic flux by
feedback from its products. Adenylate kinase function is critical because a
rise in [AMP] is necessary to activate glycogen phosphorylase. ATPase is the
primary source of H+ production. The sum of contributions of the 13 reactions
of the glycogenolytic and glycolytic network to total proton load is
negligible. The stoichiometry of lactate and H+ production is near unity.
These results identify a default state of energy metabolism for resting muscle
in which there is no difference in the metabolic phenotype of EDL and SOL.
Therefore, additional control mechanisms, involving higher ATPase flux and
[Ca2+], must exist to explain the well-known difference in glycolytic rates in
fast-twitch and slow-twitch muscles in actively contracting muscle.

This model was taken from the [CellML
repository](http://www.cellml.org/models) and automatically converted to SBML.  
The original model was: [ **Vinnakota KC, Rusk J, Palmer L, Shankland E,
Kushmerick MJ. (2010) - version=1.0**
](http://models.cellml.org/exposure/aa821a8dda7e55888bd486f8cbb68791)  
The original CellML model was created by:  
**Geoffrey Nunns**   
gnunns1@jhu.edu  
The University of Auckland  

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



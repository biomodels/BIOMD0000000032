# BIOMD0000000032: Kofahl2004_PheromonePathway

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000032.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000032.git@20140916`


# Model Notes


This a model from the article:  
** Modelling the dynamics of the yeast pheromone pathway. **   
Kofahl B, Klipp E _Yeast_[2004 Jul; Volume: 21 (Issue: 10 )] Page info: 831-50
[15300679](http://www.ncbi.nlm.nih.gov/pubmed/15300679),  
**Abstract:**   
We present a mathematical model of the dynamics of the pheromone pathways in
haploid yeast cells of mating type MATa after stimulation with pheromone
alpha-factor. The model consists of a set of differential equations and
describes the dynamics of signal transduction from the receptor via several
steps, including a G protein and a scaffold MAP kinase cascade, up to changes
in the gene expression after pheromone stimulation in terms of biochemical
changes (complex formations, phosphorylations, etc.). The parameters entering
the models have been taken from the literature or adapted to observed time
courses or behaviour. Using this model we can follow the time course of the
various complex formation processes and of the phosphorylation states of the
proteins involved. Furthermore, we can explain the phenotype of more than a
dozen well-characterized mutants and also the graded response of yeast cells
to varying concentrations of the stimulating pheromone.

  

The model was updated on 21st October 2010, by Vijayalakshmi Chelliah.  
The following changes were made: 1) The model has been converted to SBML l2v4.
2) The model has been recurated and the curation figure was updated (units are
in nanoMolar; but the publication has units in microMolar). Simulations were
done using Copasi v4.6 (Build 32). 3) Notes have been added. 4) Annotation for
one of the species has been corrected (Complex M).

  
  

** [SBML](http://www.sbml.org/) level 2 code generated for the JWS Online project by Jacky Snoep using [PySCeS](http://pysces.sourceforge.net/)   
Run this model online at
[http://jjj.biochem.sun.ac.za](http://jjj.biochem.sun.ac.za/)  
To cite JWS Online please refer to: Olivier, B.G. and Snoep, J.L. (2004) [Web-
based modelling using JWS Online](http://bioinformatics.oupjournals.org/cgi/co
ntent/abstract/20/13/2143), Bioinformatics, 20:2143-2144 **

The following are the four major differences between the original publication
by Kofahl et al and the model that actually is able to replicate the results
as depicted in the publication (those corrections have been made in agreement
with the authors):  
1\. Bar1 is the inactive protease present inside the cell but the publication
wrongly mentions that Bar1 is also the protease that is present on the
extracellular surface.  
The model correctly names the protease in it's different forms by calling
inactive Bar1 within the cell as Bar1, active Bar1 within the cell as Bar1a
and extracellular Bar1 as Bar1aex  
2\. The initial amount of Alpha-factor is given as 1000nM but the model uses a
value of 100nM.  
3\. The value of the paramenter k8 is given as 0.33 but the model uses a value
of 0.033.  
4\. The value of the paramenter k41 is given as 0.002 but the model uses a
value of 0.02.

This model originates from BioModels Database: A Database of Annotated
Published Models
(http://www.ebi.ac.uk/biomodels/).(http://www.ebi.ac.uk/biomodels/). It is
copyright (c) 2005-2010 The BioModels.net Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)



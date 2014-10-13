

# NFkB model M(39,65,90) - most complex model

This is a model of NFkB pathway functioning from hierarchy of models of
decreasing complexity, created to demonstrate application of model reduction
methods proposed in

**Robust simplifications of multiscale biochemical networks. **   
Radulescu O, Gorban A., Zinovyev A., Lilienbaum. A. _BMC Syst Biol_2008:2:86
[18854041](http://www.ncbi.nlm.nih.gov/pubmed/18854041),  
**Abstract:**   
BACKGROUND: Cellular processes such as metabolism, decision making in
development and differentiation, signalling, etc., can be modeled as large
networks of biochemical reactions. In order to understand the functioning of
these systems, there is a strong need for general model reduction techniques
allowing to simplify models without loosing their main properties. In systems
biology we also need to compare models or to couple them as parts of larger
models. In these situations reduction to a common level of complexity is
needed. RESULTS: We propose a systematic treatment of model reduction of
multiscale biochemical networks. First, we consider linear kinetic models,
which appear as "pseudo-monomolecular" subsystems of multiscale nonlinear
reaction networks. For such linear models, we propose a reduction algorithm
which is based on a generalized theory of the limiting step that we have
developed in 1. Second, for non-linear systems we develop an algorithm based
on dominant solutions of quasi-stationarity equations. For oscillating
systems, quasi-stationarity and averaging are combined to eliminate time
scales much faster and much slower than the period of the oscillations. In all
cases, we obtain robust simplifications and also identify the critical
parameters of the model. The methods are demonstrated for simple examples and
for a more complex model of NF-kappaB pathway. CONCLUSION: Our approach allows
critical parameter identification and produces hierarchies of models.
Hierarchical modeling is important in "middle-out" approaches when there is
need to zoom in and out several levels of complexity. Critical parameter
identification is an important issue in systems biology withpotential
applications to biological control and therapeutics. Our approach also deals
naturally with the presence of multiple time scales, which is a general
property of systems biology models.

The models are provided in CellDesigner v3.5 format. The name of the model
M(x,y,z) should be deciphered as following:

x - number of species y - number of reactions z - number of parameters

Simulation protocol: The model can be simulated in CellDesigner directly, or
in any simulator supporting events. The simulation period should be set up in
40 hours (t=144000 sec). The 'signal' event applies signal to the pathway at
the moment t=20 hours=72000 sec. This model reproduces Figure 7c (M(39,65,90))
of the publication.

For additional information please contact Andrei.Zinovyev at curie.fr

This model originates from BioModels Database: A Database of Annotated
Published Models. It is copyright (c) 2005-2009 The BioModels Team.  
For more information see the [terms of
use](http://www.ebi.ac.uk/biomodels/legal.html).  
To cite BioModels Database, please use [Le Novère N., Bornstein B., Broicher
A., Courtot M., Donizelli M., Dharuri H., Li L., Sauro H., Schilstra M.,
Shapiro B., Snoep J.L., Hucka M. (2006) BioModels Database: A Free,
Centralized Database of Curated, Published, Quantitative Kinetic Models of
Biochemical and Cellular Systems Nucleic Acids Res., 34: D689-D691.](http://ww
w.pubmedcentral.nih.gov/articlerender.fcgi?tool=pubmed&pubmedid=16381960)


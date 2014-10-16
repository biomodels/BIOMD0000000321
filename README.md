# BIOMD0000000321: BIOMD0000000321

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000321.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000321.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000321 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Grange2001 - L-dopa PK model

A pharmacokinetics of L-dopa in rats after administration of L-dopa alone
(this model: BIOMD0000000321) or L-dopa combined with a peripheral AADC
(amino-acid-decarboxylase) inhibitor (BIOMD0000000320) has been studied using
noncompartmental analysis.

This model is described in the article:

[A pharmacokinetic model to predict the PK interaction of L-dopa and
benserazide in rats.](http://identifiers.org/pubmed/11587490)

Grange S, Holford NH, Guentert TW

Pharmaceutical Research [2001, 18(8):1174-1184]

Abstract:

**PURPOSE:** To study the PK interaction of L-dopa/benserazide in rats. METHODS: Male rats received a single oral dose of 80 mg/kg L-dopa or 20 mg/kg benserazide or 80/20 mg/kg L-dopa/benserazide. Based on plasma concentrations the kinetics of L-dopa, 3-O-methyldopa (3-OMD), benserazide, and its metabolite Ro 04-5127 were characterized by noncompartmental analysis and a compartmental model where total L-dopa clearance was the sum of the clearances mediated by amino-acid-decarboxylase (AADC), catechol-O-methyltransferase and other enzymes. In the model Ro 04-5127 inhibited competitively the L-dopa clearance by AADC. 

**RESULTS:** The coadministration of L-dopa/benserazide resulted in a major increase in systemic exposure to L-dopa and 3-OMD and a decrease in L-dopa clearance. The compartmental model allowed an adequate description of the observed L-dopa and 3-OMD concentrations in the absence and presence of benserazide. It had an advantage over noncompartmental analysis because it could describe the temporal change of inhibition and recovery of AADC. 

**CONCLUSIONS:** Our study is the first investigation where the kinetics of benserazide and Ro 04-5127 have been described by a compartmental model. The L-dopa/benserazide model allowed a mechanism-based view of the L-dopa/benserazide interaction and supports the hypothesis that Ro 04-5127 is the primary active metabolite of benserazide. 

The model has a species (A-dopa) whose initial concentration is calculated
from a _listOfInitialAssignments_ . While running for the first time the time-
course (24hrs) for this model in COPASI (up to version 4.6, Build 33), the
resulting graph displays only straight lines for all the species. Any
subsequent runs should provide proper plots (i.e. without making any change to
the model, just by clicking the "run" button again).

The above issue is caused by some initial assignments which are not calculated
when COPASI imports the file. This issue should not be present in newer
releases of COPASI.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[MODEL1103250000](http://identifiers.org/biomodels.db/MODEL1103250000) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.



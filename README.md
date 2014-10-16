# BIOMD0000000458: BIOMD0000000458

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000458.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000458.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000458 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Smallbone2013 - Serine biosynthesis

Kinetic modelling of metabolic pathways in application to Serine biosynthesis.

This model is described in the article:

[Kinetic Modeling of Metabolic Pathways: Application to Serine
Biosynthesis](http://identifiers.org/pubmed/23417802)

Kieran Smallbone, Natalie J. Stanford

Methods in Molecular Biology. 2013; 985:113-121

Abstract:

In this chapter, we describe the steps needed to create a kinetic model of a
metabolic pathway using kinetic data from both experimental measurements and
literature review. Our methodology is presented by using the example of serine
biosynthesis in E. coli.

As there are no plots to be reproduced as curation figure, table 6 and 7 that
corresponds to steady state concentration of metabolite and steady state
fluxes of reactions has been reproduced.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000458](http://identifiers.org/biomodels.db/BIOMD0000000458) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.



[![DOI](https://zenodo.org/badge/321306840.svg)](https://zenodo.org/badge/latestdoi/321306840)

# TePIA taxonomy
A taxonomy of Test case Prioritisation Information Attributes

## Note

This repository contains additional material to the paper entitled *A Taxonomy of Information Attributes for Test Case Prioritisation: Applicability, Machine Learning*, accepted for publication in ACM Transactions on Software Engineering and Methodology. DOI: https://doi.org/10.1145/3511805

## Description

The TePIA taxonomy formalises the definition of information attributes suitable for test case priorisation (TCP) in the context of regression testing. The taxonomy was built following a bottom-up approach after analysising 110 TCP methods found in the literature. 

In total, 91 attributes were identified and characterised. The taxonomy has three dimensions and seven categories:

* *Source*, which specifies the origin of the information. Two categories are defined: group and entity.
* *Collection*, which describes how the attribute is obtained. Three categories are defined: artefact, observation and session-dependent.
* *Representation*, which refers to the computational representation of the attribute. Two categories are defined: type and arity.

Details on the taxonomy definition, development and evaluation can be found in the paper. It also includes an analysis of the information attributes appearing in TCP studies with industrial evaluation, as well as those applying machine learning techniques.  

For a detailed analysis of information attributes by dimension, the interested reader is referred to the technical report available [**here**](docs/tepia-taxonomy-tr.pdf).

## Organisation

This repository is organised as follows:

* In [*attributes*](attributes/README.md), we collect the description and characteristics of the information attributes classified using the taxonomy. They are organised by group and entity.
* In [*bib*](bib/README.md), we include the list of references used for the taxonomy development and evaluation. Additional lists of industrial studies and works applying machine learning are provided too.
* In [*references*](references/README.md), we provide the evaluation of each reference (industry or machine learning) with respect to the information attributes. The analysis presented in the paper is based on this content.
* In [*taxonomy*](taxonomy/README.md), you can navigate through the taxonomy dimensions and categories, with links to the attributes belonging to each possible value.

## How to contribute

The taxonomy is open to contributions from researchers and practitiones interested in the area of regression testing, so pull requests and issues are welcome. You can contribute in different ways:

* Adding new references to support the definition of one attribute already defined in the taxonomy. In this case, please check if the attribute description needs to be adapted or extended. 
* Adding new attributes to the taxonomy. In this case, please use the available templates to fully describe the attribute and provide appropriate references.

## Contributors

The TePIA taxonomy is original work by:

* [Aurora Ramírez](https://github.com/aurorarq), University of Córdoba (Spain)
* [Robert Feldt](https://github.com/robertfeldt), Chalmers University of Technology (Sweden)
* [José Raúl Romero](https://github.com/jrromero), University of Córdoba (Spain)

A list of contributions will appear here too. Contact us if you want to contribute or be part of this GitHub organisation.

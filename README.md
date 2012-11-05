PyData Academy
==============

Initiative of Continuum Analytics (http://continuum.io) to provide knowledge
for data scientist curriculum.

Goals:

* Help solve problems in data science
* give insight into data processing for data analysts
* give insight into data analysis for data warehouse engineers

The academy structure is based on *modules*. Modules are short trainings or
presentations and appropriate module content should fit somewhere within 30
minutes to two hours. Finer granularity allows better fitting of overall
training for target customer/audience. Each module has:

description of problems the course skills/knowledge will help to solve (note:
multiple modules can solve one problem) prerequisites: knowledge (even
external, with provided resource links) or other modules follow-up – suggested
next modules list of skills that the learner will gain after taking the module
exercises and example datasets

Contents
--------

The project contains following folders:

* `modules` - knowledge/skill modules
* `data` – shared example datasets and their metadata
* `data/datasets.json` – metadata about the datasets (see below)

Modules
-------

The module directory contains:

* course description (might be contained in the included Python notebooks)
* python scripts
* one or more python notebooks
* `data` directory if the datasets are related only to that particular module
* module metadata in `module.json`

Datasets Metadata
-----------------

Each dataset is accompained by a file with same with `.json` suffix. The file
contains information about the dataset such as:

* dataset source URL
* date of last file download/update from the source (sometimes required by TOS
  of the data provider)
* other information, such as list of fields

Reason for datasets metadata are:

* provide links to original dataset source for more information or other
  similar datasets
* describe the data conteint in more details
* legal requirements

Copyright
=========

(c) 2012 Continuum Analytics.

License: Creative Commons Attribution-ShareAlike 3.0 Unported License

See LICENSE file for more information. 

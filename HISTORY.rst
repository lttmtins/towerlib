.. :changelog:

History
-------

0.1.0 (25-05-2018)
------------------

* First release


0.2.0 (27-07-2018)
------------------

* Refactored code to use entity managers for all tower objects saving a huge amount of network calls and implemented
  filtering

* Removed pipenv locking mechanism as this is broken for python 2.7 completely


0.3.0 (01-08-2018)
------------------

* Added capability to launch job template job


1.0.0 (27-09-2018)
------------------

* Added support for specifying http or https and certificate verifications options
* Extented the editing capabilities of hosts to name, description and enabled status


2.0.0 (16-10-2018)
------------------

* Implemented dynamic attributes in running jobs.
* Implemented cancel capabilities for running jobs.
* Updated the template to python 3.7
* Officially dropped support for python 2.7


2.0.1 (25-10-2018)
------------------

* Update template and dependencies


2.0.2 (25-10-2018)
------------------

* Reverted breaking change for upload script


2.0.3 (29-11-2018)
------------------

* Fixed reference in the package for the right github repo


2.1.0 (29-11-2018)
------------------

* Fixed issue https://github.com/schubergphilis/towerlib/issues/11 with some organization entities

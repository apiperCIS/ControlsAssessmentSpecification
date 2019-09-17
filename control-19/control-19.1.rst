19.1: Document Incident Response Procedures
=========================================================
Ensure that there are written incident response plans that define roles of personnel as well as phases of incident handling/management.

.. list-table::
	:header-rows: 1

	* - Asset Type 
	  - Security Function
	  - Implementation Groups
	* - N/A
	  - N/A
	  - 1, 2, 3

Status
------
Draft

Inputs
-----------
#. Incident response plan

Operations
----------
#. Determine whether an incident response plan document exists (becomes M1)
#. If the document exists, then perform a manual review of the incident response plan to determine if the plan defines incident response roles (becomes M2) and if the plan defines incident handling/management phases (becomes M3)

Measures
--------
* M1 = binary value indicating if an incident response plan document exists; 1 if document exists, 0 if not
* M2 = binary value indicating if the document defines incident response roles; 1 if roles are defined, 0 if not
* M3 = binary value indicating if the document defines incident handling/management phases; 1 if phases are defined, 0 if not

Metrics
-------

Existence
^^^^^^^^^
.. list-table::

	* - **Metric**
	  - | Binary value indicating if there is an incident response plan document that defines
	    | the roles of personnel as well as phases of incident handling/management.
	    | 1 if all 3 criteria are met, 0 if at least one is not met
	* - **Calculation**
	  - :code:`M1 AND M2 AND M3`

.. history
.. authors
.. license

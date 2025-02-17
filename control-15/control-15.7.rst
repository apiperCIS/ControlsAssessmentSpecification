15.7: Leverage the Advanced Encryption Standard (AES) to Encrypt Wireless Data
==============================================================================
Leverage the Advanced Encryption Standard (AES) to encrypt wireless data in transit.

.. list-table::
	:header-rows: 1

	* - Asset Type 
	  - Security Function
	  - Implementation Groups
	* - Network
	  - Protect
	  - 1, 2, 3

Status
------
Draft

Dependencies
------------
* Subcontrol 1.4: Maintain Detailed Asset Inventory
* Subcontrol 1.5: Maintain Asset Inventory Information

Inputs
-----------
#. List of wireless devices
#. List of AES-capable wireless devices

Operations
----------
#. For each AES-capable wireless device, collect cipher suite configuration

Measures
--------
* M1 = Number of AES-capable devices configured to use non-AES ciphers
* M2 = Number of AES-capable devices

Metrics
-------

Coverage
^^^^^^^^
.. list-table::

	* - **Metric**
	  - What percentage of AES-capable devices still support less-than-secure cipher suites?
	* - **Calculation**
	  - :code:`M1 / M2`

.. history
.. authors
.. license
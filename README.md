# Extract user device information from Cisco AVPair

This is the guide for extracting user device information from a Cisco Radius request packet for put to the database.

# Tested on

Radius Version 3.0.4
Cisco ASA 9.2

# Installation

- Add file ``add-custom-avp`` to ``/etc/raddb/policy.d`` folder.
- Add the content of dictionary file into the ``/etc/raddb/dictionary`` file.
- Add ``add-custom-avps`` to the preacct section

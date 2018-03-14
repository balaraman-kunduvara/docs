|opal-node-soap build status| |npm (scoped)|

opal-node-soap
==============

**This module is part of the OPAL framework**

**Nodes:** \* soap service

**Soap Service** Connects to a soap service and provides the response.

**Inputs:**

-  **Name**: A Name for this read-excel instance
-  **Url**: Specify the url for soap request
-  **Method**: Specify the methods to invoke based on the wsdl
-  **Parameters**: Specify the parameters in json format
-  **Headers**: Specify the header for the request

**Outputs:**

``msg.error`` When an error happens contains the error message from the
read operation ``msg.payload`` contains the data read from spreadsheet

.. |opal-node-soap build status| image:: https://frozen-fortress-98851.herokuapp.com/telligro/opal-nodes/5/badge?subject=build
   :target: https://travis-ci.org/telligro/opal-nodes
.. |npm (scoped)| image:: https://img.shields.io/npm/v/opal-node-soap.svg
   :target: https://www.npmjs.com/package/opal-node-soap

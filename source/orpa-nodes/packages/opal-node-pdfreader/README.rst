|opal-node-pdfreader build status| |npm (scoped)|

opal-node-pdfreader
===================

**This module is part of the OPAL framework**

**Nodes:** \* read pdf

**Read PDF** Opens an pdf from a specified location and reads the
contents. The contents can then be passed to downstream node or saved to
a store variable.

**Inputs:** \* **Name**: A Name for this instance \* **File Path**:
choose the location from where the pdf can be read \* **Preprocess**:
specify if pdf document needs to be processed, optionally based on rules
specified.

**Output Formats:** The output of the read operation can be a JSON

**Outputs:** ``msg.error`` When an error happens contains the error
message from the read operation ``msg.payload`` contains the data read
from pdf

.. |opal-node-pdfreader build status| image:: https://frozen-fortress-98851.herokuapp.com/telligro/opal-nodes/8/badge?subject=build
   :target: https://travis-ci.org/telligro/opal-nodes
.. |npm (scoped)| image:: https://img.shields.io/npm/v/opal-node-pdfreader.svg
   :target: https://www.npmjs.com/package/opal-node-pdfreader

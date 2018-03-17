
Getting Started
===============

Let us get the tool installed. You can refer to the steps provided in the :ref:`rst_setup`

Terms
-----
**Node**- A action that is performed. Nodes are available in the palette. Read the opalnodes_ documentation to view all nodes.

**Properties** - The properties of a node are the list of attributes or values that is required for executing a node. They are configured through the editor and passed to the run-time as part of the generated json configuration.

**Module** - A collection of related nodes that are published together to the repository. They are installed and managed as a collection and they mostly have their own palette category.

**Flow** -  A sequence of nodes that represent tasks performed on various resources. The resources maybe UI based like TextField, Button etc or Non-UI resources like File, Webservice, Email.

**Context** - Refers to the state that is available to a node. This could be any valid JS types. There are 3 types of context namely; Global, Flow and Node.

**Project** - A collection of flows that contains a deployed unit. Typically a process to be automated

**Editor** - The user interface that is used to compose flows. Editor has sections to define flows and resources. It shows debug messages, help associated with various nodes and managing projects.Flows are composed by configuring nodes and connecting them together as the process dictates.

**Runtime** - The engine that executes the flow once it is deployed from the Editor

**Object Finder** -  The component integrated with studio that allows finding UI objects on various types of application.


Opal Nodes
----------
.. _opalnodes:

.. toctree::
   :glob:

   packages/**/README

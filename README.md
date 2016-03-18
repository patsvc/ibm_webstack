#IBM Web Stack Pattern

This repository contains the blueprint for the IBM Web Stack pattern in IBM Bluemix. The IBM Web Stack includes a high-availability IBM WebSphere App Server, an IBM HTTP server, and a high-availability IBM DB2 database.

The _ibm_webstack.yaml_ file is a HEAT Orchestration Template that contains definitions of the parameters and resources that are required to provision this stack to Bluemix. The stack components are provisioned into the Bluemix VM service by using Salt formulas that are only accessible through Bluemix.

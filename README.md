#IBM Web Stack Pattern

This repository contains the blueprint for the IBM&reg; Web Stack pattern in IBM Bluemix&reg;. The IBM Web Stack pattern includes a high-availability IBM WebSphere&reg; App Server, an IBM HTTP server, and a high-availability IBM DB2 database.

The _ibm_webstack.yaml_ file is a HEAT Orchestration Template that contains definitions of the parameters and resources that are required to provision this stack to Bluemix. The stack components are provisioned into the Bluemix Virtual Servers service by using Salt formulas that are only accessible through Bluemix.

#Text for the Bluemix Service Tile

Use this blueprint to quickly provision and deploy a three-tier web application.
* The blueprint is predefined with the stack components and architecture, including a high-availability IBM&reg; WebSphere&reg; App Server, an IBM HTTP server, and a high-availability IBM DB2&reg; database.
* You can customize the blueprint to meet your application needs. Add your application components to the stack, and then quickly the stack into the Bluemix VM service and iterate changes in the live environment.
* Your iterative changes to the blueprint and application source code are stored in Git repositories. By storing your infrastructure and application code together, you can easily standardize, maintain, and replicate your environments across development, testing, and production environments.



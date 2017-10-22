BAKER: A TOSCA Templates marketplace and orchestration RESTful service for Openastack based Cloud infrastructures
==========

BAKER-TTMOS is a RESTful marketplace web service implementing a public marketplace solutiontogether with an orchestration engine for easily deploying TOSCA based templates on top of Openstack infrastructures via OAuth2. The architecture consists of TTMOS Marketplace backend solution that includes a Brokering service that accommodates marketplace requests, together with a Marketplace frontend interface (https://github.com/NAMGroup/BAKER-TTMOS-Web), and a client application management tool (https://github.com/NAMGroup/baker-client) for the various end-user devices/machines that will be supported. 

BAKER-TTMOS is a RESTful backend service build in java. Currently it runs in the Jetty container and needs MySQL to persist data. Apache CXF is used to implement the RESTful interface and Apache SHIRO as the Authentication and Authorization framework.  A java implementation for openstack API is used called woorea to access resources on an Openstack infrastructure.
Main offered services are:
-	management of users and their resources
-	management of TOSCA archives (or TOSCA Cloud Service Archive, or “CSAR”): a package artifact that contains a TOSCA service template and other artifacts usable by a TOSCA orchestrator to deploy an application.
-	management of the platform
-	brokering, orchestrating and provisioning on target virtual machines. A so called TOSCA orchestrator (also called orchestration engine): A TOSCA processor that interprets a TOSCA service template or a TOSCA CSAR in order to instantiate and deploy the described application in a Cloud.
-	Keystone login
-	management of TOSCA applications


Licenses
--------

The license for this software is [Apache 2 v2.1](./src/license/header.txt).

Contact
-------

For further information on collaboration, support or alternative licensing, please contact:

* Website: http://nam.ece.upatras.gr
* Email: tranoris@ece.upatras.gr

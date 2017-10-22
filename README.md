TTM-Service: A TOSCA Templates marketplace and brokering RESTful service for Openastack based Cloud infrastructures
==========

TTM-Service  is a RESTful marketplace web service implementing marketplace solution for easily deploying TOSCA based templates  on Openstack infrastructures via OAuth2. The architecture consists of a Marketplace backend solution, a Marketplace frontend interface, and a Brokering service that accommodates marketplace requests and a client TTM Application container and application management tools for the various end-user devices/machines that will be supported. 


TTM-Service and brokering service, is a RESTful backend service build in java. Currently it runs in the Jetty container and needs MySQL to persist data. Apache CXF is used to implement the RESTful interface and Apache SHIRO as the Authentication and Authorization framework.  A java implementation for openstack API is called woorea and it is used to access resources on FIWARE Lab.
Main offered services are:
-	management of users and their resources
-	management of application
-	management of buns
-	management of the platform
-	brokering, orchestrating and provisioning on target machines
-	OAUTH2 login based to FIWARE Lab
-	Automated provisioning of machines on top of FIWARE Lab


Licenses
--------

The license for this software is [Apache 2 v2.1](./src/license/header.txt).

Contact
-------

For further information on collaboration, support or alternative licensing, please contact:

* Website: http://nam.ece.upatras.gr
* Email: tranoris@ece.upatras.gr

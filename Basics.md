




NFV :



NFV Architecture:

![Optional Text](https://github.com/kesavand/nfv/blob/master/Images/NFV_Architectural_framework.PNG)



NFV  Functional Blocks:
=======================


Virtualised Infrastructure Manager
----------------------------------

– controlling and managing(Allocation of resources & mantaining the inventory) the NFVI compute, storage and network
resources, within one operator’s infrastructure sub-domain

– collection and forwarding of performance measurements and events

- Collection of infrastructure fault information.

- Collection of information for capacity planning, monitoring, and optimization.

VNF Manager:
-----------
– lifecycle management of VNF instances (e.g. instantiation, update, query, scaling, termination)
– overall coordination and adaptation role for configuration and event reporting between NFVI and the E/NMS 


NFV Orchestrator:
----------------
– on-boarding of new Network Service (NS), VNF-FG and VNF Packages
– NS lifecycle management (including instantiation, scale-out/in,performance measurements, event correlation, termination)
– global resource management, validation and authorization of NFVI resource requests
– policy management for NS instances 

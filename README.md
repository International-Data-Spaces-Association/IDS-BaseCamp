# The IDS Base Camp
Similar to the Testbed the IDS-BaseCamp provides developers functioning components with just enough features to be usable for a secure and sovereign data exchange, yet its intended purpose is to enable developers to experiment with their own ideas and implement their visions, as out-of-pocket as they may be, in it, without any regard to the standardized specifications of the IDSA. 
Contrary to the MVDS the Base Camp is not confined by the criteria to use the minimal working state, but not only can, but is supposed to develop and explore new branches and possibilities of a dataspace. 

The ISD-BaseCamp is the unique solution provided by IDSA Head Office, as current best practice.

> **Warning**
> Software / Hardware prerequisites needed here

> **Warning**
> Skill - Level needed here

> **Warning**
> Will the experiments in the BaseCamp be in the Deployment scenarios too? I think they should stay in the BaseCamp and maybe be opened as a seperate project if it'd come to that.

The [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios) act as best practices and sources of inspiration on building data spaces. There, you will find various examples of implementation, along with experiments also run with the IDS Base Camp.

To find more information on implementing data spaces and a step-by-step classification of existing IDS documentation, you may check [How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces). 



# What are the components that are provided in the IDS-BaseCamp?
The Base Camp consists of: 
1. Two or more IDS connectors  
2. The [Certificate Authority (CA)](https://github.com/International-Data-Spaces-Association/IDS-testbed/tree/IDS-testbed-mvds/CertificateAuthority) granting X.509 certificates (not to be confused with certification)
3. The [Dynamic Attributes Provisioning Service (DAPS)](https://github.com/International-Data-Spaces-Association/omejdn-daps) to handle dynamic attributes and manage dynamic access tokens
4. [MetadataBroker](https://github.com/International-Data-Spaces-Association/metadata-broker-open-core) which is a registry for IDS Connector self-description documents.

![IDS-BaseCamp](/pictures/IDS-BaseCamp_1.0.png)

[Certification](https://internationaldataspaces.org/use/certification/) of all components and the operational environments is an additional trust layer, since it ensures the functionality of components work in clearly specified boundaries.

# How can I start experimenting with a Dataspace? 
To start with implementing a Dataspace, you can check the list of IDS-compliant components that are listed [on this page](https://github.com/International-Data-Spaces-Association/idsa/blob/main/how-to-build-data-spaces/3-Build-Components.md), which is part of the
[How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces) section, that explains the process of building data spaces in five steps.

:arrow_forward: And we recommend to use [IDS-testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) to ensure the compatibility and interoperability of the components you will be using in your MVDS.

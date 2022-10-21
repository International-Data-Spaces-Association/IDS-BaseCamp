# The IDS-BaseCamp
Similar to the [Testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed), the IDS-BaseCamp provides developers functioning components with just enough features to be usable for a secure and sovereign data exchange, yet its intended purpose is to enable developers to experiment with their own ideas and implement their visions, as out-of-pocket as they may be, in it, without any regard to the standardized specifications of the IDSA. This playground for ideas can be used before subjecting a developers idea to the testbed, in which the project would have to adhere to certain guidelines. 

Contrary to the [MVDS](https://github.com/International-Data-Spaces-Association/IDS-testbed/blob/master/minimum-viable-data-space/MVDS.md), the IDS-BaseCamp is not confined by the criteria of a minimal working state, it not only can, but is supposed to develop and explore new branches and possibilities of a dataspace.

The ISD-BaseCamp is the unique solution provided by IDSA Head Office, who will function as moderators.

> **Warning**
> Software / Hardware prerequisites needed here

> **Warning**
> Skill - Level needed here

The [IDS Deployment Scenarios](https://github.com/International-Data-Spaces-Association/IDS-Deployment-Scenarios) act as best practices and sources of inspiration on building data spaces. There, you will find various examples of implementation, along with experiments also run with the IDS-BaseCamp.

> **Note**
>The IDS-Deployment-Scenarios are not just for successful experiments, also feel free submit failures so everyone can learn from them

To find more information on implementing data spaces and a step-by-step classification of existing IDS documentation, you may check [How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces). 



# What are the components that are provided in the IDS-BaseCamp?
The IDS-BaseCamp consists of: 
1. Two or more IDS connectors  
2. The [Certificate Authority (CA)](https://github.com/International-Data-Spaces-Association/IDS-testbed/tree/IDS-testbed-mvds/CertificateAuthority) granting X.509 certificates (not to be confused with certification)
3. The [Dynamic Attributes Provisioning Service (DAPS)](https://github.com/International-Data-Spaces-Association/omejdn-daps) to handle dynamic attributes and manage dynamic access tokens
4. [MetadataBroker](https://github.com/International-Data-Spaces-Association/metadata-broker-open-core) which is a registry for IDS Connector self-description documents.

<p align="center">
<img src="/pictures/IDS-BaseCamp_1.0.png">
</p>

[Certification](https://internationaldataspaces.org/use/certification/) of all components and the operational environments is an additional trust layer, since it ensures the functionality of components work in clearly specified boundaries.

# How can I start experimenting with a Dataspace? 
To start with implementing a Dataspace, you can check the list of IDS-compliant components that are listed [on this page](https://github.com/International-Data-Spaces-Association/idsa/blob/main/how-to-build-data-spaces/3-Build-Components.md), which is part of the
[How to Build Data Spaces?](https://github.com/International-Data-Spaces-Association/idsa/tree/main/how-to-build-data-spaces) section, that explains the process of building data spaces in five steps.

:arrow_forward: If your components worked as intended you can take them to the [IDS-testbed](https://github.com/International-Data-Spaces-Association/IDS-testbed) to ensure their compatibility and interoperability with IDS-compliant components.

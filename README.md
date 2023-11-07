**IDS Basecamp**

The IDS basecamp is a software distribution of components to build and operate an IDS Data Space. It's a project build from an OSS repository which integrates contributions from differnet projects to allow us to work on a common code basis which: 

- makes it easy for data spaces to work on a basis of integrated components which are proven in productive environments
- allows all contributors to participate from the learnings and also investements from other projects 

The goal is to enable developers, testbeds and productive systems to be able to work on a common basis and leverage the power of many to constantly improve the code set whilst maintaining the highest level of interoperability. At the same time the efforts of project teams can shift from setup and integration of basic services towards the value of creating use cases. It includes experiences from commercial operators with validated security, scalability and maintainability requirements and is used in productive environments. It does not contain any proprietary elements and the project is available to all parties willing to contribute. It can be extended with additional components and services (like onboarding workflows, integration with ID or certificate providers, testbeds, different type of connectors). 

The general approach in building a distribution is a community process following the schema: 
- intensive research with the community on available software assets  
- improvement of the code base towards a production grade technical readiness level 
- packaging towards an integrated distribution  

Governance: IDSA assumes the role of GitHub Maintainer of the repository to ensure contributions by the committers are aligned with the IDSA reference architecture and specifications

v 1.0 of the Basecamp is a distribution following IDS RAM 4.0 and the EDC MS 0.8.

It consists of the following IDS based infrastructure components: 
CA, DAPS, ParIS, Metadata Broker, Transaction Log (Clearing House)


1. How to get started (truzzt Port umbenennen)

2. Core Repository 

3. Useful Extensions
- SGX...


Roadmap: "v Next"
* Extension to Vocabulary Provider, App Store
* Once RAM 5 and the protocol specs are finalized we will start planning for the next release



# <a name="_toc120026359"></a>**8. Brief description of Open Source Intel® SGX Technology**

For application and solution developers, new hardware-based controls for cloud and enterprise environments provide excellent opportunities to ensure high data security. Intel® Software Guard Extensions (Intel® SGX)1 2 provide hardware-based encryption of memory contents that isolates specific program code and data in memory. With Intel® SGX, application code can consume its own areas of memory, known as enclaves, that are protected from processes running at a higher privilege level. Only Intel® SGX offers this level of control and protection. (<https://www.intel.de/content/www/de/de/architecture-and-technology/software-guard-extensions.html>). 

Intel® SGX helps protect against many known and active threats. They form an additional layer of defense by helping to reduce the attack surface of the system.

The combination of Intel® SGX's enhanced security and verification capabilities, along with Intel's continued collaboration with a broad ecosystem of security companies, helps minimize the potential attack surface and even reduce theoretical risks.





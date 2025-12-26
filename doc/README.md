# Additional documentation

This directory provides additional and more detailed documentation about the FIWARE Data Space Connector, 
specific flows and its deployment and integration with other frameworks.

<!-- ToC created with: https://github.com/thlorenz/doctoc -->
<!-- Update with: doctoc README.md -->

<details>
<summary><strong>Table of Contents</strong></summary>

<!-- START doctoc generated TOC please keep comment here to allow auto update -->
<!-- DON'T EDIT THIS SECTION, INSTEAD RE-RUN doctoc TO UPDATE -->
<!-- param::isNotitle::true:: -->

- [Details about flows and interfaces](#details-about-flows-and-interfaces)
  - [Contract Management](#contract-management)
  - [M2M Service Interaction](#m2m-service-interaction)
- [Deployment / Integration](#deployment--integration)
  - [Local deployment of Minimal Viable Dataspace (helm/k3s)](#local-deployment-of-minimal-viable-dataspace-helmk3s)

<!-- END doctoc generated TOC please keep comment here to allow auto update -->


</details>



## Details about flows and interfaces

### Contract Management

The FIWARE Data Space Connector provides components to perform contract management based on the TMForum APIs. 

More information can be found here:
* [Contract Management](./flows/contract-management) - Information about the Contract Management and its 
  authentication/authorization
* [TMForum contract management example](./flows/contract-management/tmf) - Example requests to interact 
  with the TMForum APIs



### M2M Service Interaction

A detailed description about the steps to be performed in a Machine-To-Machine (M2M) service interaction 
can be found here:
* [Service Interaction (M2M)](./flows/service-interaction-m2m)





## Deployment / Integration

###  Minimal Viable Dataspace on Kubernetes using ArgoCD

This is an example of a "Minimal Viable Dataspace", consisting of a fictitious data service 
provider called M&P Operations Inc. (using the FIWARE Data Space Connector), a data service consumer 
called Fancy Marketplace Co. and the 
data space's trust anchor.

The service is provided by the Scorpio Context via the NGSI-LD API, offering access to 
energy report entities.

More information can be found here:
* [Local Deployment](./deployment-integration/local-deployment/LOCAL.MD)




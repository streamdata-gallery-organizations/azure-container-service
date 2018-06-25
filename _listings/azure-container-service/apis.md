---
name: Azure Container Service
x-slug: azure-container-service
description: Azure Container Service optimizes the configuration of popular open-source
  tools and technologies specifically for Azure. You get an open solution that offers
  portability for both your containers and your application configuration. You select
  the size, number of hosts, and choice of orchestrator tools&mdash;Container Service
  handles everything else.
image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
x-kinRank: "10"
x-alexaRank: "0"
tags: Azure Container Service
created: "2018-06-25"
modified: "2018-06-25"
url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/apis.md
specificationVersion: "0.14"
apis:
- name: Azure Container Service API Container Services List
  x-api-slug: azure-container-service-api
  description: Gets a list of container services in the specified subscription. The
    operation returns properties of each container service including state, orchestrator,
    number of masters and agents, and FQDNs of masters and agents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/providers/Microsoft.ContainerService/containerServices
  tags: Containers,Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidprovidersmicrosoft-containerservicecontainerservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidprovidersmicrosoft-containerservicecontainerservices-get-openapi.md
- name: Azure Container Service API Container Services Create Or Update
  x-api-slug: azure-container-service-api
  description: Creates or updates a container service with the specified configuration
    of orchestrator, masters, and agents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerService/containerServices/{containerServiceName}
  tags: Containers,Services
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-put-openapi.md
- name: Azure Container Service API Container Services Get
  x-api-slug: azure-container-service-api
  description: Gets the properties of the specified container service in the specified
    subscription and resource group. The operation returns the properties including
    state, orchestrator, number of masters and agents, and FQDNs of masters and agents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerService/containerServices/{containerServiceName}
  tags: Containers,Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-get-openapi.md
- name: Azure Container Service API Container Services Delete
  x-api-slug: azure-container-service-api
  description: Deletes the specified container service in the specified subscription
    and resource group. The operation does not delete other resources created as part
    of creating a container service, including storage accounts, VMs, and availability
    sets. All the other resources created with the container service are part of the
    same resource group and can be deleted individually.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerService/containerServices/{containerServiceName}
  tags: Containers,Services
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-delete-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservicescontainerservicename-delete-openapi.md
- name: Azure Container Service API Container Services List By Resource Group
  x-api-slug: azure-container-service-api
  description: Gets a list of container services in the specified subscription and
    resource group. The operation returns properties of each container service including
    state, orchestrator, number of masters and agents, and FQDNs of masters and agents.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com////subscriptions/{subscriptionId}/resourceGroups/{resourceGroupName}/providers/Microsoft.ContainerService/containerServices
  tags: 'Containers,Services '
  properties:
  - type: x-postman-collection
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservices-get-postman.md
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/subscriptionssubscriptionidresourcegroupsresourcegroupnameprovidersmicrosoft-containerservicecontainerservices-get-openapi.md
- name: Azure Container Service API
  x-api-slug: azure-container-service-api
  description: Azure Container Service optimizes the configuration of popular open-source
    tools and technologies specifically for Azure. You get an open solution that offers
    portability for both your containers and your application configuration. You select
    the size, number of hosts, and choice of orchestrator tools&mdash;Container Service
    handles everything else.
  image: http://kinlane-productions.s3.amazonaws.com/api-evangelist-site/company/logos/azure-container-service.png
  humanURL: https://azure.microsoft.com/en-us/services/container-service/
  baseURL: ://management.azure.com//
  tags: Azure Container Service
  properties:
  - type: x-openapi-spec
    url: https://raw.githubusercontent.com/streamdata-gallery-organizations/azure-container-service/master/_listings/azure-container-service/openapi.md
x-common:
- type: x-documentation
  url: https://docs.microsoft.com/en-us/azure/container-service/
- type: x-pricing
  url: https://azure.microsoft.com/en-us/pricing/details/container-service/
- type: x-service-level-agreements
  url: https://azure.microsoft.com/en-us/support/legal/sla/container-service/
- type: x-status
  url: https://azure.microsoft.com/en-us/status/
- type: x-website
  url: https://azure.microsoft.com/en-us/services/container-service/
include: []
maintainers:
- FN: Kin Lane
  x-twitter: apievangelist
  email: info@apievangelist.com
---